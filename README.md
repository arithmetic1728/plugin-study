Reference: https://expobrain.net/2015/09/13/create-a-plugin-for-google-protocol-buffer/

Python version: 2.7

Commands to generate the Json file:
```
protoc --plugin=protoc-gen-custom=my-plugin.py --custom_out=./build hello_world.proto
```

plugin.proto: https://github.com/protocolbuffers/protobuf/blob/master/src/google/protobuf/compiler/plugin.proto
descriptor.proto: https://github.com/protocolbuffers/protobuf/blob/master/src/google/protobuf/descriptor.proto

