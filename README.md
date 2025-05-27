<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Menú Bonito</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8; /* Fondo azul claro suave */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            box-sizing: border-box;
        }
        .menu-card {
            background-color: #ffffff; /* Fondo blanco para la tarjeta del menú */
            border-radius: 1.5rem; /* Bordes más redondeados */
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04); /* Sombra más pronunciada */
            max-width: 600px; /* Ancho máximo para el menú */
            width: 100%;
            overflow: hidden;
            border: 1px solid #e2e8f0; /* Borde sutil */
        }
        .header-image {
            /* Tu foto de Imgur está aquí */
            background-image: url('https://i.imgur.com/mJbUvBL.png');
            background-size: cover;
            background-position: center;
            height: 200px; /* Altura de la imagen */
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }
        .header-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(to bottom, rgba(0,0,0,0.4) 0%, rgba(0,0,0,0.7) 100%); /* Degradado oscuro */
            border-radius: 1.5rem 1.5rem 0 0; /* Bordes redondeados solo arriba */
        }
    </style>
</head>
<body class="antialiased">
    <div class="menu-card">
        <div class="header-image">
            <div class="header-overlay"></div>
            <h1 class="relative text-white text-4xl sm:text-5xl font-extrabold tracking-tight text-center p-4 z-10">
                Menú Especial
            </h1>
        </div>

        <div class="p-6 sm:p-8">
            <p class="text-gray-600 text-center mb-6 text-lg">
                ¡Disfruta de nuestros deliciosos platos y bebidas!
            </p>

            <div class="mb-8">
                <h2 class="text-2xl font-bold text-gray-800 mb-4 border-b-2 border-yellow-500 pb-2">
                    Platos Fuertes
                </h2>
                <ul class="space-y-4">
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Parrilladita</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Burritos de Carne</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Hamburguesa de Carne</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Crep de Pollo en Salsa de Champiñón</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Lasaña</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Choriperro</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-yellow-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Waps de Carne o Pollo</span>
                        <span class="text-xl text-yellow-700 font-bold">$18.000</span>
                    </li>
                </ul>
            </div>

            <div>
                <h2 class="text-2xl font-bold text-gray-800 mb-4 border-b-2 border-blue-500 pb-2">
                    Bebidas Refrescantes
                </h2>
                <ul class="space-y-4">
                    <li class="flex justify-between items-center bg-blue-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Sangría</span>
                        <span class="text-xl text-blue-700 font-bold">$5.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-blue-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Jugos Naturales</span>
                        <span class="text-xl text-blue-700 font-bold">$5.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-blue-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Soda Italiana (Frutos Rojos)</span>
                        <span class="text-xl text-blue-700 font-bold">$5.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-blue-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Té Helado</span>
                        <span class="text-xl text-blue-700 font-bold">$5.000</span>
                    </li>
                    <li class="flex justify-between items-center bg-blue-50 p-4 rounded-lg shadow-sm">
                        <span class="text-lg text-gray-900 font-medium">Refajo</span>
                        <span class="text-xl text-blue-700 font-bold">$5.000</span>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
