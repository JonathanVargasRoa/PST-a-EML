 <h1> PST-a-EML <h1/>


Se realiza la conversión en la terminal Linux Ubuntu v.2022.1 de los formatos de correo electrónico de la organización Microsoft, los archivos de datos cuya exención es PST, la cual es conformada por calendarios, bandejas de entrada, bandeja de salida etc,... es exportada al formato standar EML.

----
- Console

```
#sudo apt-get update
#sudo apt-get install readpst rename zip unzip

#mkdir pst-export
#readpst -D -M -b -o pst-export archive.pst

#ls
#cd pst-export/
#ls
#cd  -Directorio- 
#ls

#find . -type f ! -iname '*.eml' -exec rename 's/([0-9]+)$/$1.eml/' {} \;

#zip -r pst-export.zip pst-export/

#cd -r pst-export.zip /mnt/d/

```
 RFC
  <img src= '5.webp' width='400'/>
 
----
Imagenes
 
<p align="center">
<img src= '1.bmp' width='400'/>
  <img src= '2.bmp' width='400'/>
  <img src= '3.bmp' width='400'/>
  <img src= '4.bmp' width='400'/>
</p align="center"


----
  
  ![Snake animation](https://github.com/JonathanVargasRoa/JonathanVargasRoa/blob/output/github-contribution-grid-snake.svg)
  
----
  
usd80 - Jonathan Vargas Roa
