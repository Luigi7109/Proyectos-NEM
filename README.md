<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultora Educativa Macías Hernández: Proyectos Educativos con la Nueva Escuela Mexicana</title>
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography,aspect-ratio,line-clamp,container-queries"></script>
    <style>
      @font-face {
        font-family: 'LucideIcons';
        /* Using CDN for Lucide font */
        src: url(https://cdn.jsdelivr.net/npm/lucide-static@latest/font/Lucide.ttf) format('truetype');
      }
      .lucide {
        font-family: 'LucideIcons';
        font-size: 1.25rem; /* Adjust size as needed */
        line-height: 1;
      }
      /* Basic styles for message box */
      .message-box {
        position: fixed;
        top: 20px;
        right: 20px;
        background-color: #4CAF50; /* Green */
        color: white;
        padding: 15px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        z-index: 1000;
        opacity: 0;
        transition: opacity 0.5s ease-in-out;
      }
      .message-box.show {
        opacity: 1;
      }
    </style>
    <script>
      // Tailwind CSS Configuration
      tailwind.config = {
        theme: {
          extend: {
            fontFamily: {
              sans: ['Inter', 'sans-serif'], // Use Inter font
            },
            colors: {
              // Primary and secondary colors set to sky blue tones
              primary: '#0284c7', // Tailwind sky-600
              secondary: '#0ea5e9', // Tailwind sky-500
              accent: '#FFC107', // Amber/Yellow (Kept for contrast)
            }
          }
        }
      }
    </script>
</head>
<body class="bg-gray-50 font-sans antialiased">

    <header class="bg-white shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <span class="lucide text-primary" aria-hidden="true">&#xe46f;</span> <span class="text-xl font-bold text-primary">Consultora Educativa Macías Hernández</span>
            </div>
            <div>
                <a href="#contacto" class="bg-primary hover:bg-secondary text-white font-semibold py-2 px-4 rounded-lg transition duration-300 ease-in-out">
                    Contáctanos
                </a>
            </div>
        </nav>
    </header>

    <section class="bg-gradient-to-r from-primary to-secondary text-white py-20 md:py-32">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-4 leading-tight">
                Transforma la Educación con IA y la Nueva Escuela Mexicana
            </h1>
            <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto">
                Diseñamos proyectos educativos innovadores alineados al nuevo plan de estudios, integrando inteligencia artificial para potenciar el aprendizaje.
            </p>
            <a href="#elementos-clave" class="bg-accent hover:bg-yellow-500 text-primary font-bold py-3 px-8 rounded-lg text-lg transition duration-300 ease-in-out">
                Descubre Cómo
            </a>
        </div>
    </section>

    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">El Desafío: Integrar la Nueva Escuela Mexicana</h2>
                    <p class="text-gray-600 mb-4">
                        Alinear los proyectos educativos con los múltiples componentes de la Nueva Escuela Mexicana (NEM) —contenidos, PDA, campos formativos, ejes articuladores, contexto, perfil de egreso y ajustes razonables— puede ser complejo y consumir mucho tiempo.
                    </p>
                    <p class="text-gray-600">
                        ¿Cómo asegurar una integración coherente y efectiva que realmente responda a las necesidades del alumnado y al contexto local?
                    </p>
                </div>
                <div class="bg-gray-100 p-8 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold text-primary mb-3 flex items-center">
                        <span class="lucide mr-2">&#xe46f;</span> Nuestra Solución con IA
                    </h3>
                    <p class="text-gray-700">
                        Utilizamos inteligencia artificial para analizar los requerimientos de la NEM y tu contexto específico, generando propuestas de proyectos estructuradas, relevantes y personalizadas. Simplificamos el proceso, asegurando la coherencia pedagógica y la inclusión.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="elementos-clave" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Integración Completa de la Nueva Escuela Mexicana</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="flex items-center text-secondary mb-3">
                        <span class="lucide mr-2">&#xe115;</span> <h3 class="text-xl font-semibold">Contenidos y PDA</h3>
                    </div>
                    <p class="text-gray-600">La IA identifica y sugiere contenidos relevantes y Procesos de Desarrollo de Aprendizaje (PDA) alineados a los objetivos del proyecto y al grado escolar.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="flex items-center text-secondary mb-3">
                        <span class="lucide mr-2">&#xe40d;</span> <h3 class="text-xl font-semibold">Campos Formativos</h3>
                    </div>
                    <p class="text-gray-600">Aseguramos la articulación del proyecto a través de los diferentes Campos Formativos, fomentando una visión integral del conocimiento.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="flex items-center text-secondary mb-3">
                        <span class="lucide mr-2">&#xe4b7;</span> <h3 class="text-xl font-semibold">Ejes Articuladores</h3>
                    </div>
                    <p class="text-gray-600">La IA ayuda a integrar transversalmente los Ejes Articuladores (Inclusión, Pensamiento Crítico, etc.) en las actividades del proyecto.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="flex items-center text-secondary mb-3">
                        <span class="lucide mr-2">&#xe287;</span> <h3 class="text-xl font-semibold">Contexto y Problemática</h3>
                    </div>
                    <p class="text-gray-600">Analizamos el contexto escolar y comunitario para proponer proyectos que aborden problemáticas locales significativas.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="flex items-center text-secondary mb-3">
                        <span class="lucide mr-2">&#xe45b;</span> <h3 class="text-xl font-semibold">Perfil de Egreso</h3>
                    </div>
                    <p class="text-gray-600">Diseñamos actividades que contribuyen directamente al desarrollo de las competencias y rasgos del Perfil de Egreso de la Educación Básica.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="flex items-center text-secondary mb-3">
                        <span class="lucide mr-2">&#xe520;</span> <h3 class="text-xl font-semibold">Ajustes Razonables (Inclusión)</h3>
                    </div>
                    <p class="text-gray-600">La IA sugiere estrategias y adaptaciones (ajustes razonables) para garantizar la participación y aprendizaje de todo el alumnado, incluyendo aquellos con NEE.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="py-16 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold text-gray-800 mb-12">Beneficios de Nuestra Metodología</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="bg-secondary text-white rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4">
                        <span class="lucide text-3xl">&#xe0e1;</span> </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Eficiencia y Rapidez</h3>
                    <p class="text-gray-600">Acelera el proceso de diseño curricular y planificación de proyectos.</p>
                </div>
                <div class="text-center">
                    <div class="bg-secondary text-white rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4">
                        <span class="lucide text-3xl">&#xe4b6;</span> </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Coherencia Pedagógica</h3>
                    <p class="text-gray-600">Asegura la alineación y articulación de todos los elementos de la NEM.</p>
                </div>
                <div class="text-center">
                    <div class="bg-secondary text-white rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4">
                        <span class="lucide text-3xl">&#xe51f;</span> </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Inclusión y Personalización</h3>
                    <p class="text-gray-600">Facilita la creación de ajustes razonables y la adaptación al contexto.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="codiseno" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="text-center">
                   <span class="lucide text-primary text-8xl md:text-9xl mx-auto">&#xe521;</span> </div>
                <div>
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">Espacio de Codiseño para Docentes</h2>
                    <p class="text-gray-600 mb-4">
                        Facilitamos un entorno colaborativo donde <span class="font-semibold">las y los docentes</span> pueden participar activamente en el <span class="font-semibold">codiseño de contenidos y procesos de desarrollo de aprendizaje (PDA)</span>.
                    </p>
                    <p class="text-gray-600 mb-4">
                        Nuestra plataforma asistida por IA permite adaptar y construir conjuntamente los elementos curriculares necesarios para la elaboración de <span class="font-semibold">proyectos de aula, escolares o comunitarios</span>, asegurando que respondan auténticamente a las <span class="font-semibold">necesidades y problemáticas de su contexto</span>.
                    </p>
                    <p class="text-gray-600 mb-6">
                        ¡Fomentamos la autonomía profesional y la creación colectiva para un aprendizaje significativo!
                    </p>
                    <a href="#contacto" class="bg-primary hover:bg-secondary text-white font-semibold py-2 px-5 rounded-lg transition duration-300 ease-in-out inline-flex items-center">
                        Participa en el Codiseño
                        <span class="lucide ml-2 text-base">&#xe0c8;</span> </a>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="py-20 bg-gradient-to-r from-primary to-secondary text-white">
        <div class="container mx-auto px-6">
            <div class="max-w-2xl mx-auto text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">¿Listo para Innovar tus Proyectos Educativos?</h2>
                <p class="text-lg mb-8">Completa el formulario y uno de nuestros consultores expertos en IA y educación se pondrá en contacto contigo.</p>
            </div>
            <div class="max-w-xl mx-auto bg-white p-8 rounded-lg shadow-xl">
                <form id="contact-form">
                    <div class="mb-4">
                        <label for="name" class="block text-gray-700 font-semibold mb-2">Nombre Completo</label>
                        <input type="text" id="name" name="name" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-secondary text-gray-900">
                    </div>
                    <div class="mb-4">
                        <label for="email" class="block text-gray-700 font-semibold mb-2">Correo Electrónico</label>
                        <input type="email" id="email" name="email" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-secondary text-gray-900">
                    </div>
                    <div class="mb-4">
                        <label for="institution" class="block text-gray-700 font-semibold mb-2">Institución Educativa (Opcional)</label>
                        <input type="text" id="institution" name="institution" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-secondary text-gray-900">
                    </div>
                    <div class="mb-6">
                        <label for="message" class="block text-gray-700 font-semibold mb-2">Mensaje</label>
                        <textarea id="message" name="message" rows="4" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-secondary text-gray-900"></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-accent hover:bg-yellow-500 text-primary font-bold py-3 px-8 rounded-lg text-lg transition duration-300 ease-in-out w-full">
                            Solicitar Información
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-gray-400 py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025 Consultora Educativa Macías Hernández. Todos los derechos reservados.</p>
            <div class="mt-2">
                <a href="#" class="hover:text-white mx-2">Política de Privacidad</a> |
                <a href="#" class="hover:text-white mx-2">Términos de Servicio</a>
            </div>
        </div>
    </footer>

    <div id="message-box" class="message-box"></div>

    <script>
        const form = document.getElementById('contact-form');
        const messageBox = document.getElementById('message-box');

        // Add event listener for form submission
        form.addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent actual form submission for this demo

            // Simulate sending data (replace with actual API call if needed)
            console.log('Form submitted');

            // Get form data to personalize message (optional)
            const formData = new FormData(form);
            const name = formData.get('name');

            // Show success message using the helper function
            showMessage(`Gracias ${name || ''}, hemos recibido tu mensaje. Nos pondremos en contacto pronto.`);

            // Clear the form after submission
            form.reset();
        });

        // Helper function to display the message box
        function showMessage(message) {
            messageBox.textContent = message;
            messageBox.classList.add('show'); // Make the box visible

            // Hide the message box after 5 seconds
            setTimeout(() => {
                messageBox.classList.remove('show'); // Hide the box
            }, 5000); // 5000 milliseconds = 5 seconds
        }
    </script>

</body>
</html>
