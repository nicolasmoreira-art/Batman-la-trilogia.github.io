Alumno: Nicolas Moreira
Carrera: Diseño Multimedial
Comision: DMM2BP
Turno: Mañana
Año: 2025
https://nicolasmoreira-art.github.io/la-trilogia-del-batman-de-nolan.github.io/#Batman
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nicolas Moreira - DMM2BP - Turno mañana - 2025</title>
  
  <!-- Bootstrap 5 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <!-- Tu CSS -->
  <link rel="stylesheet" href="css/estilos.css">
</head>

<body>

<!-- 🔹 NAVBAR BOOTSTRAP -->
<header>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#banner">
        <img src="imagenes/imagenes/Logo Alpha Locks.png" alt="Logo Alpha Locks" width="120">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#Batman">Batman</a></li>
          <li class="nav-item"><a class="nav-link" href="#Peliculas">Películas</a></li>
          <li class="nav-item"><a class="nav-link" href="#Director">Director</a></li>
          <li class="nav-item"><a class="nav-link" href="#Opiniones">Opiniones</a></li>
          <li class="nav-item"><a class="nav-link" href="#Contacto">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>
</header>

<!-- 🔹 BANNER CON CAROUSEL BOOTSTRAP -->
<section id="banner" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <!-- Primer Imagen (activa) -->
    <div class="carousel-item active">
      <img src="imagenes/imagenes/Batman.jpg" class="d-block w-100" alt="Batman">
      <div class="carousel-caption d-none d-md-block">
        <h1 class="titulo">THE BATMAN</h1>
        <h2 class="subtitulo">DE CHRISTOPHER NOLAN</h2>
      </div>
    </div>
    <!-- Segunda Imagen -->
    <div class="carousel-item">
      <img src="imagenes/imagenes/batman banner 2.jpg" class="d-block w-100" alt="Batman2">
      <div class="carousel-caption d-none d-md-block">
        <h1 class="titulo">THE BATMAN</h1>
        <h2 class="subtitulo">DE CHRISTOPHER NOLAN</h2>
      </div>
    </div>
   

  <!-- Controles del carrusel -->
  <button class="carousel-control-prev" type="button" data-bs-target="#banner" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Anterior</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#banner" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Siguiente</span>
  </button>
</section>

<!-- 🔹 SECCIÓN BATMAN -->
<section id="Batman" class="container bloque-info mt-5">
  <div class="texto">
    <h2>La evolución de Batman según Nolan</h2>
    <p>  La figura de Batman ha sido reinterpretada muchas veces a lo largo del cine, pero bajo la visión de Christopher Nolan
    alcanzó una profundidad inédita. En su trilogía, el héroe deja de ser una máscara para convertirse en el reflejo de un
    ser humano marcado por el trauma, la pérdida y la búsqueda constante de sentido. Nolan muestra que detrás del símbolo
    hay un hombre que lucha no solo contra el crimen, sino contra sus propios límites.</p>

    <p>
    Desde sus primeros pasos como vigilante, Bruce Wayne es retratado como alguien que canaliza su miedo en fuerza. La
    oscuridad de Gotham no solo lo rodea, sino que lo moldea. Cada golpe, cada caída y cada derrota lo transforman en un
    guerrero más consciente de lo que representa. Batman no nace de la venganza, sino de la necesidad de justicia en un mundo
    donde las instituciones han fallado.
  </p>

  <p>
    A medida que las películas avanzan, también evoluciona su manera de entender el heroísmo. Lo que comienza como una lucha
    física se convierte en una batalla moral. Nolan plantea a Batman como un símbolo que trasciende al individuo: cualquiera
    puede portar la máscara si mantiene viva la idea de resistencia ante la corrupción y el miedo.
  </p>

  <p>
    El conflicto interior es una constante. Bruce Wayne debe aprender a equilibrar su identidad personal con su deber como
    protector de Gotham. En su viaje, el héroe se enfrenta a la soledad, al sacrificio y a las consecuencias de sus propias
    decisiones. Esta dualidad entre el hombre y el mito se convierte en el corazón emocional de toda la trilogía.
  </p>

  <p>
    Lo interesante del enfoque de Nolan es que nunca presenta a Batman como un ser invencible. Su cuerpo se desgasta, su fe
    flaquea y su determinación es puesta a prueba una y otra vez. Sin embargo, es justamente esa fragilidad lo que lo hace
    humano y cercano. La fuerza de Batman no proviene de su traje ni de su tecnología, sino de su capacidad para volver a
    levantarse cada vez que cae.
  </p>

  <p>
    Al final, la evolución de Batman no solo es física o narrativa, sino también simbólica. El héroe se transforma en una
    idea: la de que incluso en la oscuridad más profunda puede existir una chispa de esperanza. Nolan logra que el mito del
    murciélago trascienda la pantalla para recordarnos que cualquiera puede ser un héroe, siempre que tenga el valor de
    enfrentar sus propios miedos.
  </p>

  </div>
</section>

<!-- 🔹 SECCIÓN PELÍCULAS (CARDS DE BOOTSTRAP) -->
<section id="Peliculas" class="container bloque-info">
  <h2 class="titulo-nolan text-center mb-4">La Trilogía de Nolan</h2>
  <div class="row justify-content-center g-4">

    <!-- Batman Begins -->
    <div class="col-md-4">
      <div class="card bg-dark text-light h-100">
        <img src="imagenes/imagenes/Batman 1.jpg" class="card-img-top" alt="Batman Begins">
        <div class="card-body">
          <h5 class="card-title text-warning">Batman Begins</h5>
          <p class="card-text">Bruce Wayne, marcado por el asesinato de sus padres, viaja por el mundo en busca de entender el crimen y la justicia. Bajo el entrenamiento de la Liga de las Sombras, aprende a dominar sus miedos y regresa a Gotham para enfrentarse a la corrupción. Allí nace Batman, un símbolo que inspira esperanza en una ciudad dominada por el miedo.</p>
          
          <!-- Botón Ver Más -->
          <button class="btn btn-warning w-100 mb-2" type="button" data-bs-toggle="collapse" data-bs-target="#batmanBeginsCharacters" aria-expanded="false" aria-controls="batmanBeginsCharacters">
            Ver más
          </button>
          
          <!-- Collapse con personajes -->
          <div class="collapse" id="batmanBeginsCharacters">
            <div class="mt-3">
              <div class="d-flex flex-wrap justify-content-center gap-3">
                <div class="text-center">
                  <img src="imagenes/imagenes/batman personaje 1.jpg" class="rounded" width="80" alt="Batman">
                  <p class="mb-0 text-warning">Batman</p>
                </div>
                <div class="text-center">
                  <img src="imagenes/imagenes/Vilano pelicula 1.jpg" class="rounded" width="80" alt="Ra's al Ghul">
                  <p class="mb-0 text-warning">Ra's al Ghul</p>
                </div>
                <div class="text-center">
                  <img src="imagenes/imagenes/alfred.jpg" class="rounded" width="80" alt="Alfred">
                  <p class="mb-0 text-warning">Alfred</p>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </div>

    <!-- The Dark Knight -->
    <div class="col-md-4">
      <div class="card bg-dark text-light h-100">
        <img src="imagenes/imagenes/batman 2.jpg" class="card-img-top" alt="The Dark Knight">
        <div class="card-body">
          <h5 class="card-title text-warning">The Dark Knight</h5>
          <p class="card-text">Batman se enfrenta a su mayor desafío: el Joker, un criminal caótico que busca destruir el orden moral de Gotham. A medida que el caos se extiende, Bruce Wayne debe elegir entre ser un héroe o un fugitivo. La película explora los límites del sacrificio y la delgada línea entre el bien y el mal.</p>
          
          <button class="btn btn-warning w-100 mb-2" type="button" data-bs-toggle="collapse" data-bs-target="#darkKnightCharacters" aria-expanded="false" aria-controls="darkKnightCharacters">
            Ver más
          </button>
          
          <div class="collapse" id="darkKnightCharacters">
            <div class="mt-3">
              <div class="d-flex flex-wrap justify-content-center gap-3">
                <div class="text-center">
                  <img src="imagenes/imagenes/Batman personaje 2.jpg" class="rounded" width="80" alt="Batman">
                  <p class="mb-0 text-warning">Batman</p>
                </div>
                <div class="text-center">
                  <img src="imagenes/imagenes/jocker pelicula 2.jpg" class="rounded" width="80" alt="Joker">
                  <p class="mb-0 text-warning">Joker</p>
                </div>
                <div class="text-center">
                  <img src="imagenes/imagenes/2 caras.jpg" class="rounded" width="80" alt="Harvey Dent">
                  <p class="mb-0 text-warning">Harvey Dent</p>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </div>

    <!-- The Dark Knight Rises -->
    <div class="col-md-4">
      <div class="card bg-dark text-light h-100">
        <img src="imagenes/imagenes/batman 3.jpg" class="card-img-top" alt="The Dark Knight Rises">
        <div class="card-body">
          <h5 class="card-title text-warning">The Dark Knight Rises</h5>
          <p class="card-text">Ocho años después de los eventos anteriores, Gotham vive en una falsa paz. Sin embargo, un nuevo enemigo, Bane, amenaza con destruir todo lo que Batman defendió. Bruce Wayne debe salir del retiro, superar su dolor y demostrar que el verdadero poder del héroe no está en su fuerza, sino en su capacidad para levantarse una vez más.</p>
          
          <button class="btn btn-warning w-100 mb-2" type="button" data-bs-toggle="collapse" data-bs-target="#darkKnightRisesCharacters" aria-expanded="false" aria-controls="darkKnightRisesCharacters">
            Ver más
          </button>
          
          <div class="collapse" id="darkKnightRisesCharacters">
            <div class="mt-3">
              <div class="d-flex flex-wrap justify-content-center gap-3">
                <div class="text-center">
                  <img src="imagenes/imagenes/Batman personaje 3.jpg" class="rounded" width="80" alt="Batman">
                  <p class="mb-0 text-warning">Batman</p>
                </div>
                <div class="text-center">
                  <img src="imagenes/imagenes/Bane villano 3.png" class="rounded" width="80" alt="Bane">
                  <p class="mb-0 text-warning">Bane</p>
                </div>
                <div class="text-center">
                  <img src="imagenes/imagenes/gatubela.jpg" class="rounded" width="80" alt="Catwoman">
                  <p class="mb-0 text-warning">Catwoman</p>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </div>

  </div>
</section>

<!-- 🔹 SECCIÓN PERSONAJES PRINCIPALES (Bootstrap) -->
<section id="Personajes" class="container bloque-info my-5">
  <h2 class="titulo-nolan text-center mb-4">Personajes Principales</h2>

  <div class="row justify-content-center g-4">
    
    <!-- Batman -->
    <div class="col-12 col-md-6">
      <div class="card bg-dark text-light border-warning shadow personaje">
        <img src="imagenes/imagenes/Batman 4.jpg" class="card-img-top" alt="Batman">
        <div class="card-body descripcion text-center">
          <h5 class="card-title text-warning nombre">Batman / Bruce Wayne</h5>
          <p class="card-text">Millonario y vigilante de Gotham, símbolo de disciplina y justicia frente al crimen.</p>
        </div>
      </div>
    </div>

    <!-- Joker -->
    <div class="col-12 col-md-6">
      <div class="card bg-dark text-light border-warning shadow personaje">
        <img src="imagenes/imagenes/jocker.jpg" class="card-img-top" alt="Joker">
        <div class="card-body descripcion text-center">
          <h5 class="card-title text-warning nombre">El Joker</h5>
          <p class="card-text">Agente del caos que enfrenta a Batman, obligándolo a desafiar sus propios límites morales.</p>
        </div>
      </div>
    </div>

    <!-- Alfred -->
    <div class="col-12 col-md-6">
      <div class="card bg-dark text-light border-warning shadow personaje">
        <img src="imagenes/imagenes/Alfred 2.jpg" class="card-img-top" alt="Alfred">
        <div class="card-body descripcion text-center">
          <h5 class="card-title text-warning nombre">Alfred Pennyworth</h5>
          <p class="card-text">Leal mayordomo y figura paterna de Bruce, aporta la guía moral y el apoyo emocional.</p>
        </div>
      </div>
    </div>

    <!-- Gordon -->
    <div class="col-12 col-md-6">
      <div class="card bg-dark text-light border-warning shadow personaje">
        <img src="imagenes/imagenes/Gordon.jpg" class="card-img-top" alt="Gordon">
        <div class="card-body descripcion text-center">
          <h5 class="card-title text-warning nombre">Jim Gordon</h5>
          <p class="card-text">Aliado fiel de Batman, símbolo de justicia y moral dentro de la policía de Gotham.</p>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- 🔹 SECCIÓN VIDEO -->
<div class="video-container">
  <h2 class="titulo-nolan">Video Alusivo</h2>
  <iframe 
    src="https://www.youtube.com/embed/TsLEolNcXug"
    title="Batman - Video principal"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>


<!-- 🔹 SECCIÓN DIRECTOR -->
<section id="Director" class="container bloque-info director-section">
  <h2 class="titulo-director text-center mb-5">Biografía</h2>
  <div class="row align-items-center justify-content-center">
    <div class="col-md-4 text-center mb-4 mb-md-0">
      <img src="imagenes/imagenes/cristopher nolan.jpg" alt="Christopher Nolan" class="img-fluid rounded shadow-img">
    </div>
    <div class="col-md-7">
      <div class="bio-box p-4">
      <h3>Biografía</h3>
      <p>Christopher Nolan es un director, guionista y productor británico nacido en Londres en 1970. Reconocido por su estilo visual preciso y sus historias no lineales, se consolidó como uno de los cineastas más influyentes del siglo XXI. Su trilogía de The Dark Knight revolucionó el género de superhéroes, mientras que películas como Inception e Interstellar lo consagraron a nivel mundial. En 2024, ganó el Óscar a Mejor Director por Oppenheimer, reafirmando su lugar como un autor que combina innovación, emoción y espectacularidad cinematográfica.</p>
       </div>
    </div>
  </div>
</section>


<!-- 🔹 SECCIÓN OPINIONES -->
<section id="Opiniones" class="container bloque-info">
  <h2 class="titulo-seccion">Opiniones de los Fans</h2>
  <div class="row justify-content-center g-4">
    <div class="col-md-3 text-center">
      <img src="imagenes/imagenes/Persona 1.png" class="foto-fan">
      <p class="comentario">Batman en la trilogía de Nolan es el más duro y frío que yo vi. Nunca pierde su esencia en ninguna de las tres películas</p>
      <p class="nombre-fan">Dante Rattalino</p>
    </div>
    <div class="col-md-3 text-center">
      <img src="imagenes/imagenes/Persona 2.png" class="foto-fan">
      <p class="comentario">Nolan crea tensión y atmósfera únicas, haciendo que villanos como Joker y Bane sean memorables y auténticos </p>
      <p class="nombre-fan">Agustin Rodriguez</p>
    </div>
    <div class="col-md-3 text-center">
      <img src="imagenes/imagenes/Persona 3.png" class="foto-fan">
      <p class="comentario">Nolan combina técnica y narrativa inteligente, con realismo y efectos impactantes, destacándose como un director influyente</p>
      <p class="nombre-fan">Ezequiel Cerutti</p>
    </div>
  </div>
</section>


<section id="Noticias" class="container bloque-info mt-5">
  <h2 class="titulo-nolan text-center mb-5">Noticias</h2>

  <div class="row justify-content-center g-4">
    <!-- Noticia 1 -->
    <div class="col-md-5">
      <div class="card bg-dark text-light h-100 border-warning shadow-lg">
        <img src="imagenes/imagenes/noticia 1.jpg" class="card-img-top" alt="Christopher Nolan">
        <div class="card-body">
          <h4 class="card-title text-warning">21/09/2025 - Christopher Nolan</h4>
          <p class="card-text">Christopher Nolan fue elegido presidente del Directors Guild of America, consolidándose como una figura influyente en la industria tras el éxito de "Oppenheimer".</p>
        </div>
      </div>
    </div>

    <!-- Noticia 2 -->
    <div class="col-md-5">
      <div class="card bg-dark text-light h-100 border-warning shadow-lg">
        <img src="imagenes/imagenes/noticia 2.jpg" class="card-img-top" alt="The Batman 2">
        <div class="card-body">
          <h4 class="card-title text-warning">19/09/2025 - The Batman 2</h4>
          <p class="card-text">Matt Reeves indicó que "The Batman 2" podría ser la última película de Robert Pattinson como Batman, aunque sus historias seguirán siendo independientes dentro del Universo DC.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 🔹 SECCIÓN CONTACTO -->
<section id="Contacto" class="container bloque-info">
  <h2 class="titulo-nolan text-center">Formulario de Contacto</h2>
  <form action="mailto:tuemail@ejemplo.com" method="post" enctype="text/plain" class="mt-4 w-75 mx-auto">
<!-- 🔸 Fila con 3 columnas (Nombre, Apellido, Email) -->
    <div class="row mb-3">
      <div class="col-md-4">
        <label for="nombre" class="form-label">Nombre</label>
        <input type="text" class="form-control" id="nombre" name="nombre" required>
      </div>
      <div class="col-md-4">
        <label for="apellido" class="form-label">Apellido</label>
        <input type="text" class="form-control" id="apellido" name="apellido" required>
      </div>
      <div class="col-md-4">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" name="email" required>
      </div>
    </div>
<!-- 🔸 Campo Comentario -->
    <div class="mb-3">
      <label for="comentario" class="form-label">Comentario</label>
      <textarea class="form-control" id="comentario" name="comentario" rows="4" required></textarea>
    </div>
<!-- 🔸 Botón -->
    <div class="text-center">
      <button type="submit" class="btn btn-warning px-5">Enviar</button>
    </div>
  </form>
</section>


<!-- 🔹 FOOTER -->
<footer class="footer mt-5">
  <div class="container text-center">
    <div class="datos mb-3">
      <ul class="list-unstyled">
        <li><strong>Nombre:</strong> Moreira Nicolas</li>
        <li><strong>Materia:</strong> Maquetado y Desarrollo Web</li>
        <li><strong>Turno:</strong> Mañana</li>
        <li><strong>Comisión:</strong> DMM2BP</li>
        <li><strong>Año:</strong> 2025</li>
      </ul>
    </div>
    <div class="redes">
      <a href="https://instagram.com" target="_blank"><i class="fa-brands fa-square-instagram"></i></a>
      <a href="https://facebook.com" target="_blank"><i class="fa-brands fa-square-facebook"></i></a>
      <a href="https://x.com" target="_blank"><i class="fa-brands fa-square-x-twitter"></i></a>
    </div>
  </div>
</footer>

</body>
</html>
