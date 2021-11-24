## Notes about Rust

### Functions
* ***fn*** defines functions
* ***{}*** encompase functions
* ***main*** is a special function because it is the entry point for all programs. It holds other functions
* Functions options
    * ***name: &str*** is a parameter of a function
    * ***-> &str*** is the return value type

```rust
    fn say_my_name(name: &str) -> &str {
        name
    }
```