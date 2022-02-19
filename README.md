# GoLang Rest API
We are creating a JSON API that will allow to create, read, update and delete events

## Prerequisites

* Have Go installed. If not, check it out [here](https://golang.org/doc/install) or [download](https://go.dev/dl/)

* Also after installing, make sure you are working inside your GOPATH

## Getting Started 🚀

    mkdir GoLang-REST-API
    cd GoLang-REST-API
    go mod init GoLang-REST-API
    go run hello.go
    go test

## Install packages
    go get -u github.com/gorilla/mux
    go run main.go

Run sever on [http://localhost:8080/](http://localhost:8080/) and use for Ctrl + C to trun off server.

## Tutorial

* [Build a RESTful JSON API with GOlang](https://medium.com/the-andela-way/build-a-restful-json-api-with-golang-85a83420c9da) with [code](https://github.com/Duncanian/go-rest-api/blob/develop/main.go)

* [Building basic RESTful (CRUD) with Golang & MySQL](https://towardsdev.com/building-basic-restful-crud-with-golang-mysql-6869dfdefade) with  [code](https://github.com/Vishalj32/rest-go-demo)

* [Example go-json-res](https://github.com/ant0ine/go-json-rest)


## References

* [Installation](https://www.geeksforgeeks.org/how-to-install-golang-on-macos/)
* [Get package](https://stackoverflow.com/questions/55631569/go-mod-cannot-find-module-providing-package)


## Nodemon + Go  🚀

When developing an application in the go language, it is necessary to restart it every time through the console in order to apply new changes, this is not convenient.

Install nodemon globally

    npm install -g nodemon

For easy launch of the application, I will create a Makefile.

    run:
	    nodemon --exec go run main.go

Here to nodemon we pass the launch parameters and the application itself.

To run the application

    make run
