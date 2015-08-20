# proyectofrancisco
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"> 
        <title>Ejercicio Conexión</title>
    </head>
    
    <body>
        <?php
        // put your code here
        ?>
        
        <form action="control.php" method="POST">
            Nombres: 
            <input type="text" name="nombres" placeholder="Escriba sus nombres"><br><br>
            Apellidos: 
            <input type="text" name="apellidos" placeholder="Escriba sus apellidos"><br><br>
            Cédula: 
            <input type="number" name="cedula" placeholder="Ingrese su cédula"><br><br>
             Usuario: 
            <input type="text" name="usuario" placeholder="Escriba su usuario"><br><br>
            Contraseña
            <input type="password" name="contrasena" placeholder="Ingrese su contraseña"><br><br>
            <input type="submit" value="Enviar">
            <input type="reset" value="Borrar">
        </form>
    </body>
</html>
