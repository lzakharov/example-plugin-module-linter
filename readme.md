This is an example linter that can be used as a plugin for `golangci-lint`.

Build custom binary:
```sh
golangci-lint custom
```

Run example plugin:
```sh
./custom-gcl run -c .golangci.example.yml -Eexample testdata/src/testlintdata/todo/todo.go
```
