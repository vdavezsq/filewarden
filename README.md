# filewarden

Go CLI that organizes a messy folder by file extension

Small but I use it weekly.

## Examples

```bash
./bin/filewarden ~/Downloads --dry-run
./bin/filewarden ~/Downloads
```

## Installation

```bash
go build -o bin/ ./...
```

## What it does

- Single static binary, no runtime deps
- Dry-run prints the plan before moving anything
- Groups files into folders by extension
- Skips hidden files and folders by default

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## 说明

个人练习项目, 谨慎用于生产环境。
