Título y descripción: Ejemplo e proyecto colaborativo
Instalación: clonar le repositorio
Uso: 
     Usuario A
     git clone
     git add app.js
     git commit -m "Fix: cambio realizado"
     git push

     Usuario B
     git clone
     git add app.js
     git commit -m "Fix: cambio tardio NO realizado"
#Error al registrar cambio     
     git push
# Traer la modificación
     git pull
#  Se produce un archivo combinado
#  Editar el archivo y resolver el conflito
     git app.js
     git commit -m "Fix: Registrar versión final"
     git push
