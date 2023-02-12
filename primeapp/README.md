# Project to learning purpose

Run all tests

```
go test .
```

Run all tests "-v" verbose.

```
go test -v .
```

Run specific test

```
go test -run {test_name}
```

Run test suite

```
go test -run {test_name_suite}
```

Run test with coverage info

```
go test -cover .
```

Generate output about tests

```
go test -coverageprofile=coverage.out
```

Show details in the browser based on output generated previously

```
go tool cover -html=coverage.out
```
