This is a companion repo for the [HTMX & Go with ThePrimeagen](https://frontendmasters.com/courses/htmx) course on [Frontend Masters](https://frontendmasters.com).

[YouTube link](https://www.youtube.com/watch?v=x7v6SNIgJpE)

[Class materials link](https://theprimeagen.github.io/fem-htmx/)

## Setup

Add Air package for hot reload

```bash
go install github.com/cosmtrek/air@latest
```

Add alias for convenient development

```bash
path+=('~/go/bin')
alias air='~/go/bin/air'
```

## Development

`air` - to start server with hot reloading

`go run cmd/main.go` - to run server without hot reloading

`go run cmd/class-examples/main.go` - to run example server
