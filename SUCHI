<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>SUCHICOOP</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">

<style>
body {
margin: 0;
font-family: 'Inter', sans-serif;
background: #0b0f14;
color: white;
}

/* HERO /
.hero {
height: 100vh;
display: flex;
align-items: center;
justify-content: center;
text-align: center;
background: linear-gradient(120deg, #0b0f14, #0f3d2e);
padding: 20px;
}

.hero h1 {
font-size: 45px;
}

.btn {
margin-top: 20px;
padding: 12px 30px;
background: #00ff88;
border: none;
border-radius: 25px;
cursor: pointer;
}

/ FORM /
.form {
background: #121821;
padding: 30px;
border-radius: 15px;
max-width: 400px;
margin: auto;
}

input, select {
width: 100%;
padding: 12px;
margin-top: 10px;
border-radius: 8px;
border: none;
}

/ SECCIONES /
.section {
padding: 60px 20px;
text-align: center;
}

/ FOOTER */
.footer {
text-align: center;
padding: 20px;
color: #777;
}
</style>

</head>

<body>

<!-- HERO -->
<div class="hero">
<div>
<h1>Solicitá tu crédito hoy</h1>
<p>Respuesta rápida • Proceso sencillo • Atención personalizada</p>

<button class="btn" onclick="document.getElementById('formulario').scrollIntoView()">
Solicitar ahora
</button>
</div>
</div>

<!-- FORMULARIO REAL -->
<div class="section" id="formulario">
<h2>Solicitud de Crédito</h2>

<div class="form">

<input type="text" id="nombre" placeholder="Nombre completo"> <input type="text" id="telefono" placeholder="Teléfono">

<select id="tipo">
<option>Tipo de crédito</option>
<option>Consumo</option>
<option>Vivienda</option>
<option>Comercio</option>
</select>

<input type="number" id="monto" placeholder="Monto solicitado">

<button class="btn" onclick="enviarWhatsApp()">Enviar solicitud</button>

</div>
</div>

<!-- SERVICIOS -->
<div class="section">
<h2>¿Por qué elegirnos?</h2>
<p>✔ Atención rápida</p>
<p>✔ Procesos simples</p>
<p>✔ Respaldo y confianza</p>
</div>

<div class="footer">
© 2026 SUCHICOOP
</div>

<script>
function enviarWhatsApp() {

let nombre = document.getElementById("nombre").value;
let telefono = document.getElementById("telefono").value;
let tipo = document.getElementById("tipo").value;
let monto = document.getElementById("monto").value;

let mensaje = "Hola, quiero solicitar crédito:%0A"
+ "Nombre: " + nombre + "%0A"
+ "Teléfono: " + telefono + "%0A"
+ "Tipo: " + tipo + "%0A"
+ "Monto: $" + monto;

let url = "https://wa.me/50375678767?text=" + mensaje;

window.open(url, '_blank');
}
</script>

</body>
</html>
