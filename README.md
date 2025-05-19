<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gestoy Agency</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>Gestoy Agency</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#nosotros">Sobre Nosotros</a></li>
                <li><a href="#contacto"

/* RESET y estilo base */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Open Sans', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

/* Header */
header {
    background-color: #1a1a1a;
    color: #fff;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header .logo h1 {
    font-size: 2.5em;
    font-weight: 600;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}

header nav ul li a:hover {
    color: #ff6f61;
}

/* Secciones */
.section {
    padding: 60px 20px;
    text-align: center;
}

/* Hero Section */
.hero {
    background: url('https://via.placeholder.com/1500x800') center/cover no-repeat;
    color: #fff;
    padding: 100px 0;
}

.hero h2 {
    font-size: 3em;
    font-weight: 600;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 30px;
}

.cta-button {
    background-color: #ff6f61;
    color: white;
    padding: 15px 30px;
    font-size: 1.1em;
    text-decoration: none;
    border-radius: 5px;
}

.cta-button:hover {
    background-color: #e65d53;
}

/* Servicios */
.services-container {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.service {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    flex: 1;
    text-align: left;
}

.service h3 {
    color: #333;
    margin-bottom: 15px;
}

.service p {
    font-size: 1.1em;
    color: #777;
}

/* Formulario de contacto */
form input, form textarea {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    border: 1px solid #ddd;
