# up

Simple HTTP server.

# Hacking
To build a production mode binary, use the following command:

```sh
$ go build -ldflags="-s -w" cli/bundle/primeshell.go
$ upx --best -k ./primeshell
```

# License

MIT License. Copyright (c) 2022, Sandeep Gupta.
