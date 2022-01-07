<h1>Rust para poder entrar a SOLANA</h1>

<h2>Comandos Rust</h2>

<strong>rustc <rust_file></strong>
<p>Compila código de Rust</p>

<strong>cargo new <project_name></strong>
<p>Crear un proyecto de Rust. Si no tiene git iniciado, lo crea.</p>

<strong>cargo build</strong>
<p>En la carpeta del proyecto, compila el código en la carpeta de ./target/debug/<project_name></p>

<strong>cargo run</strong>
<p>En la carpeta del proyecto, ejecuta el archivo compilado. Si el código cambia, vuelve a compilarlo</p>

<strong>cargo check</strong>
<p>Verifica que el código es correcto sin producir un ejecutable</p>

<strong>cargo buikd</strong> --release
<p>Compila con optimizaciones para producción. Benchmark debe ser so/pe release</p>

<h2>For GitHub projects</h2>
<ol>
    <li>git clone <project_url></li>
    <li>cargo build</li>
    <li>cd <project_path></li>
</ol>