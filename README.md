!DOCTYPE html>
<html>
<head>
	<title>Numero Mayor de un arreglo</title>

<script type="text/javascript">
var arreglo  = [5,10,25,58,12];
    maximo = 0;

for(var i=0,len=arreglo .length;i<len;i++){
    if(maximo < arreglo [i]){
        maximo = arreglo [i];
    }
}
document.write(maximo);
</script>
</head>
<body>

</body>
</html>

