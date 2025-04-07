- **Running Code**:
  - `go run` compiles and executes a Go program.

- **Building Executables**:
  - `go build` compiles Go source code into an executable binary.

- **Testing Code**:
  - `go test` runs tests in the current package.
  - `go test ./...` runs tests in all subdirectories.

- **Package Management (with Modules)**:
  - `go mod init` initializes a new module (Go project) and creates a `go.mod` file.
  - `go get` downloads and installs packages and dependencies.
  - `go mod tidy` removes any dependencies that are no longer necessary.
  - `go list -m all` lists all dependencies for the current module.

- **Documentation**:
  - `go doc` shows documentation for a package or symbol.

- **Dependency Analysis**:
  - `go list` lists information about available packages.
  - `go list -m -versions <module>` lists all known versions of a module.

- **Code Formatting**:
  - `go fmt` formats Go source code.

- **Environment**:
  - `go env` prints Go environment information.
