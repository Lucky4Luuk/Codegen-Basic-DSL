# DSL
Basic DSL meant for code generation

## Syntax
### Variable declaration
```
fn main() {
  var a = 8
  var b = 3
  var c = a + b
  print("c: ", c)
}
```

### Functions
```
fn foo(a) {
  print("a: ", a)
}

fn main() {
  foo(5)
}
```

### Built-in
`print(a, b, c, ...) //Prints variables to stdout`
`sqrt(a) //Takes the square root of a`
`pow(a, b) //Takes a to the power of b`
