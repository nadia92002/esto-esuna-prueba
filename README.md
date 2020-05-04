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

               <center><h1><font color="blue">Page editor</h1></center>

                 <img src="https://media1.tenor.com/images/eb5be197a3f3d1d63bc1e0b3b8ef797a/tenor.gif?itemid=15026828" width="100" height="100">
                 </div>
                 
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
</head>

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
<p>TEXTO QUE QUIERAS</p>
</div>
</div>
</body>
</html>
