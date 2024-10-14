<!DOCTYPE html> 
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Casamiento de Elias</title>
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@300;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #F9F5F0;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background: #F9F5F0;
            text-align: center;
            padding: 50px 0;
            position: relative;
        }

        header::after {
            content: '';
            background-image: url('https://example.com/floral-background.png'); /* Cambia esto por una URL válida */
            background-size: cover;
            background-position: center;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0.1;
            z-index: -1;
        }

        header h1 {
            font-size: 4rem;
            color: #A67C52;
            font-family: 'Great Vibes', cursive;
        }

        header p {
            font-size: 2rem;
            margin: 0;
            font-family: 'Montserrat', sans-serif;
            color: #A67C52;
            letter-spacing: 2px;
        }

        section {
            margin: 60px auto;
            max-width: 800px;
            text-align: center;
        }

        .event-details {
            background-color: #FFF;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            margin: 30px auto;
            max-width: 600px;
            border: 1px solid #e0e0e0;
        }

        .event-details h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #A67C52;
            text-transform: uppercase;
        }

        .event-details p {
            font-size: 1.4rem;
            line-height: 1.7;
            color: #555;
        }

        .event-details strong {
            color: #A67C52;
            font-weight: 600;
        }

        .confirmacion {
            background-color: #FFF;
            border-radius: 15px;
            padding: 30px;
            margin: 40px auto;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            border: 1px solid #e0e0e0;
            max-width: 600px;
        }

        .confirmacion h2 {
            font-size: 2rem;
            color: #A67C52;
            margin-bottom: 20px;
        }

        .confirmacion form input, 
        .confirmacion form button {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            font-size: 1rem;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .confirmacion form button {
            background-color: #A67C52;
            color: white;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .confirmacion form button:hover {
            background-color: #8A6340;
        }

        .vestimenta {
            background-color: #FFF;
            border-radius: 15px;
            padding: 30px;
            margin: 40px auto;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            border: 1px solid #e0e0e0;
            max-width: 600px;
        }

        .vestimenta h2 {
            font-size: 2rem;
            color: #A67C52;
            margin-bottom: 20px;
        }

        .vestimenta p {
            font-size: 1.4rem;
            color: #555;
        }

        footer {
            background-color: #A67C52;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 1.2rem;
            letter-spacing: 1px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>¡Nos Casamos!</h1>
        <p>Elias & [Nombre de tu pareja]</p>
    </header>

    <section>
        <!-- Detalles del evento -->
        <div class="event-details">
            <h2>Detalles del Evento</h2>
            <p><img src="https://img.icons8.com/color/48/000000/calendar--v1.png" class="icon"><strong>Fecha:</strong> 15 de diciembre de 2024</p>
            <p><img src="https://img.icons8.com/color/48/000000/marker--v1.png" class="icon"><strong>Lugar:</strong> Salón de Fiestas XYZ, Ciudad de Córdoba</p>
            <p><img src="https://img.icons8.com/color/48/000000/clock--v1.png" class="icon"><strong>Hora:</strong> 17:00</p>
        </div>

        <!-- Confirmación de asistencia -->
        <div class="confirmacion">
            <h2>Confirmación de Asistencia</h2>
            <form action="#">
                <input type="text" name="nombre" placeholder="Ingresa tu nombre completo" required>
                <input type="email" name="email" placeholder="Ingresa tu correo electrónico" required>
                <button type="submit">Confirmar Asistencia</button>
            </form>
        </div>

        <!-- Código de vestimenta -->
        <div class="vestimenta">
            <h2>Código de Vestimenta</h2>
            <p>Para nuestro evento, recomendamos un código de vestimenta **elegante-casual**. Nos encantaría ver a todos disfrutando y luciendo elegantes en nuestro día especial.</p>
        </div>
    </section>

    <footer>
        <p>Hecho con amor por Elias y [Nombre de tu pareja]</p>
    </footer>

</body>
</html>
