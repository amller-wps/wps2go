# WPS To Go
![](wps2go.svg)

## TODOs:
- Maps: `present` sollte "ok" heißen. Es gibt ein eigenes Idiom zu diesem "Pattern". Das so genannte "Comma OK Idiom"
- Generics: Sadly they are not there yet :(

## Prerequisites

Visit: https://play.golang.org  (Note: There are some restrictions)
OR  
Install Go from here https://golang.org/dl.  
We recommend VS Code as text editor in combination with the official Go-Extension (https://marketplace.visualstudio.com/items?itemName=golang.Go) or JetBrains GoLand (https://www.jetbrains.com/go/) (requires a license). But any other text will work, too.

## Commands & Tooling
- `go help` Lists Help for the given command or topic.
- `go run` Runs the given Go file. (Use . to run everything in the current directory).
- `go build` Compiles the package.
- `go test` Runs tests.
- `go generate` Generate Go files. See https://go.dev/blog/generate for more info.
- `go get` Adds dependencies to the current module and installs them
- `go mod` Command to manage modules. See the topics listed in `go help` related to modules.
- `go tool` runs a Go tool

## Cross compilation
Set the `GOOS` environment variable to the target OS (Allowed by default: `aix`, `android`, `darwin` (macOS and iOS), `dragonfly`, `freebsd`, `hurd`, `illumos`, `js`, `linux`, `netbsd`, `openbsd`, `plan9`,  `solaris`, `windows`, `zos`) and the `GOARCH` environment variable for the target architecture (You will most probably use `amd64`, `arm64` or `386`). See https://golang.org/doc/install/source for more information. `go tool dist list` shows all supported platforms.

## Structure of a Go Program
- Be as simple as possible, but not simpler than that!
- Use a structure that works best for you.
- It is a valid approach to keep everything in one single package.
- Domain Driven Design works in Go, too. (https://youtu.be/oL6JBUk6tj0)

## Exercises
- Modules: Invoke the function `F` from the `wps2go` Module. Note: The Repository is located at `github.com/`

## Resources
- https://pkg.go.dev/std
- https://golang.org/doc
- https://go-proverbs.github.io/
- https://go.dev/blog/
- https://gobyexample.com
- https://forum.golangbridge.org/
- https://groups.google.com/g/golang-nuts
- https://stackoverflow.com/collectives/go
- https://www.reddit.com/r/golang/
- https://www.amazon.de/Go-Programming-Blueprints-Second-English/dp/1786468948
- http://www.gopl.io/
