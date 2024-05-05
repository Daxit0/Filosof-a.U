<!DOCTYPE html><!-- Este comentario oculta la declaración DOCTYPE -->
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EL PERÍODO DE LAS GRANDES SÍNTESIS DE PLATÓN Y SU DISCÍPULO ARISTÓTELES</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f2f2f2;
            color: #333;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .game {
            border: 1px solid #ccc;
            padding: 20px;
            margin-bottom: 20px;
        }
        .words {
            margin-top: 20px;
        }
        input[type="text"] {
            width: 150px; /* Aumenta el tamaño del campo de texto */
            padding: 5px;
            margin: 0 5px;
            text-align: center;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="text"][placeholder="___"] {
            background-color: #ffe6e6;
        }
        .title {
            text-align: center;
            font-size: 24px;
            margin-bottom: 10px;
        }
        .creators {
            text-align: center;
            font-size: 14px;
            color: #666;
            margin-bottom: 20px;
        }
        #username-form {
            text-align: center;
            margin-bottom: 20px;
        }
        #username {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="title">
            EL PERÍODO DE LAS GRANDES SÍNTESIS DE PLATÓN Y SU DISCÍPULO ARISTÓTELES
        </div>
        <div class="creators">
            Creado por Escobar Uriel, Brovia Dante, Meza Bruno y Lagos Gonzalo
        </div>
        <form id="username-form">
            <label for="username">Nombre de Usuario:</label>
            <input type="text" id="username" name="username" required>
            <button type="submit">Comenzar Juego</button>
        </form>
        <div class="game" style="display: none;">
            <p><strong>Completa las siguientes frases:</strong></p>
            <ol>
                <li>Platón nació en <input type="text" id="word1" placeholder="___"> en el 427 ac y murió en el <input type="text" id="word2" placeholder="___">.</li>
                <li>Todos los escritos de Platón son <input type="text" id="word3" placeholder="___">.</li>
                <li>Platón acepta el incesante <input type="text" id="word4" placeholder="___"> que perciben los sentidos como lo afirmaba Heráclito.</li>
                <li>Las ideas y conceptos no provienen de la experiencia sensorial, sino del <input type="text" id="word5" placeholder="___">, en el mundo de las ideas, universales, inmateriales, eternas y perfectas.</li>
                <li>Platón propuso la existencia de dos reales: el mundo <input type="text" id="word6" placeholder="___"> y el mundo <input type="text" id="word7" placeholder="___">.</li>
                <li>Platón entendía al Estado ideal como una extensión de la división del <input type="text" id="word8" placeholder="___">. Cada clase social tendrá diferentes virtudes según su ubicación: <input type="text" id="word9" placeholder="___">, <input type="text" id="word10" placeholder="___"> y <input type="text" id="word11" placeholder="___">.</li>
            </ol>
        </div>
        <div class="words" style="display: none;">
            <p><strong>Palabras:</strong></p>
            <ul>
                <li><strong>Palabra 1:</strong> Atenas</li>
                <li><strong>Palabra 2:</strong> 347 ac</li>
                <li><strong>Palabra 3:</strong> diálogos</li>
                <li><strong>Palabra 4:</strong> cambio</li>
                <li><strong>Palabra 5:</strong> alma</li>
                <li><strong>Palabra 6:</strong> sensible</li>
                <li><strong>Palabra 7:</strong> inteligible</li>
                <li><strong>Palabra 8:</strong> alma</li>
                <li><strong>Palabra 9:</strong> templanza</li>
                <li><strong>Palabra 10:</strong> fortaleza</li>
                <li><strong>Palabra 11:</strong> sabiduría</li>
            </ul>
        </div>
    </div>

    <script>
        document.getElementById("username-form").addEventListener("submit", function(event) {
            event.preventDefault();
            var username = document.getElementById("username").value;
            document.getElementById("username-form").style.display = "none";
            document.querySelector(".game").style.display = "block";
            document.querySelector(".words").style.display = "block";
            // Puedes hacer algo con el nombre de usuario si lo necesitas
            console.log("Nombre de Usuario:", username);
        });
    </script>
</body>
</html>
