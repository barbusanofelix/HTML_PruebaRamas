Ejercicio Practico
Varios Script para hacer pruebaCrea uno o varios scripts, guárdalos en local en tu equipo, crea un repositorio github y vincúlalo con su directorio de trabajo.

Una vez vinculado, procede a poner en práctica las diferentes acciones que hemos visto en el temario:

modifica un script 
“comit” los cambios para que se suban a github
crea ramas y trabaja en ellas realizando algún cambio en el script
“merge” los cambios a la rama principal
borra ramas creadas.

Cree este repositorio en GitHub.
* En Signo + , esquina superior derecha, elegimos crear Repositorio.

En Visual Studio: Cree una carpeta para el WorkSpace y coloque 4 archivos HTML
* Abrimos el terminal e iniciamos el repositorio local  :  git init
* Pasamos los archivos al staging Area con              :  git add .
* Hacemos un commit de los 4 archivos                   :  git commit -m "V0.0.1"
* Conectamos el repositorio remoto con                  :  git remote add origin https://github.com/barbusanofelix/HTML_PruebaRamas.git
*                                                       :  La URL https://github.com/barbusanofelix/HTML_PruebaRamas.git la copiamos de GitHub.
* Enviamos el repositorio Local al remoto en GitHub     :  git push -u origin master         ( Al ir a GitHub ya vemos el repositorio)
*                                               : 

Creare RamaUno 
git branch RamaUno 

Para subir la RamaUno, por primera vez, hay que usar:
git push -u origin RamaUno
Cuando lo subi en 02_CompraCocheParaHTML.html habia añadido 
<h1>¡Hola, mundo!</h1>
    <p>Este es un ejemplo de cómo incluir JavaScript en HTML.</p>
    <p> La idea era suministrar el dinero y edad</p>
    <p> Aqui cree la RamaUno y añadi esta linea</p>
    <p>Aqui me puse en ramaUno y añadi esta linea</p> 

    Mientras que en Master :
    <h1>¡Hola, mundo!</h1>
    <p>Este es un ejemplo de cómo incluir JavaScript en HTML.</p>
    <p> La idea era suministrar el dinero y edad</p>


Cree RamaDos
git branch RamaDos

 En CompraCocheParaHTML los comentarios sera:
   <h1>¡Hola, mundo!</h1>
    <p>Este es un ejemplo de cómo incluir JavaScript en HTML.</p>
    <p> La idea era suministrar el dinero y edad</p>
    <p> Cree RamaDos y añadi esta linea al master ( con Esta 3 p) </p>


