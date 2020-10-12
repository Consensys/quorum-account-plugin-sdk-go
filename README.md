# Go SDK for Quorum account plugins

## Quickstart

```shell
# account plugin sdk
go get github.com/ConsenSys/quorum-account-plugin-sdk-go/proto

# plugin initialization sdk
go get github.com/ConsenSys/quorum-account-plugin-sdk-go/proto_common

# mocks for testing
go get github.com/ConsenSys/quorum-account-plugin-sdk-go/mock_proto
```

## Overview

[Quorum's pluggable architecture](https://docs.goquorum.consensys.net/en/latest/Concepts/Plugins/Plugins/) allows for a Quorum node to be extended with additional functionality.

`account` plugins [extend Quorum's default account management functionality](https://docs.goquorum.consensys.net/en/latest/HowTo/ManageKeys/AccountPlugins/).

The communication between Quorum and an `account` plugin uses gRPC.

This SDK can be used to develop Go `account` plugins that fulfill Quorum's gRPC `account` plugin interface.  It provides the necessary Go types and methods for starting a new gRPC server, initializing a new plugin, and for handling Quorum gRPC requests.

***This repo is auto-updated***

*The [quorum-plugin-definitions](https://github.com/ConsenSys/quorum-plugin-definitions) project defines the `account` plugin gRPC API.  A [GitHub Actions workflow](.github/workflows/run.yml) updates the SDK whenever quorum-plugin-definitions is altered.*
