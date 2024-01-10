# TrainToday
git clone https://github.com/tu-usuario/TrainToday.git
cd TrainToday
touch index.html style.css script.js
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>TrainToday - Tu Entrenamiento Diario</title>
</head>
<body>
    <h1>Bienvenido a TrainToday</h1>
    <p>¡Entrenamiento diario para una vida más saludable!</p>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 20px;
}

h1 {
    color: #333;
}

p {
    color: #666;
}
// Puedes agregar código JavaScript aquí
console.log("Entrenamiento diario para una vida más saludable!");
git add .
git commit -m "Añadir archivos iniciales"
git push origin master
