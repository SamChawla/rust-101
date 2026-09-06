# Rust 101

A hands-on learning path for Rust — from your first `println!` to advanced systems programming.

## What is this?

**Rust 101** is a structured, module-by-module course for learning Rust at your own pace. Each folder is a self-contained lesson with examples you can read, run, and modify.

**Level:** Beginner → Advanced

## Prerequisites

- Basic programming experience (variables, functions, loops) in any language
- [Rust installed](https://www.rust-lang.org/tools/install) (`rustc`, `cargo`, `rustup`)

Verify your setup:

```bash
rustc --version
cargo --version
```

## Learning path

| Module | Topic | Level |
|--------|-------|-------|
| `hello_rust/` | Hello, World — your first Rust program | Beginner |
| *Coming soon* | Variables, types, and mutability | Beginner |
| *Coming soon* | Ownership and borrowing | Beginner |
| *Coming soon* | Structs, enums, and pattern matching | Beginner |
| *Coming soon* | Error handling (`Result`, `Option`) | Intermediate |
| *Coming soon* | Collections and iterators | Intermediate |
| *Coming soon* | Traits and generics | Intermediate |
| *Coming soon* | Concurrency and async | Advanced |
| *Coming soon* | Unsafe Rust and FFI | Advanced |

## Getting started

1. Clone this repo
2. Open a module folder (start with `hello_rust/`)
3. Read the source, then compile and run:

```bash
cd hello_rust
rustc main.rs
./main        # Linux / macOS
.\main.exe    # Windows
```

As modules grow, many will use Cargo:

```bash
cargo run
```

## How to use this repo

- **Read** the code and comments in each module
- **Run** examples and observe the output
- **Experiment** — change values, break things, fix them
- **Progress** in order; later modules build on earlier ones

## Contributing

This is a living course. Suggestions and improvements are welcome.

## License

MIT
