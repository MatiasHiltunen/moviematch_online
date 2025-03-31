# moviematch_online

Example project for Cross Platform Mobile Application Development course

## Compiling Proto

_This is needed first: https://protobuf.dev/installation/, must be added to PATH after extracting the .zip file, fe. in Windows to User Environment Variables_

protoc --dart_out=grpc:lib/generated -Iprotos protos/moviematch.proto

## Start Server

Start the server in another terminal from project's path:

- `dart run .\lib\server\server.dart`

## Getting Started

- After server is running, you can start the app, for example with `flutter run`
- Project assumes that you are using android emulator and has included the emulator localhost proxy to /lib/providers/moviematch.dart: `10.0.2.2`. If you are not using Android emulator, replace that with `localhost`

