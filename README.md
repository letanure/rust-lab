# rust-lab
Learning rusty

## Hello, World!

https://doc.rust-lang.org/book/second-edition/ch01-02-hello-world.html

```
fn main() {
    println!("Hello, world!");
}
```

```
$ rustc main.rs
$ ./main
Hello, world!
```

## Hello, Cargo

Cargo is Rust’s build system and package manager,

```
$ cargo new hello_cargo --bin
$ cd hello_cargo
```

```
$ cargo build
$ ./target/debug/hello_cargo
# or
$ cargo run
```

