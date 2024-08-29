<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitación de Cumpleaños</title>
    <style>
        body {
            background-image: url('https://fotografias-neox.atresmedia.com/clipping/cmsimages01/2020/09/17/46E76535-71FD-4BD4-9F4E-D369CA8F97FD/97.jpg?crop=1271,715,x0,y0&width=1600&height=900&optimize=high&format=webply');
            background-size: cover;
            background-position: center;
            color: #f0e68c;
            font-family: 'Garamond', serif;
            text-align: center;
            padding: 20px;
            margin: 0;
            box-sizing: border-box;
        }
        .invitation {
            background-color: rgba(244, 208, 63, 0.9);
            color: #990000;
            max-width: 90%;
            margin: 20px auto;
            border: 5px solid #990000;
            padding: 15px;
            border-radius: 20px;
            position: relative;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
        }

        .invitation h1 {
            font-size: 1.8em;
            margin-bottom: 10px;
        }

        .invitation p {
            font-size: 1em;
            margin: 10px 0;
        }

        .invitation .name {
            font-size: 2em;
            font-weight: bold;
            color: #990000;
        }

        .invitation .details {
            margin-top: 15px;
        }

        .glasses {
            position: absolute;
            top: 5%;
            right: -12%;
            width: 150px;
        }

        .castle {
            position: absolute;
            bottom: 5%;
            left: -8%;
            width: 125px;
        }

        .snitch {
            position: absolute;
            top: 8%;
            left: -10%;
            width: 150px;
        }

        @media screen and (max-width: 480px) {
            .invitation {
                padding: 10px;
            }

            .invitation h1 {
                font-size: 1.5em;
            }

            .invitation .name {
                font-size: 1.8em;
            }

            .glasses,
            .castle,
            .snitch {
                width: 100px;
            }
        }
    </style>
</head>
<body>
    <div class="invitation">
        <img src="https://i.pinimg.com/originals/b3/b4/8c/b3b48cdea0d5f4c07f8154680b225651.png" alt="Golden Snitch" class="snitch">
        <h1>Atención a todas las Brujas y Magos</h1>
        <p>Que la magia de Hogwarts ilumine tu día especial.</p>
        <p class="name">[Nombre del Cumpleañero/a]</p>
        <p>¡Que el Sombrero Seleccionador te coloque en la casa de la felicidad!</p>
        <p class="details">
            <strong>Que la magia siempre te acompañe</strong><br>
            <strong>Recuerda que las palabras son nuestra fuente inagotable de magia.</strong><br>
        </p>
        <p>Que la magia de Hogwarts brille intensamente en tu día especial...</p>
        <p>¡Feliz cumpleaños! ✨</p>
        <img src="https://i.pinimg.com/originals/d5/32/d6/d532d62c7029926a373ba346cfec739c.png" alt="Hogwarts Castle" class="castle">
        <img src="https://i.pinimg.com/originals/9d/59/af/9d59afaaea96bfa643576ee9fdb7cf86.png" alt="Harry Potter Glasses" class="glasses">
    </div>
</body>
</html>
