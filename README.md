<h1>Rust para poder entrar a SOLANA</h1>

<h2>Comandos Rust</h2>

<strong>rustc <rust_file></strong> --> Compila código de Rust
<strong>cargo new <project_name></strong> --> Crear un proyecto de Rust. Si no tiene git iniciado, lo crea.
<strong>cargo build</strong> --> en la carpeta del proyecto, compila el código en la carpeta de ./target/debug/<project_name>
<strong>cargo run</strong> --> en la carpeta del proyecto, ejecuta el archivo compilado. Si el código cambia, vuelve a compilarlo
<strong>cargo check</strong> --> verifica que el código es correcto sin producir un ejecutable
<strong>cargo buikd</strong> --release --> compila con optimizaciones para producción. Benchmark debe ser sobre release

For GitHub projects
git clone <project_url>
cd <project_path>
cargo build