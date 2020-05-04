<html>
<head>
  <style>
  .contenedor{

        text-aling: center;

        background: Aqua; 

        height: 200px;
        
        width: 1000px;
        
        float: left;

      
}

    .contenedor2{

        text-aling: center;
        background: Pink;

        height: 800px;
        
        width: 1000px;
}
</style>
<body>

              <div class="contenedor">

     <img src="https://media1.tenor.com/images/eb5be197a3f3d1d63bc1e0b3b8ef797a/tenor.gif?itemid=15026828" width="100" height="100">
                 </div>
                 <input type="color"/>

  <div class="contenedor2">
<script language="JavaScript">
function CambioTexto(){
var e=document.getElementsByTagName("p");
var x=document.getElementById("valor");
for (var i = 0; i < e.length; i++){
if (x.options[x.selectedIndex].text=="elige"){return false}
e[i].style.fontSize=x.options[x.selectedIndex].text+"px";
e[i].style.fontFamily="Arial";
e[i].style.color="#ff0000";
}
}
</script>


Selecciona un tamaño:
<select id="valor" onchange="CambioTexto()">
<option>elige</option>
<option>10</option>
<option>15</option>
<option>20</option>
<option>25</option>
<option>30</option>
<option>35</option>
<option>40</option>
</select>

<p>Si no lees bien el texto . . .</p>

<div>
<p>HTML es el lenguaje con el que se escribe el contenido de las páginas web. Las páginas web pueden ser vistas por el usuario mediante un tipo de aplicación llamada cliente web o más comúnmente "navegador". Podemos decir por lo tanto que el HTML es el lenguaje usado por para especificar el contenido que los navegadores deben representar a la hora de mostrar una página web.

Este lenguaje nos permite aglutinar textos, imágenes, enlaces... y combinarlos a nuestro gusto. La ventaja del HTML a la hora de representar el contenido en un navegador, con respecto a otros formatos físicos como libros o revistas, es justamente la posibilidad de colocar referencias a otras páginas, por medio de los enlaces hipertexto.Un editor es un programa que nos permiten redactar documentos. Hoy en día existen
un gran número de editores que permiten crear páginas web sin la necesidad de
escribir ni una sola línea de código HTML. Estos editores disponen de un entorno
visual, y generan automáticamente el código de las páginas. Al poder ver en todo
momento cómo quedará la página en el navegador, se facilita la creación de las
páginas, y el uso de menús permite ganar rapidez.
Estos editores visuales pueden generar en ocasiones código basura, es decir, código
que no sirve para nada, en otras ocasiones puede ser más efectivo corregir
directamente el código por lo que resulta necesario saber HTML para poder depurar el
código de nuestra páginas.</p>
</div>
