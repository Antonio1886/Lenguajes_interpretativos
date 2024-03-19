a. ¿Cómo se inicializa un repositorio en Git? 
para inicializar un repostorio en una carpeta existente solo tienes que poner en la barra de comandos el "git init" para empezar el repositorio

b. ¿Cómo creas un repositorio en GitHub? 
  Debes de entrar a git Hub con una cuenta ya creada, despues tienes que crear un nuevo documento en "NEW"  tienes que nombrar el nomnbre del proyecto indicar si es privado o publico
  y despues crear el repositorio

c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

    git init  (con esto creas el repositorio)
git add .    (Agregas todos los cambios y modificaciones al respositorio)
git commit -m "Primer commit"  (Guardas los cambios y lo documentas para indicar que estas modficiando o agregando)
git branch -M main  (indicas en que rama lo guardas en caso de que tengas varias ramas)
git remote add origin https://github.com/usuario/repositorio.git   (vinculas el repositorio con el archivo de github)
git push -u origin main  (lo vinculas con el main de github)


d. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
  modified (donde almacenas todos los documetnos en tu computadora, la base del documento)
  staged (es donde registras e indexas todos los cambios previos a subirlos a github )
  committed (donde todos los cambios realizados se suben a la plataforma github )
  remote. (donde guardas todo el proyecto en una plataforma web como lo es github)

e. ¿Para qué sirve el archivo .gitignore?
agregamos todo lo que no deseamos incluir en un repositorio 
f. ¿Cuál es el propósito de una rama?
sirve para poder organizar el trabajo de forma remota
haciendo que todas las modifiaciones se hagan de forma externa a la rama principal en caso de tener algun error ver en que rama esta dicho fallo y poder modifcarlo a la brevedad sin tener que perjudicar todo el proyecto 

g. ¿Qué es una fusión?
 combinas dos ramas antes separadas, haciendo todas las modificaciones de diferentes ramas se combinen en una sola (se hace cuando se sabe que ya no hace falta mover mas cosas de una rama y la incorporas a la principal)

h. Explica los diferentes tipos de fusión que existen.
Fusion rapida: no tiene ningun fallo la fusion de ambas ramas 
fusion manual: se tiene que realizar cuando existan fallos por duplicacion de contenido en las ramas 

i. ¿Cómo puedes ver el historial de tu repositorio?
colocando en la terminal de comandos  "git log" podemos ver todos los cambios, viendo fecha, autor e id de cada uno de los cambios 
para ver los que estan en linea se hace con " git log --oneline" 

de esta manera podemos ver todos los cambios y enfocarnos en cuales son las versiones que nos importa encontrar

j. ¿Cuál es el propósito de una etiqueta?
poder tener un orden e indicar en que version encontramos nuestro proyecto
viendolo en un sitema de 3 numeros "1.0.0" 
el primero es para marcar las versiones que son mas significativas, haciendo que puedan dejar obsoletas versiones anteriores por un cambio de iterfaz, documentos vitales etc.
el seguno hace modificaciones menores, haciendo aun compatible con la versiones anteriores
el ultimo indica cuando haces parches al codigo, como quitar un bug al subir la version anteerior, algun texto que tenga que ser modificado etc.

para agregar una etiqueta se hace con 
git tag
git tag Numero_de_la_version
