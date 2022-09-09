# up

Simple HTTP server.

# Hacking
To build a production mode binary, use the following command:

```sh
$ go build -ldflags="-s -w" main.go
$ upx --best -k ./up
```

# License

MIT License. Copyright (c) 2022, Sandeep Gupta.
