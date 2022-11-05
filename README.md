### Hola mi nombre es Gonzalo Oyarzun Soy Analista programador 👋 

<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css"
        integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Portfolio</title>
    <link rel="stylesheet" href="estilo.css">
</head>

<body>
    <!-- MENU ENCABEZADO -->
    <div class="contenedor-header">
        <header>
            <div class="logo">
                <a href="#">Gonzalo</a>
            </div>
            <nav id="nav">
                <ul>
                    <li><a href="#inicio" onclick="seleccionar()">INICIO</a></li>
                    <li><a href="#sobremi" onclick="seleccionar()">SOBRE MI</a></li>
                    <li><a href="#skills" onclick="seleccionar()">SKILLS</a></li>
                    <li><a href="#curriculum" onclick="seleccionar()">CURRICULUM</a></li>
                    <li><a href="#portfolio" onclick="seleccionar()">PORTFOLIO</a></li>
                    <li><a href="#contacto" onclick="seleccionar()">CONTACTO</a></li>
                </ul>
            </nav>
            <div class="nav-responsive" onclick="mostrarOcultarMenu()">
                <i class="fa-solid fa-bars"></i>
            </div>
        </header>
    </div>

    <!-- SECCION INICIO -->
    <section id="inicio" class="inicio">
        <div class="contenido-banner">
            <div class="contenedor-img">
                <img src="img/hero5.png" alt="">
            </div>
            <h1>GONZALO OYARZUN</h1>
            <h2>Analista Programador - Desarrollador Front End</h2>
            <div class="redes">
                <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-skype"></i></a>
                <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
                <a href="#"><i class="fa-solid fa-rss"></i></a>
            </div>
        </div>
    </section>

    <!-- SECCION SOBRE MI -->
    <section id="sobremi" class="sobremi">
        <div class="contenido-seccion">
            <h2>Sobre Mí</h2>
            <p><span>Hola, Mi nombre es Gonzalo Oyarzun.</span> Soy Titulado de la carrera Analista programador del
                centro de
                formacion tecnica INACAP, en el año 2021 Actualmente tengo 30 años me gusta mucho la tecnolgia y la
                programacion, me considero una persona con capacidad para trabajar en equipo y en situaciones de
                presion,
                ademas poseo muchas ganas de aprender y tengo una gran iniciativa propia.</p>

            <div class="fila">
                <!-- datos personales -->
                <div class="col">
                    <h3>Datos Personales</h3>
                    <ul>
                        <li>
                            <strong>Cumpleaños</strong>
                            03-01-1992
                        </li>
                        <li>
                            <strong>Teléfono</strong>
                            +569 78967336
                        </li>
                        <li>
                            <strong>Email</strong>
                            goyarzunpanes@gmail.com
                        </li>
                        <li>
                            <strong>Website</strong>
                            www.example.com
                        </li>
                        <li>
                            <strong>Dirección</strong>
                            Puente Alto Santiago de Chile
                        </li>
                        <li>
                            <strong>Cargo</strong>
                            <span>PROGRAMADOR COMPUTACIONAL</span>
                        </li>
                    </ul>
                </div>

                <!-- intereses -->
                <div class="col">
                    <h3>Intereses</h3>
                    <div class="contenedor-intereses">
                        <div class="interes">
                            <i class="fa-solid fa-gamepad"></i>
                            <span>JUEGOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-headphones"></i>
                            <span>MUSICA</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-plane"></i>
                            <span>VIAJAR</span>
                        </div>
                        <div class="interes">
                            <i class="fa-sharp fa-solid fa-code"></i>
                            <span>CODE</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-person-hiking"></i>
                            <span>DEPORTE</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-book"></i>
                            <span>LIBROS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-car"></i>
                            <span>AUTOS</span>
                        </div>
                        <div class="interes">
                            <i class="fa-solid fa-camera"></i>
                            <span>FOTOS</span>
                        </div>

                    </div>
                </div>
            </div>
            <button>
                Descargar CV <i class="fa-solid fa-download"></i>
                <span class="overlay"></span>
            </button>
        </div>
    </section>

    <!-- SECCION SKILLS -->
    <section class="skills" id="skills">
        <div class="contenido-seccion">
            <h2>Skills</h2>
            <div class="fila">
                <!-- Technical Skill -->
                <div class="col">
                    <h3>Technical Skills</h3>
                    <div class="skill">
                        <span>Javascript</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>50%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>HTML & CSS</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>50%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>MySQL</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>30%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Wordpress</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>50%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Laravel</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>55%</span>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Professional Skills -->
                <div class="col">
                    <h3>Professional Skills</h3>
                    <div class="skill">
                        <span>Comunicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>80%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Trabajo en Equipo</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>70%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Creatividad</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>99%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Dedicación</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>65%</span>
                            </div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>Proyect Management</span>
                        <div class="barra-skill">
                            <div class="progreso">
                                <span>50%</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION CURRICULUM -->
    <section id="curriculum" class="curriculum">
        <div class="contenido-seccion">
            <h2>Curriculum</h2>
            <div class="fila">
                <div class="col izquierda">
                    <h3>Educación</h3>
                    <div class="item izq">
                        <h4>Analista Programador</h4>
                        <span class="casa">Centro de Formacion Tecnica INACAP</span>
                        <span class="fecha">2018 - 2021</span>
                        <p>Titulado de Analista Programador del centro de formacion tecnica INACAP sede Santiago sur año
                            de Titulacion 2021.</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <div class="item izq">
                        <h4>Curso de Programacion Web</h4>
                        <span class="casa">OTEC Sustantiva</span>
                        <span class="fecha">2021</span>
                        <p>Certificado de curso PROGRAMACION WEB curso de verano aprobando capacitacion de 348 horas</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div>
                    <!-- <div class="item izq">
                        <h4>Arte y Multimedia</h4>
                        <span class="casa">Universidad de Oxford</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora
                            recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta
                            aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectori">
                            <div class="circuloi"></div>
                        </div>
                    </div> -->
                </div>

                <div class="col derecha">
                    <h3>Experiencia de trabajo</h3>
                    <div class="item der">
                        <h4>Programador Computacional</h4>
                        <span class="casa">Direccion de Bienestar de Carabineros de Chile</span>
                        <span class="fecha">marzo 2022 - agosto 2022</span>
                        <p>Principalmente mi funcion dentro de este trabajo fue participar en el desarrollo y mantencion
                            de los modulos de la plataforma web del fondo de ahorro desarrollandome como programador
                            junior en los lenguajes PHP, JS, HTML, CSS Boostrap y un framework de PHP llamado
                            CodeIgniter, Ademas de apoyar en la cuadratura historica en conjunto con el departamento de
                            contabilidad del fondo de ahorro buscando posibles errores contables con el apoyo del
                            sistema ANZIO.</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Programador Junior</h4>
                        <span class="casa">Digital Product Manager, Medicina / Salud</span>
                        <span class="fecha">agosto 2021 - Septiembre 2021</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora
                            recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta
                            aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                    <div class="item der">
                        <h4>Front Developer</h4>
                        <span class="casa">Nombre de Compañía</span>
                        <span class="fecha">2005 - 2008</span>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis, cumque repellat, tempora
                            recusandae aliquam nemo esse natus impedit, nostrum temporibus veritatis eaque soluta
                            aperiam id repudiandae fugiat deserunt! Explicabo, veritatis?</p>
                        <div class="conectord">
                            <div class="circulod"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION PORTFOLIO -->
    <section id="portfolio" class="portfolio">
        <div class="contenido-seccion">
            <h2>PORTFOLIO</h2>
            <div class="galeria">
                <div class="proyecto">
                    <img src="img/p1.jpg" alt="">
                    <div class="overlay">
                        <h3>Proyecto de Muestra</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p2.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p3.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p4.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p5.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
                <div class="proyecto">
                    <img src="img/p6.jpg" alt="">
                    <div class="overlay">
                        <h3>Diseño Creativo</h3>
                        <p>Fotografía</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION CONTACTO -->
    <section id="contacto" class="contacto">
        <div class="contenido-seccion">
            <h2>CONTACTO</h2>
            <div class="fila">
                <!-- Formulario -->
                <div class="col">
                    <input type="text" placeholder="Tú Nombre">
                    <input type="text" placeholder="Número telefónico">
                    <input type="text" placeholder="Dirección de correo">
                    <input type="text" placeholder="Tema">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Mensaje"></textarea>
                    <button>
                        Enviar Mensaje<i class="fa-solid fa-paper-plane"></i>
                        <span class="overlay"></span>
                    </button>
                </div>
                <!-- Mapa -->
                <div class="col">
                    <img src="img/ubicacion.png" alt="">
                    <div class="info">
                        <ul>
                            <li>
                                <i class="fa-solid fa-location-dot"></i>
                                Nicaragua 159, San Rafael Mza
                            </li>
                            <li>
                                <i class="fa-solid fa-mobile-screen"></i>
                                Llamanos: 2384 - 4343443
                            </li>
                            <li>
                                <i class="fa-solid fa-envelope"></i>
                                Email: cw@example.com
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- footer -->
    <footer>
        <a href="#inicio" class="arriba">
            <i class="fa-solid fa-angles-up"></i>
        </a>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
            <a href="#"><i class="fa-brands fa-skype"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
            <a href="#"><i class="fa-solid fa-rss"></i></a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>

</html>
<!--
**xchalooyarzun/xchalooyarzun** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
