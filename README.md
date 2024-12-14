# Go: Panic on nil map access

This repository demonstrates a common runtime error in Go: panicking due to accessing a nil map.  Go doesn't perform compile-time checks for nil map accesses; instead, it results in a runtime panic.

The `bug.go` file shows the problematic code. The `bugSolution.go` provides a solution to handle potential nil map values safely.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `go run bug.go`. You'll observe a panic.

## Solution

Refer to `bugSolution.go` for a robust way to avoid the panic.
