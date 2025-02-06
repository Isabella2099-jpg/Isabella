<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitación San Valentín</title>
    <style>
        body {
            font-family: "Times New Roman", serif;
            background-color: #f0e5d8;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        .section {
            margin: 20px;
        }
        .button {
            background-color: #ff69b4;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #ff3385;
        }
    </style>
</head>
<body>
    <div class="section">
        <h2>Primera Parte</h2>
        <p>Mi rey, cualquier fecha es especial para demostrarte lo importante que eres en mi vida y el amor que siento por ti. Eres tú. Has sido tú desde que llegaste los últimos meses, eres tú cuando despierto y duermo. Te amo.</p>
    </div>
    
    <div class="section">
        <h2>Segunda Parte</h2>
        <p>¿Quieres ser mi San Valentín?</p>
        <button class="button" onclick="showCelebration()">¡Síiiii!</button>
    </div>

    <div class="section" id="celebration" style="display: none;">
        <h2>¡Celebración!</h2>
        <p>Ponte una pinta bonita y prepárate para una noche disfrutando de las dos cosas que más te gustan. Te sorprenderás.</p>
        <p><strong>Fecha:</strong> Finde semana del 14 de febrero</p>
        <p><strong>Pista:</strong> Hay que llegar al lugar rodando <span style="font-size: 24px;">🏍️</span></p>
    </div>

    <script>
        function showCelebration() {
            document.getElementById('celebration').style.display = 'block';
        }
    </script>
</body>
</html>
