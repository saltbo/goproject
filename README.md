# goproject

A simple Go project template.

## Prerequisites
- Go 1.20 or later
- gonew tool (install via `go install golang.org/x/tools/cmd/gonew@latest`)

## Usage

```bash
gonew github.com/saltbo/goproject github.com/yourusername/yourproject
cd yourproject
go mod tidy
go run main.go
```