# Basic RPC Client

Demonstartes a simple RPC client that connects to a server and performs CRUD operations, [original tutorial](https://www.youtube.com/watch?v=1MPWPq2N768&t=802s)

**output**

```bash
$ go run main.go
Serving on port 4040
```

client

```bash
$ go run main.go

Database [{first A first item} {second A second item} {third A third item}]
Database [{first A first item} {second A new second item} {third A third item}]
Reply {first A first item}

```
