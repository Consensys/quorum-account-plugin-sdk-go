**Note:** Github workflow is only triggered via an webhook event which is dispatched by `quorum-plugin-definitions`

## SDK for Quorum account plugin interface

The SDK is auto generated from `quorum-plugin-definitions` proto files using `protoc` compiler 3.9.1

- `proto` package contains stubs generated from `protoc` compiler
- `mock_proto` package contains mocks for unit testing

```
go get github.com/jpmorganchase/quorum-account-plugin-sdk-go/proto
go get github.com/jpmorganchase/quorum-account-plugin-sdk-go/mock_proto
```