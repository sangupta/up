# up

Simple HTTP server.

# Hacking

# Running locally

```sh
$ git clone git@github.com/sangupta/up.git
$ cd up
$ go build
```
# Release

To build a production mode binary, use the following command:

```sh
$ go build -ldflags="-s -w" main.go
$ upx --best -k ./up
```

# License

MIT License. Copyright (c) 2022, Sandeep Gupta.
