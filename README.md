# Euro-marketing.site 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tu Agencia de Marketing Digital - Impulsamos tu éxito en línea">
    <title>Marketing Digital</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

  <section id="inicio">
        <div class="container">
            <h1>Tu Éxito en Línea Comienza Aquí</h1>
            <p>Somos una agencia de marketing digital dedicada a impulsar tu presencia en línea y aumentar tus conversiones.</p>
            <a href="#contacto" class="cta-button">Contáctanos</a>
        </div>
    </section>

  <section id="servicios">
        <div class="container">
            <h2>Nuestros Servicios</h2>
            <div class="services">
                <div class="service">
                    <h3>SEO (Optimización de Motores de Búsqueda)</h3>
                    <p>Mejoramos tu clasificación en los motores de búsqueda para aumentar la visibilidad.</p>
                </div>
                <div class="service">
                    <h3>Publicidad en Redes Sociales</h3>
                    <p>Creamos estrategias de publicidad efectivas en redes sociales.</p>
                </div>
                <div class="service">
                    <h3>Email Marketing</h3>
                    <p>Llega a tu audiencia de manera personalizada y efectiva.</p>
                </div>
                <div class="service">
                    <h3>Desarrollo Web</h3>
                    <p>Diseñamos sitios web modernos y atractivos que convierten visitantes en clientes.</p>
                </div>
            </div>
        </div>
    </section>

  <section id="portfolio">
        <div class="container">
            <h2>Nuestro Portfolio</h2>
            <div class="project">
                <img src="proyecto1.jpg" alt="Proyecto 1">
                <h3>Proyecto de SEO Exitoso</h3>
                <p>Aumentamos el tráfico orgánico en un 150% para nuestro cliente en la industria de la moda.</p>
            </div>
            <div class="project">
                <img src="proyecto2.jpg" alt="Proyecto 2">
                <h3>Campaña en Redes Sociales</h3>
                <p>Generamos un aumento del 30% en la participación de los usuarios en una campaña en Instagram.</p>
            </div>
        </div>
    </section>

  <section id="contacto">
        <div class="container">
            <h2>Contacta con Nosotros</h2>
            <p>¡Contáctanos para descubrir cómo podemos ayudarte a alcanzar tus objetivos de marketing digital!</p>
            <form action="procesar.php" method="post">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                <label for="correo">Correo Electrónico:</label>
                <input type="email" id="correo" name="correo" required>
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

   <footer>
        <div class="container">
            <p>&copy; 2023 Tu Agencia de Marketing Digital</p>
        </div>
    </footer>

  <script src="script.js"></script>
</body>
</html>


