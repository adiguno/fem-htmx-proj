## sertup

- edit .zshrc file (`ls -a` to see all(hidden) files)
  - export GOPATH env var
  - add alias for air

```bash
  # hot reload for go servers using air
  path+=('~/go/bin')
  alias air='~/go/bin/.air'
```

## commands

`air` starts the program

- commnad not recognized
- `go get github.com/cosmtrek/air`
  go install github.com/cosmtrek/air@latest

- firstly find `.air.toml` in current directory, if not found, use defaults
  `air -c .air.toml`

## task 1

- [ ] display a count that shows how many times a page has been requested

[![Frontend Masters](https://static.frontendmasters.com/assets/brand/logos/full.png)](https://frontendmasters.com)

This is a companion repo for the [HTMX & Go with ThePrimeagen](https://frontendmasters.com/courses/htmx) course on [Frontend Masters](https://frontendmasters.com).
