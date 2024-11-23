<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Broma de Carlos</title>
</head>
<body onload="showAlert(); playSound();">
    <h1>¡Haz clic aquí para ver un mensaje importante!</h1>

    <a href="javascript:showAlert(); playSound();">Haz clic aquí para escuchar y ver el mensaje</a>

    <script>
        function showAlert() {
            alert("¡CARLOS!");
        }

        function playSound() {
            var audio = new Audio('https://www.soundjay.com/button/beep-07.wav');
            audio.play();
        }
    </script>
</body>
</html>
