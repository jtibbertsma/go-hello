# Hello world in Go

This repository exists so that I can test out the Go package system. Apparently the go compiler is smart enough to look at import statements in source files and clone the repositories. Also, using ```go get```, you can clone a repository, and use ```go install``` to compile the source and put the executable in $GOPATH/bin.

So, once I push this to github, anybody should be able to do

```bash
$ go get github.com/jtibbertsma/go-hello
$ go install github.com/jtibbertsma/go-hello/hello_go
$ hello_go
```

and it should print out "Hello, World!".

This is my first Go program. After this, I'm thinking about trying to write an http server to better understand the http protocol and to learn about Go style concurrent programming.