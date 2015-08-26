# episode-003
Where we print a formatted message

## Setup
The following needs to be prepared

* A `cargo` created [Rust][rust-lang] named `printing`
* An editor with the project open

## Script
Having setup our [Rust][rust-lang] environment, it is time we explore the language.

As a starting point I let `cargo` create a new project. Lets run it to see we are in a working system. I setup the editor to execute `cargo run` on `Command-B`. We can see the output below.

The `println!` [macro][macro] has a trick up its sleave. Change the expression to

```rust
println!("Hello, {}!", "world");
```

When we run it we see that `println!` can accept an argument. The argument `"world"` is replaced with the placeholder `{}`, sometimes called a mustache pair.

`println!` can accept multiple arguments. For example

```rust
println!("{}, {}!", "Hello", "world");
```

works just as well.

And there you have it, we printed a formatted message



[rust-lang]: https://www.rust-lang.org/
[macro]: https://doc.rust-lang.org/stable/book/macros.html
