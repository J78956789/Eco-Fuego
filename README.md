# Eco-Fuego
Iniciador de fuego 100% natural 
   <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eco Fuego - Iniciador de fuego orgánico</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f3f3f3;
      color: #333;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      background-color: #1b5e20;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1597262975002-c5c3b14bbd62') center/cover no-repeat;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
    }
    .hero h1 {
      font-size: 3rem;
    }
    .content {
      padding: 2rem;
      background-color: white;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .feature {
      background: #e8f5e9;
      border-radius: 10px;
      padding: 1.5rem;
      text-align: center;
    }
    .store, .testimonials {
      margin-top: 3rem;
    }
    .product {
      background: #fff;
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
    }
    .product button {
      background-color: #2e7d32;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    .testimonial {
      background: #f1f8e9;
      padding: 1rem;
      border-left: 5px solid #81c784;
      margin-bottom: 1rem;
    }
    form {
      background: #e8f5e9;
      padding: 2rem;
      border-radius: 10px;
      max-width: 600px;
      margin: 2rem auto;
    }
    form input, form textarea, form button {
      width: 100%;
      margin-bottom: 1rem;
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background-color: #2e7d32;
      color: white;
      border: none;
    }
    footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Eco Fuego</h1>
    <p>Iniciador de fuego 100% orgánico, con beneficios únicos para tu bienestar y el medio ambiente</p>
  </header>
  <nav>
    <a href="#beneficios">Beneficios</a>
    <a href="#sostenibilidad">Sostenibilidad</a>
    <a href="#tienda">Tienda</a>
    <a href="#testimonios">Testimonios</a>
    <a href="#contacto">Contacto</a>
  </nav>
  <div class="hero">
    <h1>Prende tu fuego, cuida tu entorno</h1>
  </div>
  <section class="content">
    <h2 id="beneficios">¿Por qué elegir Eco Fuego?</h2>
    <div class="features">
      <div class="feature">
        <h3>Encendido Inmediato</h3>
        <p>Fácil de usar, se enciende al instante sin necesidad de productos químicos agresivos.</p>
      </div>
      <div class="feature">
        <h3>Aromaterapia Natural</h3>
        <p>Disfruta de aromas relajantes mientras enciendes tu fogata, chimenea o parrilla.</p>
      </div>
      <div class="feature">
        <h3>Repelente de Mosquitos</h3>
        <p>Contiene ingredientes naturales que alejan a los mosquitos de forma segura.</p>
      </div>
      <div class="feature">
        <h3>100% Orgánico</h3>
        <p>Hecho con materiales completamente naturales, libre de tóxicos y seguro para el medio ambiente.</p>
      </div>
    </div>

    <h2 id="sostenibilidad" class="store">Compromiso con la Sostenibilidad</h2>
    <p>Eco Fuego no solo es eficaz, también es respetuoso con la naturaleza. Su proceso de fabricación minimiza el impacto ambiental, promueve el uso de residuos orgánicos y fomenta prácticas responsables con el planeta.</p>

    <h2 id="tienda" class="store">Tienda en Línea</h2>
    <div class="features">
      <div class="product">
        <h3>Eco Fuego Pack Clásico</h3>
        <p>Contiene 10 unidades</p>
        <p><strong>$120 MXN</strong></p>
        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
          <input type="hidden" name="cmd" value="_s-xclick">
          <input type="hidden" name="hosted_button_id" value="ID_EJEMPLO_CLASICO">
          <button type="submit">Comprar con PayPal</button>
        </form>
      </div>
      <div class="product">
        <h3>Eco Fuego Familiar</h3>
        <p>Contiene 30 unidades + envío gratis</p>
        <p><strong>$300 MXN</strong></p>
        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
          <input type="hidden" name="cmd" value="_s-xclick">
          <input type="hidden" name="hosted_button_id" value="ID_EJEMPLO_FAMILIAR">
          <button type="submit">Comprar con PayPal</button>
        </form>
      </div>
    </div>

    <h2 id="testimonios" class="testimonials">Lo que opinan nuestros clientes</h2>
    <div class="testimonial">
      <p><em>"¡Excelente producto! Lo usamos en nuestras acampadas y realmente mantiene alejados a los mosquitos."</em> - Laura G.</p>
    </div>
    <div class="testimonial">
      <p><em>"Me encantó el aroma y lo rápido que prende. Además me hace sentir bien saber que es ecológico."</em> - Mario R.</p>
    </div>
    <div class="testimonial">
      <p><em>"Muy práctico, natural y eficaz. Recomendado al 100%."</em> - Andrea V.</p>
    </div>

    <h2 id="contacto">Contáctanos</h2>
    <form action="mailto:ecofuego@ejemplo.com" method="post" enctype="text/plain">
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu correo electrónico" required>
      <textarea name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar mensaje</button>
    </form>
  </section>

  <footer>
    <p>Contacto: ecofuego@ejemplo.com | Síguenos en redes sociales @EcoFuego</p>
    <p>&copy; 2025 Eco Fuego. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
