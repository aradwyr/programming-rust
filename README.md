To bring up Rust docs: `rustup doc --std`

To run program: `cargo run 42 56`

Section Notes: 
- `eprintln!` and `assert!` are called macros
- Vec is Rust's growable vector type, analogous to a Python list or JS array
- the `&` operator in &numbers[1..] borrows a reference to the vector's elements
- the `*` operator in *m dereferences m aka the value that the reference m refers to
- since numbers owns the vector, Rust auto frees it when numbers goes out of scope at the end of main 