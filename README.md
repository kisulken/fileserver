# Simple file server written in Golang

## Installation
Build from the source
```bash
$ go get -u github.com/kardianos/osext
$ go get -u github.com/kisulken/fileserver
```
Or check out the [pre-built binaries](https://github.com/kisulken/fileserver/releases)

Simple file server that shares access to a directory on a selected port

## CLI Usage

```bash
$ fileserver 5555 "/users/username/documents/public"
```

This command will share the access of /users/username/documents/public on the port 5555.
Now, you should be able to access that directory using a web browser at http://localhost:5555/
