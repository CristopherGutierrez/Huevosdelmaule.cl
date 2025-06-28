<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pitch de Inversión: Huevos del Maule</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
            color: #374151; /* Dark gray text */
        }
        .section-title {
            color: #10B981; /* Emerald green for titles */
            font-weight: 700;
        }
        .card {
            background-color: #ffffff;
            border-radius: 1.5rem; /* More rounded corners */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease-in-out;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .btn-primary {
            background-color: #10B981; /* Emerald green */
            color: #ffffff;
            padding: 0.75rem 1.5rem;
            border-radius: 0.75rem;
            font-weight: 600;
            transition: background-color 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #059669; /* Darker emerald */
        }
        .icon {
            font-size: 2.5rem; /* Larger icons */
            color: #10B981;
        }
        .footer-note {
            font-size: 0.875rem;
            color: #6B7280;
        }
    </style>
</head>
<body class="p-4 md:p-8">

    <div class="max-w-4xl mx-auto bg-white rounded-3xl p-6 md:p-10 shadow-xl">

        <!-- Header Section -->
        <header class="text-center mb-10">
            <h1 class="text-4xl md:text-5xl font-extrabold text-green-700 mb-4 animate-pulse">
                ¡Invierte en el Futuro de la Producción de Huevos!
            </h1>
            <p class="text-lg md:text-xl text-gray-600">
                Presentamos: <span class="font-semibold text-green-600">Huevos del Maule</span>
            </p>
            <div class="flex justify-center mt-6">
                <!-- Simple egg icon SVG -->
                <svg class="w-16 h-16 text-yellow-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm-1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l3 3a1 1 0 001.414-1.414L11.414 10H15a1 1 0 100-2h-4.586l-1.707-1.707z" clip-rule="evenodd"></path>
                </svg>
            </div>
        </header>

        <!-- Project Overview -->
        <section class="mb-10 text-center">
            <h2 class="section-title text-3xl mb-4">La Oportunidad</h2>
            <p class="text-gray-700 leading-relaxed text-lg">
                "Huevos del Maule" es una empresa avícola de gallinas ponedoras blancas, ubicada estratégicamente en la Región del Maule. Nuestro objetivo es ser el proveedor líder de huevos frescos de alta calidad, diferenciándonos por la frescura, la excelencia en su origen y un modelo de producción consciente con el medio ambiente y el bienestar animal.
            </p>
        </section>

        <!-- Key Differentiators -->
        <section class="mb-10">
            <h2 class="section-title text-3xl text-center mb-6">Nuestros Pilares Diferenciadores</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="card p-6 text-center">
                    <div class="icon mb-4">🥚</div>
                    <h3 class="font-bold text-xl text-gray-800 mb-2">Producción Eficiente</h3>
                    <p class="text-gray-600">Plantel inicial de <span class="font-semibold">5,000 gallinas</span>, proyectando hasta <span class="font-semibold">4,750 huevos diarios</span>. Suministro continuo y robusto.</p>
                </div>
                <div class="card p-6 text-center">
                    <div class="icon mb-4">✅</div>
                    <h3 class="font-bold text-xl text-gray-800 mb-2">Calidad & Trazabilidad</h3>
                    <p class="text-gray-600">Rigurosos protocolos sanitarios y de bioseguridad, garantizando la trazabilidad completa desde la granja al consumidor.</p>
                </div>
                <div class="card p-6 text-center">
                    <div class="icon mb-4">🌿</div>
                    <h3 class="font-bold text-xl text-gray-800 mb-2">Sostenibilidad & Bienestar Animal</h3>
                    <p class="text-gray-600">Sistema de compostaje de estiércol y galpones diseñados bajo estrictos principios de bienestar animal.</p>
                </div>
            </div>
        </section>

        <!-- Financial Highlights -->
        <section class="mb-10 text-center">
            <h2 class="section-title text-3xl mb-6">Un Negocio Financieramente Sólido</h2>
            <p class="text-gray-700 leading-relaxed text-lg mb-6">
                La inversión total inicial es de <span class="font-bold text-green-700">\$172,060,000 CLP</span>, financiada al 100% mediante un crédito bancario a 5 años con una tasa de interés del 10%. Los números hablan por sí solos:
            </p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="card p-6">
                    <h3 class="font-bold text-xl text-gray-800 mb-2">Valor Actual Neto (VAN)</h3>
                    <p class="text-4xl font-extrabold text-green-600 mb-2">\$32,645,402 CLP</p>
                    <p class="text-gray-600">Indica un valor superior a la inversión inicial.</p>
                </div>
                <div class="card p-6">
                    <h3 class="font-bold text-xl text-gray-800 mb-2">Tasa Interna de Retorno (TIR)</h3>
                    <p class="text-4xl font-extrabold text-green-600 mb-2">28%</p>
                    <p class="text-gray-600">Supera la tasa de descuento del 10%, demostrando atractividad.</p>
                </div>
                <div class="card p-6">
                    <h3 class="font-bold text-xl text-gray-800 mb-2">Payback (Retorno de Inversión)</h3>
                    <p class="text-4xl font-extrabold text-green-600 mb-2">2 años y 1 mes</p>
                    <p class="text-gray-600">Rápida recuperación de la inversión.</p>
                </div>
            </div>
        </section>

        <!-- Conclusion / Call to Action -->
        <section class="mb-10 text-center">
            <h2 class="section-title text-3xl mb-4">¡Es Tiempo de Incubar el Éxito!</h2>
            <p class="text-gray-700 leading-relaxed text-lg mb-6">
                "Huevos del Maule" presenta una sólida propuesta de valor, con proyecciones financieras atractivas y un rápido retorno de la inversión. La combinación de una producción eficiente, el compromiso con la calidad y el bienestar animal, y una estrategia de comercialización diversificada, posiciona a este negocio para un éxito sostenible y rentable.
            </p>
            <a href="#" class="btn-primary inline-block hover:scale-105 transform">Conoce Más</a>
        </section>

        <!-- Full Pitch Script (for reference) -->
        <section class="mt-12 p-6 bg-gray-50 rounded-2xl shadow-inner">
            <h2 class="section-title text-2xl mb-4 text-center">Script Completo del Pitch (Para tu referencia)</h2>
            <div class="text-gray-700 text-base leading-relaxed">
                <p class="mb-2"></p>
                <p class="mb-4">¡Hola a todos! Soy Cristophergutierrez/Representante del Proyecto huevos del maule y estoy aquí para presentarles una oportunidad de inversión excepcionalmente sólida en el sector agrícola chileno: "Huevos del Maule".</p>
                <p class="mb-4">Estamos hablando de una empresa avícola de gallinas ponedoras blancas, estratégicamente ubicada en la Región del Maule, en un terreno de 1 hectárea. Nuestro objetivo es claro: ser el proveedor de huevos frescos de alta calidad por excelencia en la región, diferenciándonos por la frescura del producto, la excelencia en su origen y, lo más importante, un modelo de producción consciente con el medio ambiente y el bienestar animal.</p>
                <p class="mb-4">¿Qué nos hace especiales? Contaremos con un plantel inicial de 5,000 gallinas, proyectando hasta 4,750 huevos diarios. Esto nos garantiza un suministro continuo y robusto para satisfacer la demanda. Implementaremos rigurosos protocolos sanitarios y de bioseguridad para asegurar la trazabilidad completa del huevo, desde la granja hasta el consumidor, lo que se traduce en confianza y valor añadido a nuestro producto. Además, nuestro compromiso con la sostenibilidad incluye un sistema de compostaje para el estiércol, transformándolo en abono orgánico, y galpones diseñados bajo estrictos principios de bienestar animal.</p>
                <p class="mb-4">Financieramente, "Huevos del Maule" es una propuesta inmejorable. La inversión total inicial es de \$172,060,000 CLP**, la cual se financiará al 100% a través de un crédito bancario a 5 años con una tasa de interés del 10%.</p>
                <p class="mb-4">Pero lo más impresionante son nuestros indicadores de rentabilidad:</p>
                <ul class="list-disc list-inside mb-4">
                    <li>El Valor Actual Neto (VAN) es de \$32,645,402 CLP, lo que demuestra que el proyecto generará un valor superior a la inversión inicial.</li>
                    <li>Nuestra Tasa Interna de Retorno (TIR) es de un impresionante 28%, superando con creces la tasa de descuento del 10%.</li>
                    <li>Y el Payback de la inversión se estima en tan solo 2 años y 1 mes, lo que significa una recuperación rápida de su capital.</li>
                </ul>
                <p class="mb-4">En resumen, "Huevos del Maule" presenta una sólida propuesta de valor, con proyecciones financieras atractivas y un rápido retorno de la inversión. La combinación de una producción eficiente, el compromiso con la calidad y el bienestar animal, y una estrategia de comercialización diversificada, posiciona a este negocio para un éxito sostenible y rentable.</p>
                <p class="font-semibold">Estamos listos para incubar este éxito. ¡Gracias!</p>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center mt-10 pt-6 border-t border-gray-200">
            <p class="footer-note">Diseñado para la Evaluación Sumativa N°3 de Negocios Agrícolas - AGC306</p>
            <p class="footer-note">Universidad Tecnológica de Chile - Inacap</p>
        </footer>

    </div>

</body>
</html>


