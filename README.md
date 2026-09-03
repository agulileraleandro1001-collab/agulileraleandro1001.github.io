# UBICONTROL.SAS
<!doctype html>
<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7" lang=""> <![endif]-->
<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8" lang=""> <![endif]-->
<!--[if IE 8]>         <html class="no-js lt-ie9" lang=""> <![endif]-->
<!--[if gt IE 8]><!--> <html class="no-js" lang="es"> <!--<![endif]-->
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <title>UBICONTROL SAS | Marketing para empresas de insecticidas</title>
        <meta name="description" content="UBICONTROL SAS: agencia de marketing especializada en empresas de productos insecticidas. Publicidad, gestión de redes sociales y estrategias para fortalecer tu marca y aumentar tus ventas.">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="apple-touch-icon" href="assets/images/logo_1.png">
        <link rel="icon" type="image/png" href="assets/images/logo_1.png">

        <link rel="stylesheet" href="assets/css/bootstrap.min.css">
        <!--        <link rel="stylesheet" href="assets/css/bootstrap-theme.min.css">-->


        <!--For Plugins external css-->
        <link rel="stylesheet" href="assets/css/plugins.css" />
        <link rel="stylesheet" href="assets/css/roboto-webfont.css" />

        <!--Theme custom css -->
        <link rel="stylesheet" href="assets/css/style.css">

        <!--Theme Responsive css-->
        <link rel="stylesheet" href="assets/css/responsive.css" />

        <script src="assets/js/vendor/modernizr-2.8.3-respond-1.4.2.min.js"></script>

        <!-- ===== Mejoras visuales UBICONTROL (agregado) =====
             Estilos adicionales para dar más vida al diseño existente:
             sombras suaves, transiciones al pasar el mouse y una
             pequeña animación de entrada. No modifica clases ni
             estructura original, solo añade comportamiento encima. -->
        <style>
            /* Suavizado general de transiciones */
            .navbar-brand img,
            .btn,
            .cd-select,
            .single_service2,
            .single_features_left img,
            .social-icon a,
            .contact_socail_bookmark a,
            .scrollup a,
            .cd-pricing-list > li,
            input[type="submit"] {
                transition: all 0.3s ease-in-out;
            }

            /* Logos: leve zoom al pasar el mouse */
            .navbar-brand img:hover {
                transform: scale(1.06);
            }

            /* Botones: efecto de elevación */
            .btn:hover,
            .cd-select:hover,
            input[type="submit"]:hover {
                transform: translateY(-3px);
                box-shadow: 0 8px 18px rgba(0, 0, 0, 0.15);
            }

            /* Tarjetas de servicios */
            .single_service2:hover {
                transform: translateY(-6px);
                box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
                border-radius: 6px;
            }

            /* Bloques "Nuestros Servicios de Marketing" */
            /* Nota: .community-edition ya tiene su propio hover (fondo verde)
               definido en style.css; aquí solo se añade profundidad extra
               sin tocar padding, color ni fondo para no chocar con tu diseño. */
            .community-edition:hover {
                transform: translateY(-6px);
                box-shadow: 0 10px 22px rgba(0, 0, 0, 0.12);
            }
            .community-edition i {
                transition: transform 0.3s ease-in-out, color 0.3s ease-in-out;
            }
            .community-edition:hover i {
                transform: scale(1.15);
            }

            /* Imágenes de features */
            .single_features_left img {
                border-radius: 6px;
            }
            .single_features_left img:hover {
                transform: scale(1.02);
                box-shadow: 0 12px 28px rgba(0, 0, 0, 0.12);
            }

            /* Iconos sociales */
            .social-icon a:hover,
            .contact_socail_bookmark a:hover {
                transform: translateY(-3px);
                opacity: 0.85;
            }

            /* Botón "subir" */
            .scrollup a:hover {
                transform: translateY(-4px);
            }

            /* Tarjetas de precios: el volteo entre "Empresas" y "Emprendedores"
               ya usa transform (rotateY) por JS/CSS propio del tema, así que el
               hover de elevación se aplica a la columna exterior, no a la
               tarjeta que rota, para no interferir con esa animación. */
            .cd-pricing-list > li:hover {
                transform: translateY(-5px);
            }

            /* Animación de entrada suave para el encabezado */
            @keyframes ubiFadeInUp {
                from {
                    opacity: 0;
                    transform: translateY(18px);
                }
                to {
                    opacity: 1;
                    transform: translateY(0);
                }
            }
            .home-content h1,
            .home-content p,
            .home-content .home-contact {
                animation: ubiFadeInUp 0.8s ease-out both;
            }
            .home-content p { animation-delay: 0.15s; }
            .home-content .home-contact { animation-delay: 0.3s; }

            /* Separación extra en móvil solo donde tu CSS no la traía ya */
            @media (max-width: 767px) {
                .single_service2 {
                    margin-bottom: 25px;
                }
            }

            /* Logo del pie de página */
            .footer-brand img {
                display: block;
            }
        </style>
        <!-- ===== Fin mejoras visuales UBICONTROL ===== -->
    </head>
    <body>
        <!--[if lt IE 8]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
        <![endif]-->
		<div class='preloader'><div class='loaded'>&nbsp;</div></div>
        <!-- Sections -->
        <section id="social" class="social">
            <div class="container">
                <!-- Example row of columns -->
                <div class="row">
                    <div class="social-wrapper">
                        <div class="col-md-6">
                            <div class="social-icon">
                                <a href="#"><i class="fa fa-facebook"></i></a>
                                <a href="#"><i class="fa fa-twitter"></i></a>
                                <a href="#"><i class="fa fa-google-plus"></i></a>
                                <a href="#"><i class="fa fa-linkedin"></i></a>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="social-contact">
                                <a href="#"><i class="fa fa-phone"></i>+57 3228302152</a>
                                <a href="#"><i class="fa fa-envelope"></i>ubicontrol.sas12@gmail.com</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div> <!-- /container -->       
        </section>

        <nav class="navbar navbar-default">
            <div class="container">
                <!-- Brand and toggle get grouped for better mobile display -->
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="#home">
    <img src="assets/images/logo_1.png" alt="UBICONTROL" style="max-height: 55px; width: auto;" />
</a>
                    <a class="navbar-brand" href="#home">
    <img src="assets/images/logo_2_en_forma_de_escrito.png" alt="UBICONTROL" style="max-height: 40px; width: auto;" />
</a>
                </div>

                <!-- Collect the nav links, forms, and other content for toggling -->
                <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">

                    <ul class="nav navbar-nav navbar-right">
                        <li class="active"><a href="#home">Inicio</a></li>
                        <li><a href="#service">SERVICIOS</a></li>
                        <li><a href="#price">PRECIOS</a></li>
                        <li><a href="#business">PORTAFOLIO</a></li>
                        <li><a href="#contact">CONTACTO</a></li>
                        <li class="login"><a href="#contact">Cotizar</a></li>
                    </ul>

                </div><!-- /.navbar-collapse -->
            </div><!-- /.container-fluid -->
        </nav>

        <!--Home page style-->
        <header id="home" class="home">
            <div class="overlay-fluid-block">
                <div class="container text-center">
                    <div class="row">
                        <div class="home-wrapper">
                            <div class="col-md-10 col-md-offset-1">
                                <div class="home-content">

                                    <h1>Hacemos visible tu marca, impulsamos tus ventas</h1>
                                    <p> UBICONTROL lleva tu marca de insecticidas al siguiente nivel con estrategias de marketing creativas y efectivas. Conectamos tus productos con más clientes, fortalecemos tu presencia en el mercado e impulsamos el crecimiento de tu negocio</p>

                                    <div class="row">
                                        <div class="col-md-6 col-md-offset-3 col-sm-12 col-xs-12">
                                            <div class="home-contact">
                                                <form action="#contact" class="input-group">
                                                    <input type="email" class="form-control" placeholder="Ingresa tu correo electrónico" required>
                                                    <input type="submit" class="form-control" value="Asesoría Gratis">

                                                </form><!-- /input-group -->


                                            </div>
                                        </div>
                                    </div>


                                </div>
                            </div>
                        </div>
                    </div>
                </div>			
            </div>
        </header>

        <!-- Sections -->
        <section id="features" class="features sections">
            <div class="container">
                <div class="row">
                    <div class="main_features_content2">

                        <div class="col-sm-6">
                            <div class="single_features_left text-center">
                                <img src="assets/images/feature-2.jpg" alt="" />
                            </div>
                        </div>

                        <div class="col-sm-6 margin-top-60">
                            <div class="single_features_right ">
                                <h2>Nuestro Servicio</h2>
                                <p>En UBICONTROL ofrecemos un servicio de marketing especializado para empresas de insecticidas. Diseñamos estrategias de publicidad, promoción y posicionamiento para ayudar a que sus productos lleguen a más clientes, fortaleciendo su marca e impulsando sus ventas.</p>
                                <ul>
                                    <li>Publicidad y promoción de productos insecticidas.</li>
                                    <li>Diseño de estrategias de marketing para aumentar el alcance de la marca.</li>
                                    <li>Posicionamiento de marca y apoyo en ventas para llegar a más clientes.</li>
                                </ul>
                             <div class="features_buttom">
                                    <a href="#texto-extra" class="btn btn-default" data-toggle="collapse">Leer Más</a>
                                 </div>
                            <div class="collapse" id="texto-extra" style="margin-top: 15px;">
                            <p>
                                En UBICONTROL somos un equipo que busca ayudar a las empresas de insecticidas a dar a conocer sus productos por medio del marketing. Nuestro propósito es crear estrategias y publicidad que permitan llegar a más clientes y hacer crecer cada marca.

                                 Como equipo, trabajamos con responsabilidad, creatividad y compromiso para ofrecer un servicio de calidad. Queremos que nuestros clientes confíen en nosotros y vean en UBICONTROL un aliado para promocionar sus productos y aumentar sus ventas.
                            </p>
                            </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section><!--End of Features 2 Section -->
        <section id="features" class="features sections">
            <div class="container">
                <div class="row">
                    <div class="main_features_content2">

                       

                        <div class="col-sm-6 margin-top-60">
                            <div class="single_features_right ">
                                <h2>DESCRIPCIÓN DE NUESTROS SERVICIOS</h2>
                                <p>En UBICONTROL queremos que las marcas de insecticidas lleguen a más personas y se destaquen en el mercado. Por eso creamos campañas publicitarias, contenido para redes sociales y estrategias de marketing que ayudan a atraer clientes y aumentar las ventas. Nos esforzamos por ofrecer un servicio creativo, confiable y de calidad, porque creemos que una buena idea puede hacer crecer cualquier marca.
</p>
                                <ul>
                                    <li>📢 Publicidad creativa: Diseñamos campañas que hacen destacar tu marca.</li>
                                    <li>📱 Marketing digital: Creamos contenido para redes sociales que atrae más clientes.</li>
                                    <li>📈 Crecimiento de tu negocio: Desarrollamos estrategias para aumentar la visibilidad y las ventas de tus productos.</li>
                                </ul>

                            </div>
                        </div>
                         <div class="col-sm-6">
                            <div class="single_features_left text-center">
                                <img src="assets/images/feature-1.jpg" alt="" />
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section><!--End of Features 2 Section -->


        <section id="service" class="service2 sections lightbg">
            <div class="container">
                <div class="row">
                    <div class="main_service2">
                        <div class="head_title text-center">
                            <h2>SERVICES WE PROVIDE</h2>
                            <p>Conoce los servicios que hemos creado para ayudar a las empresas a dar a conocer sus productos, fortalecer su marca y llegar a más clientes mediante estrategias de marketing.</p>
                        </div>

                        <div class="service_content">
                            <div class="col-md-6 col-sm-6">
                                <div class="single_service2">
                                    <div class="single_service_left">
                                        <img src="assets/images/Megafono..png" alt="" />
                                    </div>
                                    <div class="single_service_right">
                                        <h2>Publicidad Digital</h2>
                                        <p>Creamos campañas publicitarias que ayudan a promocionar productos insecticidas y atraer nuevos clientes.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 col-sm-6">
                                <div class="single_service2">
                                    <div class="single_service_left">
                                       <img src="assets/images/Grafica.png" alt="" />
                                    </div>
                                    <div class="single_service_right">
                                        <h2>Crecimiento de Marca</h2>
                                        <p>Ayudamos a que tu marca llegue a más personas y aumente su reconocimiento en el mercado.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 col-sm-6">
                                <div class="single_service2">
                                    <div class="single_service_left">
                                      <img src="assets/images/CELULAR.png" alt="" />
                                    </div>
                                    <div class="single_service_right">
                                        <h2>Gestión de Redes Sociales</h2>
                                        <p>Diseñamos y administramos contenido para redes sociales, fortaleciendo la presencia de tu marca.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 col-sm-6">
                                <div class="single_service2">
                                    <div class="single_service_left">
                                        <img src="assets/images/OBJETIVO.png" alt="" />
                                    </div>
                                    <div class="single_service_right">
                                        <h2>Estrategias de Marketing</h2>
                                        <p>Creamos estrategias personalizadas para que cada marca llegue a más clientes y logre mejores resultados.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section><!-- End of Service2 Section -->		



        <!-- Sections -->
        <section id="price" class="price sections">


            <div class="head_title text-center">
                <h1>Nuestros Planes</h1>
				<p>En UBICONTROL ofrecemos diferentes opciones para ayudar a las empresas a promocionar sus productos. Cada plan está pensado para adaptarse a las necesidades de nuestros clientes.</p>
            </div>
            <!-- Example row of columns -->
            <div class="cd-pricing-container cd-has-margins">
                <div class="cd-pricing-switcher">
                    <p class="fieldset">
                        <input type="radio" name="duration-2" value="monthly" id="monthly-2" checked>
                        <label for="monthly-2">Empresas</label>
                        <input type="radio" name="duration-2" value="yearly" id="yearly-2">
                        <label for="yearly-2">Emprendedores</label>
                        <span class="cd-switch"></span>
                    </p>
                </div> <!-- .cd-pricing-switcher -->

                <ul class="cd-pricing-list cd-bounce-invert">
                    <li>
                        <ul class="cd-pricing-wrapper">
                            <li data-type="monthly" class="is-visible">
                                <header class="cd-pricing-header">
                                    <h2>🟢 Plan Básico</h2>

                                    <div class="cd-price">
                                        <span class="cd-currency">$</span>
                                        <span class="cd-value">150.000</span>
                                        <span class="cd-duration">COP/mes</span>
                                    </div>
                                </header> <!-- .cd-pricing-header -->

                                <div class="cd-pricing-body">
                                    <ul class="cd-pricing-features">
                                        <li><em><i class="fa fa-check-circle"></i></em>Diseño de publicaciones.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Publicidad para redes sociales.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Asesoría en marketing.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>News Letter Available</li>

                                    </ul>
                                </div> <!-- .cd-pricing-body -->

                                <footer class="cd-pricing-footer">
                                    <a class="cd-select" href="#">Elegir plan</a>
                                </footer>  <!-- .cd-pricing-footer -->
                            </li>

                            <li data-type="yearly" class="is-hidden">
                                <header class="cd-pricing-header">
                                    <h2>🟢 Plan Emprende</h2>

                                    <div class="cd-price">
                                        <span class="cd-currency">$</span>
                                        <span class="cd-value">50.000</span>
                                        <span class="cd-duration">COP/mes</span>
                                    </div>
                                </header> <!-- .cd-pricing-header -->

                                <div class="cd-pricing-body">
                                    <ul class="cd-pricing-features">
                                        <li><em><i class="fa fa-check-circle"></i></em>Diseño de publicaciones.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Publicidad básica.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Asesoría inicial.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>News Letter Available</li>

                                    </ul>
                                </div> <!-- .cd-pricing-body -->

                                <footer class="cd-pricing-footer">
                                    <a class="cd-select" href="#">Elegir plan</a>
                                </footer>  <!-- .cd-pricing-footer -->
                            </li>
                        </ul> <!-- .cd-pricing-wrapper -->
                    </li>

                    <li class="cd-popular">
                        <ul class="cd-pricing-wrapper">
                            <li data-type="monthly" class="is-visible">
                                <header class="cd-pricing-header">
                                    <h2>⭐ Plan Intermedio</h2>
                                    <div class="cd-price">
                                        <span class="cd-currency">$</span>
                                        <span class="cd-value">300.000</span>
                                        <span class="cd-duration">COP/mes</span>
                                    </div>
                                </header> <!-- .cd-pricing-header -->

                                <div class="cd-pricing-body">
                                    <ul class="cd-pricing-features">
                                        <li><em><i class="fa fa-check-circle"></i></em>Todo lo del Plan Básico.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Campañas publicitarias.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Gestión de redes sociales.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Diseño de contenido.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>News Letter Available</li>

                                    </ul>
                                </div> <!-- .cd-pricing-body -->

                                <footer class="cd-pricing-footer">
                                    <a class="cd-select" href="#">Elegir plan</a>
                                </footer>  <!-- .cd-pricing-footer -->
                            </li>

                            <li data-type="yearly" class="is-hidden">
                                <header class="cd-pricing-header">
                                    <h2>⭐ Plan Crece</h2>

                                    <div class="cd-price">
                                        <span class="cd-currency">$</span>
                                        <span class="cd-value">100.000</span>
                                        <span class="cd-duration">COP/mes</span>
                                    </div>
                                </header> <!-- .cd-pricing-header -->

                                <div class="cd-pricing-body">
                                    <ul class="cd-pricing-features">
                                        <li><em><i class="fa fa-check-circle"></i></em>Todo lo del Plan Emprende.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Más publicaciones para redes sociales.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Diseño de promociones.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>News Letter Available</li>

                                    </ul>
                                </div> <!-- .cd-pricing-body -->

                                <footer class="cd-pricing-footer">
                                    <a class="cd-select" href="#">Elegir plan </a>
                                </footer>  <!-- .cd-pricing-footer -->
                            </li>
                        </ul> <!-- .cd-pricing-wrapper -->
                    </li>

                    <li>
                        <ul class="cd-pricing-wrapper">
                            <li data-type="monthly" class="is-visible">
                                <header class="cd-pricing-header">
                                    <h2>👑 Plan Premium</h2>

                                    <div class="cd-price">
                                        <span class="cd-currency">$</span>
                                        <span class="cd-value">500.000</span>
                                        <span class="cd-duration">COP/mes</span>
                                    </div>
                                </header> <!-- .cd-pricing-header -->

                                <div class="cd-pricing-body">
                                    <ul class="cd-pricing-features">
                                        <li><em><i class="fa fa-check-circle"></i></em>Todo lo del Plan Intermedio.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Estrategia de marketing personalizada.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Seguimiento de campañas.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Atención prioritaria.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>News Letter Available</li>

                                    </ul>
                                </div> <!-- .cd-pricing-body -->

                                <footer class="cd-pricing-footer">
                                    <a class="cd-select" href="#">Elegir plan</a>
                                </footer>  <!-- .cd-pricing-footer -->
                            </li>

                            <li data-type="yearly" class="is-hidden">
                                <header class="cd-pricing-header">
                                    <h2>👑 Plan Impulsa</h2>

                                    <div class="cd-price">
                                        <span class="cd-currency">$</span>
                                        <span class="cd-value">180.000</span>
                                        <span class="cd-duration">COP/mes</span>
                                    </div>
                                </header> <!-- .cd-pricing-header -->

                                <div class="cd-pricing-body">
                                    <ul class="cd-pricing-features">
                                        <li><em><i class="fa fa-check-circle"></i></em>Todo lo del Plan Crece.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Estrategias para hacer crecer la marca.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>Seguimiento y recomendaciones.</li>
                                        <li><em><i class="fa fa-check-circle"></i></em>News Letter Available</li>

                                    </ul>
                                </div> <!-- .cd-pricing-body -->

                                <footer class="cd-pricing-footer">
                                    <a class="cd-select" href="#">Elegir plan</a>
                                </footer>  <!-- .cd-pricing-footer -->
                            </li>
                        </ul> <!-- .cd-pricing-wrapper -->
                    </li>
                </ul> <!-- .cd-pricing-list -->
            </div> <!-- .cd-pricing-container -->	

        </section>

        <!-- Sections -->
        <section id="business" class="portfolio sections">
            <div class="container">
                <div class="head_title text-center">
                    <h1>Nuestros Servicios de Marketing</h1>
					<p>En UBICONTROL ofrecemos diferentes servicios para ayudar a las empresas de insecticidas a promocionar sus productos, fortalecer su marca y llegar a más clientes.</p>
                </div>

                <div class="row">
                    <div class="portfolio-wrapper text-center">
                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-book"></i>
                                <div class="separator"></div>
                                <h4>Diseño de Contenido</h4>
                                <p>Creamos publicaciones e imágenes llamativas para redes sociales y campañas publicitarias.</p>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-bug"></i>
                                <div class="separator"></div>
                                <h4>Investigación de Mercado</h4>
                                <p>Analizamos el mercado y la competencia para identificar oportunidades que ayuden a que tu producto insecticida se posicione mejor frente a tus clientes potenciales.</p>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-gears"></i>
                                <div class="separator"></div>
                                <h4>Optimización de Campañas</h4>
                                <p>Ajustamos y mejoramos continuamente cada campaña publicitaria para obtener el mayor alcance y retorno posible para tu marca.</p>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-external-link"></i>
                                <div class="separator"></div>
                                <h4>Alcance en Nuevos Mercados</h4>
                                <p>Diseñamos estrategias para llevar tus productos insecticidas a nuevas zonas y canales de venta, ampliando tu base de clientes.</p>
                            </div>
                        </div>

                    </div>
                </div>

                <!-- Example row of columns -->
                <div class="row">
                    <div class="portfolio-wrapper2 text-center">
                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-coffee"></i>
                                <div class="separator"></div>
                                <h4>Atención Personalizada</h4>
                                <p>Acompañamos a cada cliente de cerca, entendiendo sus necesidades para ofrecer soluciones de marketing hechas a la medida de su marca.</p>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-tree"></i>
                                <div class="separator"></div>
                                <h4>Crecimiento Sostenible</h4>
                                <p>Construimos estrategias pensadas para el largo plazo, ayudando a que tu marca crezca de forma constante en el mercado de insecticidas.</p>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-paper-plane-o"></i>
                                <div class="separator"></div>
                                <h4>Campañas Publicitarias</h4>
                                <p>Creamos campañas efectivas para redes sociales y medios digitales, enfocadas en dar visibilidad a tus productos insecticidas.</p>
                            </div>
                        </div>

                        <div class="col-md-3 col-sm-6 col-xs-12">
                            <div class="community-edition">
                                <i class="fa fa-folder-open"></i>
                                <div class="separator"></div>
                                <h4>Reportes de Resultados</h4>
                                <p>Entregamos informes claros sobre el desempeño de cada campaña, para que siempre sepas cómo está creciendo tu marca.</p>
                            </div>
                        </div>

                    </div>
                </div>
            </div> <!-- /container -->       
        </section>


        <section id="contact" class="contact sections">
            <div class="container">
                <div class="row">
                    <div class="main_contact whitebackground">
                        <div class="head_title text-center">
                            <h2>GET IN TOUCH</h2>
							<p>¿Tienes alguna duda o quieres impulsar tu marca? Escríbenos y con gusto te ayudaremos a encontrar la mejor estrategia de marketing para tu negocio.</p>
                        </div>
                        <div class="contact_content">
                            <div class="col-md-6">
                                <div class="single_left_contact">
                                    <form action="#" id="formid">

                                        <div class="form-group">
                                            <input type="text" class="form-control" name="name" placeholder="first name" required="">
                                        </div>

                                        <div class="form-group">
                                            <input type="email" class="form-control" name="email" placeholder="Email" required="">
                                        </div>


                                        <div class="form-group">
                                            <textarea class="form-control" name="message" rows="8" placeholder="Message"></textarea>
                                        </div>

                                        <div class="center-content">
                                            <input type="submit" value="Submit" class="btn btn-default">
                                        </div>
                                    </form>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="single_right_contact">
                                    <p>En UBICONTROL estamos comprometidos con brindar un servicio cercano y de calidad. Si deseas conocer más sobre nuestros servicios o solicitar una asesoría, contáctanos. Estaremos felices de ayudarte a hacer crecer tu marca con estrategias de marketing creativas y efectivas.</p>

                                    <div class="contact_address margin-top-40">
                                        <span>Diagonal 11 # 6-62, El Puerto</span>
                                        <span>Ubalá, Cundinamarca, Colombia</span> 
                                        <span class="margin-top-20">T: +57 322 830 2152</span> 
                                        <span>Servicio en línea y atención personalizada</span> 
                                    </div>

                                    <div class="contact_socail_bookmark">
                                        <a href="#"><i class="fa fa-facebook"></i></a>
                                        <a href="#"><i class="fa fa-twitter"></i></a>
                                        <a href="#"><i class="fa fa-google"></i></a>
                                    </div>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section><!-- End of Contact Section -->


        <section id="footer-menu" class="sections footer-menu">
            <div class="container">
                <div class="row">
                    <div class="footer-menu-wrapper">

                        <div class="col-md-8 col-sm-12 col-xs-12">
                            <div class="col-md-4 col-sm-6 col-xs-12">
                                <div class="menu-item">
                                    <h5>Enlaces</h5>
                                    <ul>
                                        <li><a href="#home">Inicio</a></li>
                                        <li><a href="#service">Servicios</a></li>
                                        <li><a href="#price">Precios</a></li>
                                        <li><a href="#business">Portafolio</a></li>
                                        <li><a href="#contact">Contacto</a></li>
                                    </ul>
                                </div>
                            </div>

                            <div class="col-md-4 col-sm-6 col-xs-12">
                                <div class="menu-item">
                                    <h5>Legal</h5>
                                    <ul>
                                        <li><a href="#">Política de Privacidad</a></li>
                                        <li><a href="#">Términos de Uso</a></li>
                                        <li><a href="#">Aviso Legal</a></li>
                                    </ul>
                                </div>
                            </div>

                            <div class="col-md-4 col-sm-6 col-xs-12">
                                <div class="menu-item">
                                    <h5>Información</h5>
                                    <ul>
                                        <li><a href="#contact">Soporte</a></li>
                                        <li><a href="#features">Sobre Nosotros</a></li>
                                        <li><a href="#service">Servicios</a></li>
                                        <li><a href="#price">Planes</a></li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-4 col-sm-6 col-xs-12">
                            <div class="menu-item">
                                <h5>Boletín</h5>
                                <p>Recibe consejos de marketing y novedades para hacer crecer tu marca de insecticidas.</p>
                                <form action="#" class="input-group">
                                    <input type="email" class="form-control" placeholder="Ingresa tu correo electrónico">
                                    <input type="submit" class="form-control" value="Suscribirme">
                                </form>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>


        <!--Footer-->
        <footer id="footer" class="footer">
            <div class="container">
                <div class="row">
                    <div class="footer-wrapper">

                        <div class="col-md-6 col-sm-6 col-xs-12">
                            <div class="footer-brand">
                                <img src="assets/images/logo_1.png" alt="UBICONTROL" style="max-height: 90px; width: auto;" />
                            </div>
                        </div>

                        <div class="col-md-6 col-sm-6 col-xs-12">
                            <div class="copyright">
                                <p>Hecho con <i class="fa fa-heart"></i> por el equipo de UBICONTROL &copy; 2026. Todos los derechos reservados.</p>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </footer>
		
		
		<div class="scrollup">
			<a href="#"><i class="fa fa-chevron-up"></i></a>
		</div>


        <script src="assets/js/vendor/jquery-1.11.2.min.js"></script>
        <script src="assets/js/vendor/bootstrap.min.js"></script>

        <script src="assets/js/plugins.js"></script>
        <script src="assets/js/modernizr.js"></script>
        <script src="assets/js/main.js"></script>
    </body>
</html>

