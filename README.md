<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Derivador Paso a Paso</title>
  <link rel="stylesheet" href="style.css"/>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjs/12.4.1/math.min.js"></script>
</head>
<body>
  <div class="container">
    <h1>🧮 Derivador Paso a Paso</h1>
    <p>Ingresa una función para derivar:</p>
    <input type="text" id="funcion" placeholder="Ejemplo: x^3 + 2x^2 - x" />
    <button onclick="resolverDerivada()">Resolver</button>
    <div id="resultado"></div>
  </div>
  <script src="script.js"></script>
</body>
</html>
