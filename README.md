<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Soluciones Integrales | Plomería y Electricidad</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">
  <!-- Encabezado -->
  <header class="bg-blue-700 text-white p-6 shadow-md">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Soluciones Integrales</h1>
      <nav class="space-x-4">
        <a href="#inicio" class="hover:underline">Inicio</a>
        <a href="#servicios" class="hover:underline">Servicios</a>
        <a href="#nosotros" class="hover:underline">Nosotros</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Inicio -->
  <section id="inicio" class="bg-white py-20 text-center">
    <h2 class="text-3xl font-bold mb-4">¡Tu solución rápida y segura!</h2>
    <p class="text-lg">Servicios profesionales de plomería y electricidad en un solo lugar.</p>
    <a href="#contacto" class="mt-6 inline-block bg-blue-600 text-white px-6 py-3 rounded-full shadow hover:bg-blue-800 transition">Solicita tu cotización</a>
  </section>

  <!-- Servicios -->
  <section id="servicios" class="py-16 bg-gray-200">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-2xl font-bold mb-10">Nuestros Servicios</h3>
      <div class="grid md:grid-cols-2 gap-8 text-left">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-bold text-lg mb-2">🔧 Plomería</h4>
          <ul class="list-disc list-inside">
            <li>Reparación de fugas</li>
            <li>Instalación de tuberías</li>
            <li>Calentadores de agua</li>
          </ul>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="font-bold text-lg mb-2">⚡ Electricidad</h4>
          <ul class="list-disc list-inside">
            <li>Instalaciones eléctricas</li>
            <li>Reparación de cortos</li>
            <li>Paneles solares</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Nosotros -->
  <section id="nosotros" class="bg-white py-16">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-2xl font-bold mb-6">¿Quiénes somos?</h3>
      <p class="text-lg">
        Somos una empresa con más de 10 años de experiencia brindando servicios de calidad en el área de mantenimiento, plomería y electricidad. Nos caracterizamos por la honestidad, eficiencia y rapidez.
      </p>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="bg-gray-100 py-16">
    <div class="max-w-3xl mx-auto">
      <h3 class="text-2xl font-bold text-center mb-6">Contáctanos</h3>
      <form class="bg-white shadow-md rounded p-6 space-y-4">
        <input type="text" placeholder="Tu nombre" class="w-full border p-2 rounded" required />
        <input type="email" placeholder="Tu correo" class="w-full border p-2 rounded" required />
        <textarea placeholder="Tu mensaje" class="w-full border p-2 rounded" rows="4" required></textarea>
        <button type="submit" class="w-full bg-blue-700 text-white py-2 rounded hover:bg-blue-900">Enviar mensaje</button>
      </form>
    </div>
  </section>

  <!-- Botón WhatsApp -->
  <a href="https://wa.me/524412036485" target="_blank"
     class="fixed bottom-6 right-6 bg-green-500 p-4 rounded-full shadow-lg hover:bg-green-600 transition">
    <img src="https://img.icons8.com/ios-filled/50/ffffff/whatsapp.png" alt="WhatsApp" class="w-6 h-6" />
  </a>

  <!-- Pie de página -->
  <footer class="bg-blue-700 text-white text-center py-4 mt-10">
    &copy; 2025 Soluciones Integrales. Todos los derechos reservados.
  </footer>
</body>
</html>
