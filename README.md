<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transporte Puerta a Puerta</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Sección Principal (Hero) -->
    <header class="hero">
        <div class="hero-content">
            <h1>Servicio de Transporte Puerta a Puerta</h1>
            <p>Desde tu puerta hasta el destino que elijas, con comodidad y confianza.</p>
            <a href="#contacto" class="btn">Solicita tu viaje</a>
        </div>
        <img src="imagen-hero.jpg" alt="Transporte puerta a puerta" class="hero-image">
    </header>

    <!-- Sección de Beneficios -->
    <section class="beneficios">
        <h2>¿Por qué elegir nuestro servicio?</h2>
        <div class="beneficio-items">
            <div class="item">
                <h3>Comodidad</h3>
                <p>Recogemos y dejamos en tu puerta.</p>
            </div>
            <div class="item">
                <h3>Puntualidad</h3>
                <p>Siempre a tiempo en cada viaje.</p>
            </div>
            <div class="item">
                <h3>Seguridad</h3>
                <p>Vehículos monitoreados y certificados.</p>
            </div>
            <div class="item">
                <h3>Flexibilidad</h3>
                <p>Viajes personales y empresariales.</p>
            </div>
        </div>
    </section>

    <!-- Servicios -->
    <section class="servicios">
        <h2>Nuestros Servicios</h2>
        <ul>
            <li>Transporte urbano e interurbano</li>
            <li>Traslados al aeropuerto</li>
            <li>Transporte para empresas</li>
            <li>Encomiendas puerta a puerta</li>
        </ul>
    </section>

    <!-- Testimonios -->
    <section class="testimonios">
        <h2>Lo que nuestros clientes dicen</h2>
        <blockquote>
            <p>"Un servicio excelente, llegaron puntuales y fueron muy amables."</p>
            <cite>- Juan Pérez</cite>
        </blockquote>
    </section>

    <!-- Formulario de Contacto -->
    <section id="contacto" class="contacto">
        <h2>Contáctanos para reservar tu viaje</h2>
        <form action="#">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>

            <label for="direccion">Dirección de Recogida:</label>
            <input type="text" id="direccion" name="direccion" required>

            <label for="mensaje">Comentarios:</label>
            <textarea id="mensaje" name="mensaje"></textarea>

            <button type="submit" class="btn">Solicitar Cotización</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Transporte Puerta a Puerta. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
