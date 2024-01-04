# Favorite Golang

- [Packages](#packages)
  - [HTTP](#http)
  - [Logging](#logging)
  - [Testing](#testing)
  - [Utilities](#utilities)
  - [Databases](#databases)
  - [Background tasks](#background-tasks)

- [Tools](#tools)
  - [Linters](#linters)
  - [Editors](#editors)
  - [Network](#network)
  - [Debugging](#debugging)
  - [Development](#development)

- [Resources](#resources)
  - [Media](#media)
  - [Tutorials](#tutorials)
  - [Useful notes](#useful-notes)

## Packages

### HTTP

* [chi](https://github.com/go-chi/chi) - Router compatible with net/http

### Logging

* [slog](https://pkg.go.dev/log/slog) - Structured and leveled logging

### Testing

* [testify](https://github.com/stretchr/testify) - Toolkit for assertions and mocking
* [fstest](https://golang.org/pkg/testing/fstest) - FS and File implementations designed for tests
* [httptest](https://pkg.go.dev/net/http/httptest) - Utilities for testing HTTP requests

### Utilities

* [do](https://github.com/samber/do) - Dependency injection toolkit
* [lo](https://github.com/samber/lo) - Lodash-style library (map, filter, contains, find...)
* [mo](https://github.com/samber/mo) - Monads and popular FP abstractions (Option, Result...)

### Databases

* [redis](https://github.com/go-redis/redis) - Redis client
* [pgx](https://github.com/jackc/pgx) - PostgreSQL driver
* [clickhouse-go](https://github.com/ClickHouse/clickhouse-go) - ClickHouse driver
* [ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) - YDB driver
* [goose](https://github.com/pressly/goose) - A database migration tool
* [hasql](https://github.com/yandex/go-hasql) - Library for accessing multi-host SQL database installations

### Background tasks

* [gocron](https://github.com/go-co-op/gocron) - Job scheduling package which lets you
  run functions periodically

## Tools

### Linters

* [golangci-lint](https://github.com/golangci/golangci-lint) - Go linters runner that includes a lot of linters

### Editors

* [Goland](https://www.jetbrains.com/go) - IDE that contains everything you need for Go development
* [VSCode Go](https://github.com/golang/vscode-go) - Extension for VSCode that provides rich support for Go

### Network

* [GoReplay](https://github.com/buger/goreplay) - Network monitoring tool which can
  record your live traffic, and use it for shadowing, load testing, monitoring and
  analysis

### Debugging

* [Delve](https://github.com/go-delve/delve) - Simple, full featured debugging tool

### Development

* [gopls](https://github.com/golang/tools/blob/master/gopls) - Official Go language server
* [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - Tool that updates import lines, adding missing ones and removing unreferenced ones

## Resources

### Media

* [Reddit r/golang](https://www.reddit.com/r/golang)
* [Twitter @golang](https://twitter.com/golang)
* [Telegram @golang](https://t.me/golang)
* [Telegram @golang_google](https://t.me/golang_google) [RU]

### Tutorials

* [A Tour of Go](https://tour.golang.org)
* [Learn Go with tests](https://quii.gitbook.io/learn-go-with-tests)

### Useful notes

* [Constant errors](https://dave.cheney.net/2016/04/07/constant-errors)
* [Go _test packages](https://jdkaplan.dev/thinkin-logs/2021-10-07)
* [Mutex or channels?](https://github.com/golang/go/wiki/MutexOrChannel)
* [Printing cheatsheet](https://pkg.go.dev/fmt#hdr-Printing)
* [Formatting and parsing time](https://programming.guide/go/format-parse-string-time-date-example.html)
* [Maps are not reference variables](https://dave.cheney.net/2017/04/30/if-a-map-isnt-a-reference-variable-what-is-it)
* [Proper package naming for testing](https://stackoverflow.com/questions/19998250/proper-package-naming-for-testing-with-the-go-language)
