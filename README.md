# Pagina-HTML-basica
Una pagina de presentacion basica hecha con html y css
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página de Perfil</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>¡Hola! Soy Joan Aguirre 👋</h1>
        <p>Estudiante de Ingeniería de Software, apasionado por la tecnología.</p>
    </header>

    <section class="perfil">
        <img src="https://via.placeholder.com/150" alt="Foto de perfil">
        <div class="info">
            <h2>Sobre mí</h2>
            <p>
                Tengo 19 años y me encanta aprender sobre diseño web, videojuegos y música. 
                En mi tiempo libre, juego basket y practico piano 🎹.
            </p>
        </div>
    </section>

    <section class="habilidades">
        <h2>Mis habilidades</h2>
        <ul>
            <li>🎨 Dibujo digital</li>
            <li>💻 Programación básica</li>
            <li>📱 Diseño de interfaces</li>
        </ul>
    </section>

    <section class="contacto">
        <h2>Contáctame</h2>
        <p>Puedes escribirme a: <a href="mailto:ana.estudiante@gmail.com">joan.estudiante@gmail.com</a></p>
    </section>

    <footer>
        <p>© 2025 Creado por Joan Aguirre | Proyecto educativo</p>
    </footer>
</body>
</html>
CSS 
/* Estilos básicos de la página */
body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f2f7ff;
    color: #333;
}

/* Encabezado */
header {
    background-color: #0056d6;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

header p {
    margin-top: 10px;
    font-size: 1.1em;
}

/* Sección de perfil */
.perfil {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 40px;
    gap: 20px;
}

.perfil img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid #0056d6;
}

.perfil .info {
    max-width: 400px;
}

/* Sección de habilidades */
.habilidades {
    background-color: #e9f0ff;
    padding: 40px;
    text-align: center;
}

.habilidades ul {
    list-style: none;
    padding: 0;
}

.habilidades li {
    margin: 10px 0;
    font-size: 1.1em;
}

/* Sección de contacto */
.contacto {
    padding: 40px;
    text-align: center;
}

.contacto a {
    color: #0056d6;
    font-weight: bold;
    text-decoration: none;
}

.contacto a:hover {
    text-decoration: underline;
}

/* Pie de página */
footer {
    background-color: #0056d6;
    color: white;
    text-align: center;
    padding: 15px;
    font-size: 0.9em;
}

