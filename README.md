# juego_preguntas_rust_ddr
paso a paso ejecucion local
1. Descargar e instalar Cargo: Cargo es la herramienta de gestión de paquetes y compilación de Rust. Para instalarlo, sigue estos pasos:

Visita rustup.rs y sigue las instrucciones para instalar Rust y Cargo.
En sistemas Unix, puedes usar el siguiente comando:
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

2. Crear y ejecutar un proyecto localmente: Una vez instalado Cargo, puedes crear un nuevo proyecto con:

cargo new nombre_del_proyecto
cd nombre_del_proyecto

Para compilar y ejecutar el proyecto, usa:

cargo run

3. Subir el código a un repositorio: Para subir tu proyecto a un repositorio, sigue estos pasos:

Inicializa un repositorio Git en tu proyecto:
git init
git add .
git commit -m "Initial commit"

Sube el código a un servicio como GitHub:
git remote add origin https://github.com/tu_usuario/nombre_del_repositorio.git
git push -u origin master

4. Añadir librerías (dependencias): Para añadir librerías a tu proyecto, edita el archivo Cargo.toml y agrega las dependencias bajo la sección [dependencies]. Por ejemplo, para añadir la librería rand:

[dependencies]
rand = "0.8"

Luego, ejecuta:

cargo build

Esto descargará e instalará las dependencias necesarias.
