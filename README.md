<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mi Presentación</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:white;
}

header{
    text-align:center;
    padding:40px;
}

header img{
    width:180px;
    border-radius:50%;
    border:5px solid #00e5ff;
    box-shadow:0 0 20px cyan;
}

h1{
    margin-top:20px;
    font-size:40px;
}

p{
    font-size:18px;
    margin-top:10px;
}

.contenedor{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:30px;
    padding:40px;
}

.tarjeta{
    width:320px;
    background:rgba(255,255,255,.1);
    border-radius:15px;
    padding:20px;
    text-align:center;
    backdrop-filter:blur(10px);
    transition:.4s;
}

.tarjeta:hover{
    transform:translateY(-10px);
    box-shadow:0 0 20px cyan;
}

.tarjeta img{
    width:100%;
    border-radius:10px;
}

footer{
    text-align:center;
    padding:20px;
}
</style>

</head>

<body>

<header>

<!-- Cambia esta imagen por una foto tuya -->
<img src="https://i.imgur.com/YOURIMAGE.png" alt="Mi Foto">

<h1>¡Hola! Soy Luis 👋</h1>

<p>
Estudiante de programación apasionado por el desarrollo web,
la tecnología y el aprendizaje continuo.
</p>

</header>

<div class="contenedor">

<div class="tarjeta">
<h2>💻 Desarrollo Web</h2>

<img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif">
</div>
<div class="tarjeta">
<h2>🚀 Programación</h2>
<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif">
<p>
Actualmente se un poco de CSS, HTML, y ahora gifthub
</p>

</div>

<div class="tarjeta">
<h2>☕ Mi Objetivo</h2>

<img src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif">

<p>
Convertirme en desarrollador profesional y crear proyectos innovadores.
</p>

</div>

</div>

<footer>

<h3>Tecnologías que uso</h3>

<img src="https://skillicons.dev/icons?i=html,css,js,python,java,git,github,vscode">

</footer>

</body>
</html>
