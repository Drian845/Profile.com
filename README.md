<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0 user-scalable=no">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="estilo.css">
    <title>Seavar</title>
</head>

<body>
    <!-- SECCION I N I C I O -->
    <section id="inicio">
        <div class="contenido">
            <header>
                <div class="contenido-header">
                    <h1>SEAVAR</h1>
                    <nav id="nav" class="">
                        <ul id="links">
                            <li><a href="#inicio" class="seleccionado" onclick="seleccionar(this)">INICIO</a></li>
                            <li><a href="#aboutus" onclick="seleccionar(this)">ABOUT US</a></li>
                            <li><a href="#productos" onclick="seleccionar(this)">PRODUCTOS</a></li>
                            <li><a href="#servicios" onclick="seleccionar(this)">SERVICIOS</a></li>
                            <li><a href="#contactanos" onclick="seleccionar(this)">CONTACTANOS</a></li>
                        </ul>
                    </nav>

                    <!-- Icono del menu responsive -->
                    <div id="icono-nav" onclick="responsiveMenu()">
                        <i class="fa-solid fa-bars"></i>
                    </div>


                    <div class="redes">
                        <a href="#"><i class="fa-brands fa-youtube"></i></a>
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                        <a href="#"><i class="fa-brands fa-instagram-square"></i></a>
                    </div>
                </div>
            </header>
            <div class="presentacion">
                <p class="bienvenida">Bienvenidos</p>
                <h2>Seavar Eco Store | Tienda Eco Friendly<span>Adrián Granillo , Desarrollado por BAM</span></h2>
                <p class="descripcion">Tienda eco-fiendly con servicio a domicilio de lunes a domingo </p>
                <a href="#blogs">Ir a Blogs</a>
            </div>
        </div>
    </section>

    <!-- SECCION A B O U T U S -->
    <section id="aboutus">
        <div class="contenedor-foto">
            <img src="img/Tupper1.jpg" alt="">
        </div>
        <div class="sobremi">
            <p class="titulo-seccion">About us</p>
            <h2>Hola, Soy <span>Seavar</span> </h2>
            <h3>Tu mejor opción ante productos de uso diario sin el plástico</h3>
            <p>Contamos con diferentes productos de uso diario para que termines con el plástico y empieces una nueva relación con tu nueva vidda eco-friendly.</p>
            <p>Una vez inicies no sentiras la diferencia y amaras ser parte de esta reconstrucción del planeta.</p>
            <div class="contenedor-foto">
                <img src="img/Seavar.jpeg" alt="">
            </div>
        </div>
    </section>

    <!-- SECCION S E R V I C I O S -->
    <section id="servicios">
        <h3 class="titulo-seccion">SERVICIOS DE ENVIO</h3>
        <div class="fila">
            <div class="servicio">
                <span class="icono"> <i class="fa-solid fa-code"></i></span>
                <h4>Envíos por medio de Seavar</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Adicional</li>
                    <li>$3</li>
                    <li>Por su compra</li>
                </ul>
                <p>Por cualquier compra realizada se le asignara un extra de 3$ por el envío en el mismo día de sus productos a todo San Salvador</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-file-code"></i></span>
                <h4>Envíos por medio de Seavar</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Adicional</li>
                    <li>$5</li>
                    <li>Por su compra</li>
                </ul>
                <p>Por cualquier compra realizada se le asignara un extra de $5 por el envío entre 1 a 3 días de sus productos a Santa Ana, Ahuchapan y Sonsonate</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-arrow-trend-up"></i></span>
                <h4>Envios por medio de Seavar</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Adicional</li>
                    <li>$10</li>
                    <li>Por su compra</li>
                </ul>
                <p>Por cualquier compra realizada se le asignara un extra de $10 por el envío entre 1 a 3 días de sus productos al Oriente de El Salvador</p>
            </div>
        </div>
        <div class="fila">
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-database"></i></span>
                <h4>Cupones y promociones</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Adicional</li>
                    <li>$0</li>
                    <li>Por su compra</li>
                </ul>
                <p>Si usted cuenta con algún cupón o código promocional de Seavar, seleccione aquí para tener un cobro de 0$ por su envío.</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-palette"></i></span>
                <h4>Recoger al punto de venta</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Adicional</li>
                    <li>$0</li>
                    <li>Por su compra</li>
                </ul>
                <p>Si usted decide ir a recoger su compra al punto de venta, obtendra un costo de $0.</p>
            </div>
            <div class="servicio">
                <span class="icono"><i class="fa-solid fa-person-circle-question"></i></span>
                <h4>Aplicaciones de delivered</h4>
                <hr>
                <ul class="servicios-tag">
                    <li>Adicional</li>
                    <li>$</li>
                    <li>-</li>
                </ul>
                <p>Si usted realiza su compra por aplicaciones externas, Seavar no realizará un cobro extra pero los costos de envios variarán dependiendo de la empresa tercera.</p>
            </div>
        </div>
    </section>

    <!-- SECCION H A B I L I D A D E S -->
    <div class="contenedor-skills" id="skills">
        <h3>¿En qué somos buenos?</h3>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Servicio brindado por diversos medios virtuales</p>
                <span class="porcentaje">100%</span>
            </div>

            <div class="barra">
                <div class="" id="html"></div>
            </div>
        </div>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Envíos eficientes</p>
                <span class="porcentaje">90%</span>
            </div>

            <div class="barra">
                <div class="" id="js"></div>
            </div>
        </div>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Calidad</p>
                <span class="porcentaje">100%</span>
            </div>

            <div class="barra">
                <div class="" id="bd"></div>
            </div>
        </div>
        <div class="skill">
            <div class="info">
                <p> <span class="lista"> </span>Comprometidos con el medio ambiente</p>
                <span class="porcentaje">100%</span>
            </div>

            <div class="barra">
                <div class="" id="ps"></div>
            </div>
        </div>
    </div>

    <!-- SECCION PORTAFOLIO -->
    <section id="portfolio">
        <h3 class="titulo-seccion">Nuestros productos</h3>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Bolsas.jpg" alt="">
                <div class="info">
                    <h4>Bolsas Artesanales</h4>
                    <p>$10.00 La unidad</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Botellas.jpg" alt="">
                <div class="info">
                    <h4>Botellas de agua y cafeteras</h4>
                    <p>Se venden por separado a un precio de $10.00</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Cepillos.jpg" alt="">
                <div class="info">
                    <h4>Cepillos de madera</h4>
                    <p>$2.50 La unidad con 5 colores diferentes a elegir</p>
                </div>
            </div>
        </div>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Cubiertos de madera.jpg" alt="">
                <div class="info">
                    <h4>Cubiertos de madera</h4>
                    <p>Set de 3 cubiertos de maderas a $5.00 cada set</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/dog2.jpg" alt="">
                <div class="info">
                    <h4>Platos para perros</h4>
                    <p>Platos de 5 colores diferentes, faciles de transportar a $8.00</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Pajilla metalica.jpg" alt="">
                <div class="info">
                    <h4>Pajilla metalica con protector</h4>
                    <p>5 colores de pajillas metalicas + su protector y limpiador a $5.50 La unidad</p>
                </div>
            </div>
        </div>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/set pajillas metalicas.jpg" alt="">
                <div class="info">
                    <h4>Set de pajillas</h4>
                    <p>5 pajillas de 3 colores diferentes en un mismo set a $6.50 el set</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Tapas.jpg" alt="">
                <div class="info">
                    <h4>Tapas de frutas y vasos</h4>
                    <p>Set de 10 tapaderas para frutas y vasos de diferentes tamaños a $8.00 y si lleva 2 sets a un $15.00</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="img/Tuppers conjunto.jpg" alt="">
                <div class="info">
                    <h4>Conjunto de Tuppers</h4>
                    <p>Set de 12 tuppers de 3 tamaños y colores diferentes a $20.00 el set</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCTION C O N T A C T O -->
    <section id="contacto">
        <h3 class="titulo-seccion">Contactanos ahora</h3>
        <div class="contenedor-form">
            <form action="">
                <div class="fila mitad">
                    <input type="text" placeholder="Nombre Completo *" class="input-mitad">
                    <input type="email" placeholder="Dirección de Email" class="input-mitad">
                </div>
                <div class="fila">
                    <input type="text" placeholder="Tema..." class="input-full">
                </div>
                <div class="fila">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Tu Mensaje..." class="input-full"></textarea>
                </div>

                <input type="submit" value="Enviar Mensaje" class="btn-enviar">
            </form>
        </div>
    </section>

    <!-- SECCION FOOTER -->
    <footer>
        <h5>Todos los derechos reservados por BAM- 2022</h5>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-youtube"></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-instagram-square"></i></a>
        </div>

    </footer>

    <script src="script.js"></script>
</body>

</html>
