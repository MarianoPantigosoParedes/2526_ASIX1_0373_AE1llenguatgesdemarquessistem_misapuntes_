# 2526_ASIX1_0373_AE1llenguatgesdemarquessistem_misapuntes_
Repositorio sobre lo que iremos haciendo a lo largo del año
## ¿Qué es GitHub?
GitHub es una plataforma web que permite **almacenar**, **colaborar** y **versionar** proyectos usando Git.
Para que sirve:
- Para presentar o compartir el trabajo
- Seguir y administrar los cambios del codigo a lo largo del trabajo
- Dejar que otros usuarios revisen tu codigo y realicen sugerencias para mejorarlo 
- Para poder usar los comandos y sincronizarlo con el repositorio en la pagina tenemos que descargar la app **Git**
### ¿Como crear un repositorio en GitHub?
**1º Paso** <br>
Entramos a git hub y ponemos nuestra cuenta <br>
**2º Paso** <br>
Arriba a la derecha veremos un circulo con nuestra foto de perfil le damos click y veremos un apartado de perfil, entramos ahi y se nos abrira una nueva interfas. En la parte de arriba veremos un apartado que se llama repositorio, hacemos click y le damos a **nuevo** <br>
**3º Paso**<br>
A continuacion veremos una interfaz donde nos pedira llenar los datos como el nombre, si queremos que sea privado o publico **(si mas adelante vamos a querer utilizar el github pages lo tenemos que poner en publico tambien lo podremos cambiar mas adelante)** entre otras cosas, lo llenamos depende de como lo pida el profesor. Marcamos la opcion Readme para que el repositorio se cree y se inicialice automaticamente en GitHub <br>
**En caso que no se marque esta opcion el repositorio se creara vacio** <br>
Una vez creada el repositorio local, nos desplazamos a la raíz del repositorio clonado para trabajar con él, realizar modificaciones y sincronizar los cambios con GitHub cada vez que queramos, y para hacer esto implementamos estos comandos
- **git init:** 
Este comando nos servira para inicializar el repositorio de nuestro local con el de la pagina web
- **git add . :**
Este comando servira para agregar los elementos que hemos puesto en la nueva version
- **git commit -m "AÑADIR TITULO":**
Este comando servira para añadir una descripcion de lo que agregamos al repositorio
- **git push origin main:**
Este comando servira para sincronizar los elementos y subirlos tambien a la pagina del git

**a- Crear un repositorio local nuevo desde línea de comandos (GIT).**
Para crear un repositorio local nuevo y sincronizarlo con un repositorio de GitHub no inicializado, osea vacío ya que no se uso la opcion README. Lo que haremos es hacerlo desde la carpeta “raíz” del repositorio local. Iremos en local hasta la carpeta raíz de los repositorios locales y creamos una carpeta nueva para el repositorio local a vincular con el repositorio vacío e inicializado en GitHub. La carpeta se tiene que llamar igual que el repositorio de GitHub. <br>
- **echo "# BORRAR" >> README.md**: Creamos el archivo readme.md con el contenido que queramos 
- **git init**:Inicializamos el repositorio GIT local vacío en la carpeta donde estamos situados.
- **git add README.md**: Añadimos el archivo readme al repositorio local. Si ponemos git add . añadimos todos los archivos al repositorio local.
- **git branch -M main**: Asociamos la versión a la rama de desarrollo que queramos. La rama por defecto es “main”
- **git commit -m "first commit"** : Este comando es un conjunto de cambios que se realizan en los archivos del repositorio (modificar, añadir, eliminar, mover, renombrar, etc). Creamos el paquete de archivos a sincronizar con el repositorio remoto.
- **git remote add origin https://github.com/AlbertoDeSantos/BORRAR.git.:**: asociamos un repositorio remoto indicando un identificador (origin) y su URL
- **git push -u origin main**: Este comando nos permitira hacer los cambios al repositorio remoto y rama indicadas en los puntos anteriores.

