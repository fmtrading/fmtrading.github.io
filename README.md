# fmtrading.github.io







<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">


    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, maximum-scale=1.0"
    />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Reservas MI NEGOCIO</title>
    <link rel="stylesheet" href="css/estilos.css" />
	
	
	
<style>
body,h1,h2{font-family: "Raleway", sans-serif}
body, html {height: 100%}
p {line-height: 2}
.bgimg, .bgimg2 {
  min-height: 100%;
  background-position: center;
  background-size: cover;
}
.bgimg {background-image: url("/w3images/wedding_couple.jpg")}
.bgimg2 {background-image: url("/w3images/flowers.jpg")}
</style>
<body>


<!-- Header / Home-->
<header class="w3-display-container w3-wide bgimg w3-grayscale-min" id="home">
  <img src="iconFMTraing.png" class="imgLogo" />
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">FM trading</h1>
    <h2>Sistema financiero</h2>
    <h2><b>10.07.2021</b></h2>
  </div>
</header>

<!-- Navbar (sticky bottom) -->
<div class="w3-bottom w3-hide-small">
  <div class="w3-bar w3-white w3-center w3-padding w3-opacity-min w3-hover-opacity-off">
    <a href="#home" style="width:25%" class="w3-bar-item w3-button">Home</a>
    <a href="#us" style="width:25%" class="w3-bar-item w3-button">Jane & John</a>
    <a href="#wedding" style="width:25%" class="w3-bar-item w3-button">Wedding</a>
    <a href="#rsvp" style="width:25%" class="w3-bar-item w3-button w3-hover-black">RSVP</a>
  </div>
</div>

<!-- About / Jane And John -->
<div id="us">
    <h1 class="w3-center w3-text-grey"><b>Invertir</b></h1>
    <img class="w3-round w3-grayscale-min" src="1.png" style="width:100%;margin:32px 0">
    <br>
 </div>

<!-- Background photo -->
<div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">You Are Invited</h1><br>
    <h2>Of course..</h2>
  </div>
</div>

<!-- Wedding information -->



<div id="us2">
   <img class="w3-round w3-grayscale-min" src="2.jpg" style="width:100%;margin:32px 0">
    <br>
 </div>


<div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">You Are Invited</h1><br>
    <h2>Of course..</h2>
  </div>
</div>


<div id="us3">
   <img class="w3-round w3-grayscale-min" src="3.png" style="width:100%;margin:32px 0">
    <br>
 </div>
 
 
 

<div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">You Are Invited</h1><br>
    <h2>Of course..</h2>
  </div>
</div>


<div id="us3">
   <img class="w3-round w3-grayscale-min" src="4.jpg" style="width:100%;margin:32px 0">
    <br>
 </div>
 
 
 
 <div class="w3-display-container bgimg2">
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">You Are Invited</h1><br>
    <h2>Of course..</h2>
  </div>
</div>
 
 
 
 
 <div id="us3">
   <img class="w3-round w3-grayscale-min" src="5.png" style="width:100%;margin:32px 0">
    <br>
 </div>
 
 


 
 <div class="w3-display-container bgimg2" id="rsvp" >
  <div class="w3-display-middle w3-text-white w3-center">
    <h1 class="w3-jumbo">You Are Invited</h1><br>
    <h2>Of course..</h2>
  </div>
</div>
 

 
   <form action="" class="formulario">
  
      <h3 class="formulario__subtitulo">Reservas</h3>
      <p class="formulario__parrafo">
        Llena este peque??o formulario para agendar tu cita en MI NEGOCIO.
      </p>

      <label for="cliente" class="formulario__label">??Cu??l es tu nombre?</label>
      <input id="cliente" type="text" class="formulario__input" placeholder="Indica cu??l es tu nombre completo" />

      <label for="fecha" class="formulario__label">Indica la fecha de tu reserva</label>
      <input id="fecha" type="text" class="formulario__input" pattern="[0-9]{4}-[0-9]{2}-[0-9]{2}" />

      <label for="hora" class="formulario__label">Indica la hora de tu reserva</label>
      <input id="hora" type="text" class="formulario__input" />

      <label for="empleado" class="formulario__label">EMPLEADO de preferencia</label>
      <select id="empleado" name="listaempleados" class="formulario__input">
        <option>EMPLEADO 1</option>
        <option>EMPLEADO 2</option>
      </select>

      <label for="servicio" class="formulario__label">??Cu??l es el servicio que se desea realizar?</label>
      <select id="servicio" name="listaservicios" class="formulario__input">
        <option>SERVICIO 1 - $VALOR</option>
        <option>SERVICIO 2 - $VALOR</option>
        <option>SERVICIO 3 - $VALOR</option>
        <option>SERVICIO 4 - $VALOR</option>
        <option>SERVICIO 5 - $VALOR</option>
      </select>

      <div id="respuesta"></div>

      <button id="submit" class="formulario__submit">Enviar a WhatsApp</button>
    </form>
    <script src="js/form.js"></script>
	

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
<div class="w3-hide-small" style="margin-bottom:32px">??</div>

</body>
</html>








