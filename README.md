- create a directy 
- cd to the directory 
- go mod init demo

- to run

- compiles + links + creates binary + executes 

```
go run main.go
```

- to build 

```
go build main.go

```

- to get the list of go os and go arch

```
go tool dist list 
```

- cross compilation
```
GOARCH=amd64 GOOS=windows go build -o hello.exe main.go 
```
# Keywords

- package, func , import , if, else, switch, return, default, break, continue, var, const,case, map, range

# builtin functions

- print , println, len,cap, append, copy, make, delete




Tasks: Go to the tasks/ directory to find tasks
https://github.com/JitenPalaparthi/golang-training-questglobal