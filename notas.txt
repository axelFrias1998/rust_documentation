rustc <rust_file> --> Compila código de Rust
cargo new <project_name> --> Crear un proyecto de Rust. Si no tiene git iniciado, lo crea.
cargo build --> en la carpeta del proyecto, compila el código en la carpeta de ./target/debug/<project_name>
cargo run --> en la carpeta del proyecto, ejecuta el archivo compilado. Si el código cambia, vuelve a compilarlo
cargo check --> verifica que el código es correcto sin producir un ejecutable
cargo buikd --release --> compila con optimizaciones para producción. Benchmark debe ser sobre release

For GitHub projects
git clone <project_url>
cd <project_path>
cargo build