# index.html.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solarpar - Electricidad y Fotovoltaica</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #ffcc00;
            padding: 20px;
            text-align: center;
            color: #222;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: 280px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
        @media (max-width: 600px) {
            .services {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Solarpar</h1>
    <p>Electricidad y Energía Solar Fotovoltaica</p>
</header>

<nav>
    <a href="#servicios">Servicios</a>
    <a href="#proyectos">Proyectos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="servicios">
    <h2>Nuestros Servicios</h2>
    <div class="services">
        <div class="card">
            <h3>Instalaciones Fotovoltaicas</h3>
            <p>Paneles solares para autoconsumo residencial e industrial.</p>
        </div>
        <div class="card">
            <h3>Instalaciones Eléctricas</h3>
            <p>Proyectos eléctricos para obra nueva y reformas.</p>
        </div>
        <div class="card">
            <h3>Mantenimiento</h3>
            <p>Revisión y reparación de sistemas eléctricos y solares.</p>
        </div>
    </div>
</section>

<section id="proyectos">
    <h2>Proyectos Realizados</h2>
    <p>Muy pronto mostraremos nuestras instalaciones más recientes.</p>
</section>

<section id="nosotros">
    <h2>Sobre Solarpar</h2>
    <p>Somos una empresa especializada en soluciones eléctricas y energías renovables, comprometidos con la calidad y la sostenibilidad.</p>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>Email: <a href="mailto:info@solarpar.com">info@solarpar.com</a></p>
    <p>Teléfono: <a href="tel:+34123456789">+34 123 456 789</a></p>
</section>

<footer>
    <p>© 2025 Solarpar - Todos los derechos reservados</p>
</footer>

</body>
</html>
