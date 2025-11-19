<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UBICAMPUS – Universidad Politécnica del Estado de Nayarit</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #eef2f5;
}

/* ░░ HEADER ░░ */
header {
    background: #003c7e;
    color: white;
    text-align: center;
    padding: 40px 20px;
}
header img {
    width: 100%;
    max-width: 900px;
    border-radius: 15px;
    box-shadow: 0px 6px 20px rgba(0,0,0,0.2);
}

/* ░░ SECCIONES ░░ */
section {
    max-width: 1100px;
    margin: auto;
    padding: 30px 20px;
}
h2 {
    text-align: center;
    color: #003c7e;
    margin-bottom: 25px;
    font-size: 32px;
}

/* ░░ TARJETA MAPA ░░ */
.card {
    background: white;
    border-radius: 15px;
    padding: 20px;
    box-shadow: 0px 5px 15px rgba(0,0,0,0.1);
    text-align: center;
}
.card img {
    width: 100%;
    border-radius: 15px;
}

/* ░░ GALERÍA DE AULAS ░░ */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
}
.gallery-item {
    background: white;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
}
.gallery-item img {
    width: 100%;
    border-radius: 12px;
}

/* ░░ QR ░░ */
.qr {
    text-align: center;
}
.qr img {
    width: 260px;
    background: white;
    padding: 10px;
    border-radius: 15px;
    box-shadow: 0px 6px 20px rgba(0,0,0,0.15);
}
</style>

</head>
<body>

<!-- ░░ PORTADA ░░ -->
<header>
    <img src="img/portada.png" alt="Portada UBICAMPUS">
</header>


<!-- ░░ MAPA DE LA UNIVERSIDAD ░░ -->
<section>
    <h2>Mapa de la Universidad</h2>

    <div class="card">
        <img src="img/mapa.png" alt="Mapa Universidad Politécnica del Estado de Nayarit">
    </div>
</section>


<!-- ░░ AULAS Y UBICACIONES ░░ -->
<section>
    <h2>Aulas y Ubicaciones</h2>

    <div class="gallery">
        <div class="gallery-item">
            <img src="img/aula1.png" alt="Aula 101">
            <h3>Aula 101</h3>
            <p>Edificio A - Planta baja</p>
        </div>

        <div class="gallery-item">
            <img src="img/aula2.png" alt="Aula 203">
            <h3>Aula 203</h3>
            <p>Edificio B - Segundo piso</p>
        </div>

        <div class="gallery-item">
            <img src="img/aula3.png" alt="Laboratorio 3">
            <h3>Laboratorio 3</h3>
            <p>Edificio C - Planta alta</p>
        </div>
    </div>
</section>


<!-- ░░ QR ░░ -->
<section>
    <h2>Código QR de Acceso</h2>

    <div class="qr">
        <img src="img/qr.png" alt="Código QR UBICAMPUS">
    </div>
</section>

</body>
</html>

