# Go SDK for Quorum account plugins

## Quickstart

```shell
# account plugin sdk
go get github.com/jpmorganchase/quorum-account-plugin-sdk-go/proto

# plugin initialization sdk
go get github.com/jpmorganchase/quorum-account-plugin-sdk-go/proto_common

# mocks for testing
go get github.com/jpmorganchase/quorum-account-plugin-sdk-go/mock_proto
```

## Overview

[Quorum's pluggable architecture](https://docs.goquorum.com/en/latest/PluggableArchitecture/Overview/) allows for a Quorum node to be extended with additional functionality.

Quorum's default account management functionality can be [extended with `account` plugins](https://docs.goquorum.com/en/latest/Account-Key-Management/Quorum/account-Plugins/Overview/).

The communication between Quorum and an `account` plugin uses gRPC.

This SDK can be used to develop Go `account` plugins that fulfill Quorum's gRPC `account` plugin interface.  It provides the necessary Go types and methods for starting a new gRPC server, initializing a new plugin, and for handling Quorum gRPC requests.

***This repo is auto-updated***

*The [quorum-plugin-definitions](https://github.com/jpmorganchase/quorum-plugin-definitions) project defines the `account` plugin gRPC API.  A [GitHub Actions workflow](.github/workflows/run.yml) updates the SDK whenever quorum-plugin-definitions is altered.*
