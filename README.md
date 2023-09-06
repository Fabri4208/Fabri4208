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
        <!-- Agregar el menú desplegable de idioma -->
        <select id="languageSelect">
            <option value="es" selected>Español</option>
            <option value="en">English</option>
        </select>
    </header>

 <section id="inicio">
        <div class="container">
            <h1>Tu Éxito en Línea Comienza Aquí</h1>
            <p>Somos una agencia de marketing digital dedicada a impulsar tu presencia en línea y aumentar tus conversiones.</p>
            <p>¿Por qué elegirnos?</p>
            <ul>
                <li>✔️ Experiencia y conocimientos en marketing digital</li>
                <li>✔️ Estrategias personalizadas para tu negocio</li>
                <li>✔️ Resultados medibles y comprobados</li>
            </ul>
            <p>No dejes pasar esta oportunidad para llevar tu negocio al siguiente nivel. ¡Contáctanos hoy mismo!</p>
            <a href="#contacto" class="cta-button">Contáctanos</a>
        </div>
    </section>
    <!-- Resto de tu contenido en español -->

  <footer>
        <div class="container">
            <p>&copy; 2023 Tu Agencia de Marketing Digital</p>
        </div>
    </footer>

   <script>
        const languageSelect = document.getElementById('languageSelect');

        languageSelect.addEventListener('change', function() {
            const selectedLanguage = languageSelect.value;
            const url = `index-${selectedLanguage}.html`; // Cambia 'index' por el nombre de tu página principal
            window.location.href = url;
        });
    </script>
</body>
</html>






