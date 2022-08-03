<template>

  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Soy estudiante de Desarrollo de Software e Ingeniería, me estoy
formando como Front End en Prospercity y complementamos
nuestros estudios con los cursos que se encuentran en la
plataforma Platzi. Igualmente tengo conocimientos acerca de la
metodología SCRUM y su aplicación para desarrollar los
diferentes proyectos. <br> 
      <a href="https://github.com/AydaMontoya" target="_blank" rel="noopener">GitHub</a>.
    </p>
    <h4>Poseo un nivel de Ingles B1 y actualmente estudio el nivel B2, soy
Contadora Pública, con 5 años de experiencia en el área.</h4>
    <h3>Datos Personales</h3>
    <ul>
      <li>Cedula: 1058846855</li> <br>
      <li>Fecha de Nacimiento: Abril 27 de 1996</li> <br>
      <li>Lugar de Nacimiento: Pensilvania Caldas</li><br>
      <li>Estado civil: soltera</li><br>
    </ul>
    <h3>Contacto</h3>
    <ul>
      <li>Celular: 3123261708</li> <br>
      <li>correo Electronico: aidamontoya96@gmail.com</li> <br>
      <li>HackerRank: aidamontoya96</li><a href="https://www.hackerrank.com/dashboard" target="_blank" rel="noopener">HackerRank</a>.<br>
    </ul>
    <h3>Areas de Trabajo</h3>
    <ul>
      <li>- Diseño y programación de la interfaz de
usuario de los sitios o aplicaciones web.</li> <br>
      <li>- Traducción del diseño visual de una web a
código HTML, CSS y JavaScript</li> <br>
      <li>- Análisis de información financiera</li><br>  
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  text-align: left;
}
li {
  display: inline-bloÑck;
  margin: 0 10px;
  text-align: left;
}
a {
  color: #e94fdc;
}
</style>
