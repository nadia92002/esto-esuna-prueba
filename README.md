<!DOCTYPE html>
<html>
<head>
    <title>Formulario</title>
    <meta charset="utf-8">
    <link type="text/css" href="./../css/style.css" rel="stylesheet" />
</head>
 
<body>
    <input type="text" name="texto">
  <input type="submit">
  <img src="https://i0.pngocean.com/files/880/673/235/arrow-computer-icons-symbol-clip-art-send-email-button.jpg" alt="imagen" width="32" height="32" style="vertical-align: middle">
  Enviar
</button>
    <div id="registrar">
            <a href="../index.php"</a>Regresar</a>
    </div>
    <div id="envoltura">
        <div id="contenedor">
 
            <div id="cabecera">
                <img src="./../css/images/logo.gif" >
            </div>
 
            <div id="cuerpo">
 
                <form id="form-login" action="#" method="post" >
                    <p><label for="nombre">Nombre:</label></p>
                        <input name="nombre" type="text" id="nombre" class="nombre" placeholder="Pon tu nombre" autofocus=""/ ></p>
 
                    <!--=============================================================================================-->
                    <!--La sisguientes 2 líneas son para agregar campos al formulario con sus respectivos labels-->
                    <!--Puedes usar tantas como necesites-->
                    <p><label for="apellidos">Apellidos:</label></p>
                        <input name="apellidos" type="text" id="apellidos" class="apellidos" placeholder="Pon tus apellidos" /></p>
                    <!--=============================================================================================-->
 
                    <p><label for="correo">Correo:</label></p>
                        <input name="correo" type="text" id="correo" class="correo" placeholder="Pon tu mail" /></p>
 
                    <p><label for="pass">Password:</label></p>
                        <input name="pass" type="password" id="pass" class="pass" placeholder="Pon tu contraseña"/ ></p>
 
                    <p><label for="repass">Repetir Password:</label></p>
                        <input name="repass" type="password" id="repass" class="repass" placeholder="Repite contraseña" /></p>
 
                    <p id="bot"><input name="submit" type="submit" id="boton" value="Registrar" class="boton"/></p>
                </form>
            </div>
 
            <div id="pie">Sistema de Login Y Registro</div>
        </div><!-- fin contenedor -->
 
    </div>
 
</body>
 
</html>
