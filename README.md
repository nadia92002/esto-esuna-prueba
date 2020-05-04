<html>
<head>
<script language="JavaScript">
function CambioTamanio(){
var Boton=window.event.srcElement
var Elementos=document.all.tags("P")
for (i=0;i<Elementos.length;i++){
Elementos[i].style.fontSize=Boton.value
}
}
<!--function MarcaParrafo(){
var Parrafo=window.event.srcElement
Parrafo.style.color="red"
}>
</script>
</head>
<body>
<p>
<!--Tamaño del texto:-->
Si no lees bien el texto, pulsa aquí:
<input type="button" VALUE="10" onClick="CambioTamanio()">
<input type="button" VALUE="15" onClick="CambioTamanio()">
<input type="button" VALUE="20" onClick="CambioTamanio()">
<input type="button" VALUE="25" onClick="CambioTamanio()">
<input type="button" VALUE="30" onClick="CambioTamanio()">
<input type="button" VALUE="35" onClick="CambioTamanio()">
<input type="button" VALUE="40" onClick="CambioTamanio()">
</p>

<div onDblClick="MarcaParrafo()">
<p>TEXTO QUE QUIERAS</p>
</div>
</body>
</html>
