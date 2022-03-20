# opendir-
&lt;?php $dir = "/images/";  // Open a directory, and read its contents if (is_dir($dir)){   if ($dh = opendir($dir)){     while (($file = readdir($dh)) !== false){       echo "filename:" . $file . "&lt;br>";     }     closedir($dh);   } } ?>
