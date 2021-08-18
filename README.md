<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    
    <!--Menu-->
    <div class="section-Menu">
    <nav class="navbar navbar-expand-lg navbar-light ">
        <a class="navbar-brand" href="#">
            <img src="./images/logito.png" height="85" width="95" alt="Logo">
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto navbar-light">
            <li class="nav-item active">
              <a class="nav-link" href="#">Inicio <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Características</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Nosotros</a>
            </li>
       
      
          </ul>
          
        </div>
      </nav>

      <div class="jumbotron bg-transparent">
          <div class="row">
              <div class="col-5">
                <img src="./images/cel-removebg-preview.png" class="img-fluid" alt="jumbotron">
              </div>
              <div class="col-7">
                <h1>Bienvenidos a TutoHelp</h1>
                <p>Aprende o ayuda junto a tus compañeros de clase a través de videoconferias o chats en vivo </p>
                <p>Puede descargar la aplicación por: </p>
                <a href="">Descargar para Android</a>
                <a href="">Descargar para IOS</a>
              </div>
          </div>
      </div>
    </div>

      <div class="servicios">
        <div class="card-group">
            <div class="card bg-transparent">
              <img src="./images/servicio1.png" class="card-img-top" alt="Servicio1">
              <div class="card-body">
                <h5 class="card-title">Videoconferencias y chats en vivo</h5>
                <p class="card-text">Podrás interactuar de forma eficaz y rápida con tus compañeros de clase (estudiante o tutor)</p>
              
              </div>
            </div>
            <div class="card bg-transparent">
              <img src="./images/servicio2.png" class="card-img-top" alt="Servicio2">
              <div class="card-body">
                <h5 class="card-title">Compartir información con tus compañeros</h5>
                <p class="card-text">Tienes la oportunidad de compartir tus exámenes, PC's, controles, etc. Con tus compañeros que recién estan llevando el curso</p>
              
              </div>
            </div>
            <div class="card bg-transparent">
              <img src="./images/servicio3.png" class="card-img-top" alt="Servicio3">
              <div class="card-body">
                <h5 class="card-title">Crear salas virtuales</h5>
                <p class="card-text">Si estás interesado en la enseñanza, puedes crear tus propias salas virtuales personalizadas.</p>
                
              </div>
            </div>
          </div>
      </div>

      <div class="nosotros">
          <div class="row">
              <div class="col-6">
                  <h1>Sobre Nosotros</h1>
                  <p>TutoHelp es una startup sin fines de lucro encargada de ayudar a universitarios a reforzar los temas impartidos en sus centros

                    de estudios. 
                    
                    Si estás en tus primeros ciclos y te sientes algo perdido en los temas que explica tu profesor, no dudes en descargarte TutoHelp
                    
                    y aprender junto a tus compañeros de clases.</p>
              </div>
              <div class="col-6">
                  <img class="img-fluid" src="./images/undraw_book_lover_mkck_preview_rev_1.png" alt="Imagen Servicio">
              </div>
          </div>
      </div>


 <!--Contacto-->
 <div class="contact">
   <div class="row">
     <div class="col-6">
      <h1>Contáctenos</h1>
      <p>Si tiene alguna duda o requiere de mas información sobre nuestra Startup "TutoHelp", no dude en contactarnos! Atendemos en un periodo máximo de 24 horas</p>
     </div>
     <div class="col-6">
      <form>
        <div class="form-row">
          <div class="form-group col-md-6">
            
            <input type="email" class="form-control" id="inputEmail4" placeholder="Ingrese su email">
          </div>
          <div class="form-group col-md-6">
           
            <input type="text" class="form-control" id="inputPassword4" placeholder="Ingrese su nombre completo">
          </div>
        </div>
        <div class="form-group">
          <input type="text" class="form-control" id="inputAddress" placeholder="Envíe su duda o consulta">
        </div>
        <button type="submit" class="btn btn-primary">Enviar</button>
      </form>
     </div>
   </div>
 </div>
 <!--Términos condiciones-->
 <div>
   <div class="row">
    <div class="col-6">
   <h1>Terminos y Condiciones!</h1>
   <p>Procure no compartir su contraseña con otros usuarios. La aplicación es de uso personal y se procederá a acciones legales en caso de falsificación de información o personificación.</p>
  </div>
  </div>
 </div>


 <!--Final-->
 <div>
   <div class="row final">
     <div class="col-6">
      <p>Su información solo podrá ser visualizada por sus vínculos! Recuerde asegurarse de no aceptar cuentas que puedan ser falsificadas! Su seguridad es lo primero!</p>
     </div>
     <div class="col-6">
       <img src="./images/candado.png" alt="Seguridad">
     </div>
   </div>
 </div>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
</body>
</html>
