/* Barra de navegacion */

.navbar {
  padding: 2rem;
  background-color: #f5f6f7;
}

.navbar-collapse {
  align-items: center;
  justify-content: space-between;  
}

/* Estilos generales */

section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

h1 {
  font-size: 2.5rem;
  font-family: 'Rubik Dirt', cursive;
}

.seccion-oscura {
  color: white;
  background-color: #1b1b32;
}

.seccion-clara {
  color: black;
  background-color: white;
}

.seccion-titulo {
  font-size: 2rem;
  padding: 15px 0;
  font-family: 'Rubik Dirt', cursive;
}

.seccion-descripcion {
  font-size: 1.2rem;
  color: #584e4e;
}

.seccion-texto {
  font-size: 1.2rem;
}

.btn-info {
  font-size: 1.1rem;
  margin: 20px;
}

.texto-negro {
  color: black;
}

.texto-blanco {
  color: white;
}

/* Seccion Hero */

.hero {
  background-color: #f5f6f7;
  min-height: 450px;
  text-align: center;
}

.hero-principal {
  padding: 3rem;
}

.hero-imagen-desarrollador {
  width: 200px;
  height: 200px;
  margin: 20px;
}

.hero-principal h2 {
  font-size: 1.5rem;
  color: #615151;
}

/* Sobre mi */

.sobre-mi {
  height: 500px;
  padding: 10px;
}

.sobre-mi .contenedor {
  max-width: 600px;
  text-align: center;
}

/* Experiencia */

.experiencia {
  padding: 40px 40px 60px 40px;
}

.experiencia .columna {
  padding: 20px;
  border: 2px solid #8080804d;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
  transition: all 0.2s ease-in;
}

.experiencia .columna:hover {
  color: white;
  background-color: #1b1b32;
}

.experiencia i {
  font-size: 2.5rem;
  color: #7ade30;
  background-color: #0a0a23;
  padding: 8px 19px;
  border-radius: 50%;
}

.experiencia-titulo {
  font-size: 25px;
  font-weight: bold;
  margin: 10px 0;
}

.badges-contenedor {
  font-size: 20px;
  font-weight: bold;
  margin: 10px 0;
}

.badge {
  margin: 5px;
}

/* Proyectos */

.proyectos-recientes {
  padding: 40px;
}

.proyectos-recientes img {
  height: 100%;
  width: 100%;
  padding: 10px;
  border-radius: 10px;
  display: block;
  transition: all 0.2s ease;
}

.proyectos-contenedor {
  padding-top: 60px;
  margin-bottom: 40px;
}

.overlay {
  transition: all 0.2s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.overlay p {
  font-size: 25px;
  font-weight: bold;
  margin-bottom: 0;
}

.proyecto {
  position: relative;
}

.proyecto:hover img {
  opacity: 0.2;
}

.proyecto:hover .overlay {
  opacity: 1;
}

.overlay .iconos-contenedor {
  display: flex;
}

.overlay i {
  color: black;
  font-size: 60px;
  margin: 10px;
}

/* Articulos */

.articulos {
  min-height: 500px;
  padding: 30px;
}

.articulos .card {
  width: 80%;
  max-width: 600px;
  margin: 20px;
}

.articulos .card-header {
  font-weight: bold;
}

/* Testimonios */

.testimonios {
  padding: 40px 40px 80px 40px;
}

.testimonios .carousel {
  max-width: 800px;
}

.carousel-item {
  height: 500px;
}

.carousel-item .container {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.testimonio-imagen {
  height: 150px;
  width: 150px;
  margin: 10px 10px 20px 10px;
}

.testimonio-texto {
  max-width: 70%;
  font-size: 20px;
  text-align: center;
  font-family: 'Share Tech Mono', monospace;
}

.testimonio-info {
  font-weight: bold;
  text-align: center;
}

.testimonio-info p {
  margin-bottom: 0;
}

.testimonio-footer .cliente {
  font-size: 1.2rem;
}

.testimonio-info .cargo {
  font-size: 0.9rem;
  color: #656060;
}

/* Contacto */

.contacto .container {
  max-width: 1100px;
  min-height: 200px;
  padding: 20px;
}

.contacto .rectangulo {
  margin-top: -5rem;
  background-color: rgb(13, 110, 253);
  border-radius: 10px;
  box-shadow: 0px 1px 4px 1px white;
}

.contacto .row {
  width: 100%;
  display: flex;
  align-items: center;
}

.contacto .descripcion {
  color: white;
  font-size: 1.2rem;
}

.contacto button {
  color: white;
  font-weight: bold;
  background-color: transparent;
  border: 2px solid white;
  padding: 1.25em 2em;
  margin: 10px;
  border-radius: 100px;
  transition: all 0.2s ease-in-out;
}

.contacto button:hover {
  background-color: white;
  color: black;
}

.contacto button i {
  color: white;
  font-size: 1.3rem;
  transition: all 0.2s ease-in-out;
}

.contacto button:hover i {
  color: black;
}

/* Pie de pagina (footer) */

footer {
  min-height: 500px;
}

.footer-logo {
  height: 80px;
  width: 80px;
  margin: 10px;
}

.footer-texto {
  font-size: 1.5rem;
  padding: 20px;
  margin-bottom: 30px;
  font-family: 'Quicksand', sans-serif;
}

.iconos-redes-sociales a {
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2px;
  margin: 10px;
  border: 2px solid white;
  border-radius: 50%;
  transition: all 0.2s ease-in;
}

.iconos-redes-sociales i {
  color: white;
  font-size: 1.5rem;
  transition: all 0.2s ease-in;
}

.iconos-redes-sociales a:hover {
  background-color: white;
  border: 2px solid rgb(13, 110, 253);
}

.iconos-redes-sociales a:hover i {
  color: black;
}

.derechos-de-autor {
  font-size: 15px;
  color: #aeaeae;
  padding: 20px;
}

/* Adaptable (Responsivo) */

@media screen and (max-width: 400px) {
  .overlay p {
    font-size: 18px;
  }

  .overlay i {
    font-size: 40px;
  }
}

@media screen and (max-width: 767px) {
  .navbar-brand {
    display: none;
  }
}

@media screen and (max-width: 800px) {
  .testimonio-imagen {
    height: 120px;
    width: 120px;
  }

  .testimonio-texto {
    font-size: 18px;
  }
}

@media screen and (min-width: 700px) {
  .hero-inferior-imagen {
    max-width: 600px;
  }
}
<!DOCTYPE html>
<html lang="es">
  <head>
    <!-- Metadatos -->
    <meta charset="utf-8">
    <meta name="author" content="Jane Doe">
    <meta name="description" content="Portafolio de desarrollo web de Jane Doe">
    <meta name="keywords" content="HTML, CSS, JavaScript, React">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Titulo -->
    <title>Ivan Carrillo | Desarrollo Web Front-End</title>
    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="imagenes/icono.png">
    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <!-- Iconos de Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
    <!-- CSS -->
    <link href="style.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@500&family=Rubik+Dirt&family=Share+Tech+Mono&display=swap" rel="stylesheet">
  </head>
  <body>
    <!-- Barra de navegacion -->
    <nav class="navbar navbar-expand-md navbar-light">
      <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-toggler" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbar-toggler">
          <a class="navbar-brand" href="#">
            <img src="imagenes/icono.png" width="50" alt="Logo de la página web">
          </a>
          <ul class="navbar-nav d-flex justify-content-center align-items-center">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#sobre-mi">Sobre mí</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#proyectos">Proyectos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Seccion Hero -->
    <section class="hero align-items-stretch">
      <div class="hero-principal d-flex flex-column justify-content-center align-items-center">
        <img class="hero-imagen-desarrollador rounded-circle" src="imagenes/imagenes-desarrolladores/desarrollador-ejemplo.svg" alt="Foto de Jane Doe">
        <h1>Hola, soy Ivan Carrillo</h1>
        <h2>Desarrollo sitios web y escribo artículos sobre programación.</h2>
      </div>
      <div class="hero-inferior">
        <img class="hero-inferior-imagen img-fluid" src="imagenes/hero-inferior.svg" alt="Monitor, laptop y logos de HTML, CSS, JavaScript y React.">
      </div>
    </section>
    <!-- Sobre mi -->
    <section id="sobre-mi" class="sobre-mi seccion-oscura">
      <div class="contenedor">
        <h2 class="seccion-titulo">Conoce a Ivan Carrillo</h2>
        <p class="seccion-texto">Mi nombre es Ivan Carrillo, estoy empezando mi carrera como desarrollador de paginas web de calidad. Desde que descubri el potencial creativo y tecnico de la creacion web me he sentido inspirado a realizar trabajos en este campo.</p>
      </div>
    </section>
    <!-- Experiencia -->
    <section class="experiencia seccion-clara">
      <div class="container text-center">
        <div class="row">
          <!-- Desarrollo Web -->
          <div class="columna col-12 col-md-4">
            <i class="bi bi-laptop"></i>
            <p class="experiencia-titulo">Desarrollo Web</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras laoreet, odio eget fringilla scelerisque, sem purus fringilla mauris, nec ultricies nisl nisl sit amet dolor. </p>
            <div class="badges-contenedor">
              <span class="badge text-bg-primary">HTML</span>
              <span class="badge text-bg-primary">CSS</span>
              <span class="badge text-bg-primary">JavaScript</span>
              <span class="badge text-bg-primary">React</span>
            </div>
          </div>
          <!-- Articulos -->
          <div class="columna col-12 col-md-4">
            <i class="bi bi-laptop"></i>
            <p class="experiencia-titulo">Artículos</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras laoreet, odio eget fringilla scelerisque, sem purus fringilla mauris, nec ultricies nisl nisl sit amet dolor. </p>
            <div class="badges-contenedor">
              <span class="badge text-bg-primary">Escribir</span>
              <span class="badge text-bg-primary">Editar</span>
              <span class="badge text-bg-primary">Blogs</span>
            </div>
          </div>
          <!-- Estudiante -->
          <div class="columna col-12 col-md-4">
            <i class="bi bi-laptop"></i>
            <p class="experiencia-titulo">Estudiante</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras laoreet, odio eget fringilla scelerisque, sem purus fringilla mauris, nec ultricies nisl nisl sit amet dolor. </p>
            <div class="badges-contenedor">
              <span class="badge text-bg-primary">freeCodeCamp</span>
              <span class="badge text-bg-primary">Desarrollo Web</span>
              <span class="badge text-bg-primary">Python</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Proyectos -->
    <section id="proyectos" class="proyectos-recientes seccion-clara d-flex flex-column">
      <h2 class="seccion-titulo texto-negro">Mis proyectos recientes</h2>
      <h3 class="seccion-descripcion">Estos son algunos proyectos que he creado recientemente...</h3>
      <!-- Galeria de Proyectos -->
      <div class="container text-center proyectos-contenedor">
        <div class="row">
      <a href="https://github.com/IvnCarr?tab=repositories" target="_blank" rel="noopener noreferrer">
        <button type="button" class="btn btn-info">
          Ver Repositorio
          <i class="bi bi-arrow-right-circle-fill"></i>
        </button>
      </a>
    </section>


  </body>
</html>
