<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apastepeque: Historia, Cultura y Tradiciones</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header .highlight, header .current a {
            color: #e8491d;
            font-weight: bold;
        }
        header a:hover {
            color: #ffffff;
            font-weight: bold;
        }
        #showcase {
            min-height: 400px;
            background: url('/api/placeholder/1200/400') no-repeat 0 -400px;
            text-align: center;
            color: #ffffff;
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        section {
            padding: 20px 0;
            border-bottom: 1px solid #ccc;
        }
        .content-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: flex-start;
        }
        .text-content {
            flex: 1;
            min-width: 50%;
        }
        .image-content {
            flex: 1;
            min-width: 40%;
            text-align: center;
        }
        .image-content img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #ffffff;
            background-color: #35424a;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Apastepeque</span> Web</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="#inicio">Inicio</a></li>
                    <li><a href="#historia">Historia</a></li>
                    <li><a href="#gastronomia">Gastronomía</a></li>
                    <li><a href="#artesanias">Artesanías</a></li>
                    <li><a href="#festividades">Festividades</a></li>
                    <li><a href="#lugares">Lugares</a></li>
                </ul>
            </nav>
        </div>
    </header>

  <section id="showcase">
        <div class="container">
            <h1>Bienvenidos a Apastepeque</h1>
            <p>Descubre la riqueza cultural de nuestro municipio</p>
        </div>
    </section>

   <div class="container">
        <section id="inicio">
            <h2>Sobre Apastepeque</h2>
            <div class="content-section">
                <div class="text-content">
                    <p>Apastepeque, joya cultural de El Salvador, te invita a explorar su rica historia, deliciosa gastronomía y vibrantes tradiciones.</p>
                </div>
                <div class="image-content">
                    <img src="/api/placeholder/400/300" alt="Vista panorámica de Apastepeque">
                </div>
            </div>
        </section>

  <section id="historia">
            <h2>Historia</h2>
            <div class="content-section">
                <div class="text-content">
                    <h3>Orígenes Precolombinos</h3>
                    <p>Los orígenes de Apastepeque se remontan a la época precolombina, con asentamientos indígenas que datan de siglos atrás.</p>
                    <h3>Época Colonial</h3>
                    <p>Durante la colonia, Apastepeque se convirtió en un importante centro de comercio y cultura.</p>
                </div>
                <div class="image-content">
                    <img src="/api/placeholder/400/300" alt="Sitio arqueológico de Apastepeque">
                </div>
            </div>
        </section>

   <section id="gastronomia">
            <h2>Gastronomía</h2>
            <div class="content-section">
                <div class="text-content">
                    <h3>Platos Típicos</h3>
                    <ul>
                        <li>Pupusas de Apastepeque</li>
                        <li>Yuca frita con chicharrón</li>
                        <li>Tamales de elote</li>
                    </ul>
                </div>
                <div class="image-content">
                    <img src="/api/placeholder/400/300" alt="Pupusas de Apastepeque">
                </div>
            </div>
        </section>

   <section id="artesanias">
            <h2>Artesanías</h2>
            <div class="content-section">
                <div class="text-content">
                    <h3>Tejidos Tradicionales</h3>
                    <p>Los coloridos tejidos de Apastepeque son famosos por su calidad y diseños únicos.</p>
                    <h3>Alfarería</h3>
                    <p>La cerámica local refleja técnicas ancestrales transmitidas por generaciones.</p>
                </div>
                <div class="image-content">
                    <img src="/api/placeholder/400/300" alt="Artesanías de Apastepeque">
                </div>
            </div>
        </section>

   <section id="festividades">
            <h2>Festividades</h2>
            <div class="content-section">
                <div class="text-content">
                    <h3>Fiestas Patronales</h3>
                    <p>Las fiestas en honor a San Pedro Apóstol, del 24 al 29 de junio, son el evento más importante del año.</p>
                </div>
                <div class="image-content">
                    <img src="/api/placeholder/400/300" alt="Celebración de las fiestas patronales">
                </div>
            </div>
        </section>

   <section id="lugares">
            <h2>Lugares Emblemáticos</h2>
            <div class="content-section">
                <div class="text-content">
                    <h3>Iglesia San Pedro Apóstol</h3>
                    <p>Joya arquitectónica colonial y centro espiritual de la comunidad.</p>
                    <h3>Laguna de Apastepeque</h3>
                    <p>Belleza natural que ofrece actividades recreativas y hermosos paisajes.</p>
                </div>
                <div class="image-content">
                    <img src="/api/placeholder/400/300" alt="Iglesia San Pedro Apóstol">
                </div>
            </div>
        </section>
    </div>

   <footer>
        <p>Contacto: turismo@apastepeque.gob.sv | Tel: (503) 2362-5000</p>
        <p>Síguenos en redes sociales: [Iconos de redes sociales]</p>
        <p>&copy; 2024 Municipio de Apastepeque - Todos los derechos reservados</p>
    </footer>
</body>
</html>