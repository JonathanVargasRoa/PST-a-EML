# PST-a-EML


  Updated 3 minutes ago Se realiza la conversión en la terminal Linux Ubuntu v.2022.1 de los formatos de correo electrónico de la organización Microsoft, los archivos de datos cuya exención es PST, la cual es conformada por calendarios, bandejas de entrada, bandeja de salida etc,...

----

Scrip - desde la Terminal - Console

sudo apt-get update
sudo apt-get install readpst rename zip unzip

mkdir pst-export
readpst -D -M -b -o pst-export archive.pst

ls
cd pst-export/
ls
cd 2021\ -\ jvargasr/
ls


find . -type f ! -iname '*.eml' -exec rename 's/([0-9]+)$/$1.eml/' {} \;

zip -r pst-export.zip pst-export/

cd -r pst-export.zip /mnt/d/

----
Imagenes
 
<p align="center">
<img src= '1.bmp' width='400'/>
  <img src= '2.bmp' width='400'/>
</p align="center"


----
usd80 - Jonathan Vargas Roa
