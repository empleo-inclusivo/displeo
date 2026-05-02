# displeo
iseño simple, colores claros y fácil de usar. Incluye buscador con filtros, lista de empleos con botón para aplicar, sección de recursos, testimonios y contacto. Debe ser accesible, con lectura de pantalla, navegación con teclado y texto en imágenes.
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Empleo Inclusivo</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f4f4f4;
}
header {
    background: #2d89ef;
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    background: #1b5fa7;
    padding: 10px;
    text-align: center;
}
nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}
.container {
    padding: 20px;
}
.card {
    background: white;
    padding: 15px;
    margin: 10px 0;
    border-radius: 8px;
}
button {
    background: #2d89ef;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>
</head>

<body>

<header>
<h1>Empleo Inclusivo</h1>
<p>Oportunidades laborales para todos</p>
</header>

<nav>
<a href="#">Inicio</a>
<a href="#">Empleos</a>
<a href="#">Recursos</a>
<a href="#">Contacto</a>
</nav>

<div class="container">

<h2>Buscar empleo</h2>
<input type="text" placeholder="Buscar trabajo..." style="padding:10px;width:80%;">

<h2>Ofertas laborales</h2>

<div class="card">
<h3>Asistente Administrativo</h3>
<p>Empresa: Inclusiva SAC</p>
<p>Ubicación: Lima</p>
<button>Aplicar</button>
</div>

<div class="card">
<h3>Diseñador Gráfico Remoto</h3>
<p>Empresa: Creativa Studio</p>
<p>Ubicación: Remoto</p>
<button>Aplicar</button>
</div>

<h2>Recursos</h2>
<p>Consejos para entrevistas, derechos laborales y formación gratuita.</p>

<h2>Testimonios</h2>
<p>"Gracias a esta plataforma encontré trabajo fácilmente." - Usuario</p>

</div>

<footer>
<p>Contacto: info@empleoinclusivo.com</p>
</footer>

</body>
</html>
