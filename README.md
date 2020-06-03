<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  
  <style>
    @viewport{
  zoom: 1.0;
  width: extend-to-zoom;
}
@-ms-viewport{
  width: extend-to-zoom;
  zoom: 1.0;
}

.fa:hover {
    opacity: 0.7;
}

.fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin: 5px 20px;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}

.fa-reddit {
  background: #ff5700;
  color: white;
}

body{
  background-color: #333;
  color: snow
}

#welcome-section{
  background-color: #333;
  color: snow;
  padding: 350px;
  font-size: 50px;
	top: 100;
  text-align: center;
}

.projects{
 color: snow;
 font-size: 30px;
 text-align: center;
}

.project-tile{
  color: snow;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(100px, auto);
  grid-gap: 30px;
  width:100%;
  height: 100%;
  float:left;
  padding:50px 15px;
  
}

.tile-1{
  background-color: dimgrey;
  grid-column: 2;
  grid-row: 1;
  text-align: center;
}

.tile-2{
  background-color: dimgrey;
  grid-column: 3;
  grid-row: 1;
  text-align: center;
}

.tile-3{
  background-color: dimgrey;
  grid-column: 2;
  grid-row: 2;
  text-align: center;
}

.tile-4{
  background-color: dimgrey;
  grid-column: 3;
  grid-row: 2;
  text-align: center;
}

.navbar {
  overflow: hidden;
  left: 0px;
  background-color: mediumseagreen;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: +1;
}

.navbar a {
  float: left;
  display: block;
  color: snow;
  text-align: center;
  padding: 10px 16px;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background: snow;
  color: black;
}

.contact {
  overflow: hidden;
  background-color: mediumseagreen;
  width: 100%;
  text-align: center;
  padding: 10px 16px;
}
  </style>
</head>

<body>
  <section id="welcome-section">
	  
	<img src="https://www.freepik.com/free-photo/businessman-with-arms-crossed-smiling_989096.htm#page=1&query=man%20in%20suit&position=1" alt="Picture of Patrick">
     	 
    <h2 style ="left: 650px; top: 200px;">Patrick`s portfolio</h2>
    <p style="left: 775px; font-size: 25px; color: mediumseagreen; top -200px;">Vg2 Datateknologi og elektronikk
    </p>
   </section>

   <div class="navbar">
    <a href="#welcome-section">Home</a>
    <a href="#projects">Skills</a>
    <a href="#profile-link">Contact</a>
   </div>

   <section class="projects" id="projects">
   <h1>My skills</h1>   
      
    <div class="project-tile">
       <section class="tile-1">
        <h1>Git</h1>
        <p>Expert</p>
        <a href="https://git-scm.com/" target="_blank">
        <button>Click here to go to Git</button>
        </a>
       </section>
     
       <section class="tile-2">
          <h1>FreeCodeCamp</h1>
          <p>Newbie</p>
          <a href="https://www.freecodecamp.org/" target="_blank">
        <button>Click here to go to FreeCodeCamp</button>
        </a>
       </section>
     
      <section class="tile-3">
       <h1>The Odin Project</h1>
       <p>Experienced</p>
       <a href="https://www.theodinproject.com/" target="_blank">
         <button>Click here to go to The Odin Project</button>
        </a>
      </section>
     
      <section class="tile-4">
       <h1>Arduino</h1>
       <p>Veteran</p>
       <a href="https://www.arduino.cc/" target="_blank">
        <button>Click here to go to Arduino</button>
       </a>
    </section>
  </div> 
</section>
  
 <div class="contact">
   
   <section id="profile-link"> 
    <a href="https://github.com/Elbil1234" class="fa fa-reddit" target="_blank">
    </a>
     
     <a href="https://nb-no.facebook.com/" class="fa fa-facebook" target="_blank">
     </a>
     
     <a href="https://www.instagram.com/?hl=nb" class="fa fa-instagram" target="_blank">
     </a>
</body>
</html>
