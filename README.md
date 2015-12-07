# sample-golang-context
Sample Golang net/context


## Install dependencies
```
$ gom install
```


## Start server
```
$ ./vendor/bin/fresh
```


## Request server
```
$ http http://localhost:8080/ X-Request-ID:my-req-id
HTTP/1.1 200 OK
Content-Length: 28
Content-Type: text/plain; charset=utf-8
Date: Mon, 07 Dec 2015 10:53:33 GMT

Hello request ID: my-req-id
```
