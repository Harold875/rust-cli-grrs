# Ejecutar el programa

De esta forma se ejecuta la CLI (utilizando cargo)
```bash
cargo run -- some-pattern some-file
```

*forma de usar el `--help`*

```bash
cargo run -- --help
```


##  version 1

ejemplo de uso:

```bash
cargo run -- main src/main.rs
```

> Lo que hace es buscar la palabra main en el archivo src/main.rs del proyecto.

output:
```
fn main() {
```