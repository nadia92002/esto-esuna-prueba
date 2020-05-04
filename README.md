<html>
<head>
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
<body>
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
</body>
</html>
