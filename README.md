# 2526_ASIX1_0373_AE1llenguatgesdemarquessistem_misapuntes_
Repositorio sobre lo que iremos haciendo a lo largo del año
# ¿Qué es GitHub?
GitHub es una plataforma web que permite **almacenar**, **colaborar** y **versionar** proyectos usando Git.
Para que sirve:
- Para presentar o compartir el trabajo
- Seguir y administrar los cambios del codigo a lo largo del trabajo
- Dejar que otros usuarios revisen tu codigo y realicen sugerencias para mejorarlo 
- Para poder usar los comandos y sincronizarlo con el repositorio en la pagina tenemos que descargar la app **Git**
## ¿Como crear un repositorio en GitHub?
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
- **echo "# BORRAR" >> README.md:**
Creamos el archivo readme.md con el contenido que queramos 
- **git init:**
Inicializamos el repositorio GIT local vacío en la carpeta donde estamos situados.
- **git add README.md:**
Añadimos el archivo readme al repositorio local. Si ponemos git add . añadimos todos los archivos al repositorio local.
- **git branch -M main:**
Asociamos la versión a la rama de desarrollo que queramos. La rama por defecto es “main”
- **git commit -m "first commit":**
Este comando es un conjunto de cambios que se realizan en los archivos del repositorio (modificar, añadir, eliminar, mover, renombrar, etc). Creamos el paquete de archivos a sincronizar con el repositorio remoto.
- **git remote add origin:**
Asociamos un repositorio remoto indicando un identificador (origin) y su URL<br>
- **git push -u origin main:**
Este comando nos permitira hacer los cambios al repositorio remoto y rama indicadas en los puntos anteriores.

**b- Sincronizar un repositorio local ya existente desde linea de comandos**
Navegamos en local hasta la carpeta raiz del repositorio local a vincular con el repositorio vacio creado e inizializado previamente en GitHub
- **git init:** 
Inicializamos el repositorio
- **git remote add origin:** 
Una vez situados en la carpeta añadimos como origen de ese repositorio al repositorio vacio de GitHub
- **git branch -M main:**
Asociamos la version a la rama de desarrollo que queramos 
- **git commit -m "first commit":**
Este comando sirve para hacer cambios que se realizan en los archivos del repositorio. Creamos el paquete de archivos a sincronizar con el repositorio remoto 
- **git push -u origi main:**
Subimos los cambios al repositorio remoto 
## ¿Como importar en GitHub un repositorio ya existente?
**1º Paso** <br>
Vamos al repositorio, le hacemos click en la pestaña verde que se llama **Code** y copiamos la url que nos sale <br>
**2º Paso** <br>
En repositorios vamos a crear un repositorio nuevo y veremos una opcion que nos pondra **importar repositorio**<br>
En **old repository’s clone URL** pegamos la URL del repositorio que queremos importar mientras que en **Repository Name** ponemos el nombre que queremos que tenga nuestro repositorio clonado <br>
**3º Paso** <br>
Por ultimo paso elegimos si queremos que el repositorio sea privado o publico 
## ¿Como activar GitHub Pages?
**1º Paso** <br>
Iremos a nuestro repositorio al apartado configuracion <br>
**2º Paso** <br>
Iremos a la opcion **PAGES** que esta en la parte inferior izquierda <br>
**Recuerda que el repositorio tiene que ser publico para poder hacer esto** <br>
**3º Paso**
Escogemos a que rama asociar pages por defecto a **main** y a que carpeta por defecto **root** y guardamos la configuracion 

# MARKDOWN 
Es un lenguaje de marcado de codigo abierto creado por John Gruber. Contiene texto plano formateado. Este archivo se compone de un nombre y una extension que en este caso la de Markdown es **.md** 
## Etiquetas Negrita, cursiva y texto tachado
- Hay 2 formas de poner en negrita las frases o palabras. Se usa doble * o el doble guion bajo __ <br>
**TEXTO EN NEGRITA** o __TEXTO EN NEGRITA__         <!-- Se usa doble * o el doble guion bajo __ -->
- Hay 2 formas de poner en cursiva las frases o palabras. Se usa un * o un guion bajo _ <br>
*TEXTO EN CURSIVA* o _TEXTO EN CURSIVA_             <!-- Se usa un * o una guion bajo _ -->
- Hay 2 formas de poner en negrita y cursiva las frases o palabras. Se usa triple * o triple guion bajo <br>
***TEXTO EN NEGRITA Y CURSIVA*** o ___TEXTO EN NEGRITA Y CURSIVA___   <!-- Se usa triple * o triple guion bajo ___ -->
- Para poner texto tachado las frases o palabras usaremos este signo ~ <br>
~~TEXTO TACHADO~~
## ENCABEZADOS
Usamos # para crear titulos. Cuantos mas # mas pequeño es el encabezado. <br>
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

## LISTAS
Esta es una lista no ordenada:
 - Elemento 1
 - Elemento 2
 - Elemento 3 
Esta es una lista enumerada
1. Elemento 1
2. Elemento 2
3. Elemento 3
    1. Sub-elemento

## CITAS Y CITAS ANIDADAS
Una cita es para resaltar o citar texto, igual que en los correos o articulos. Se usa este simbolo >
> Esto es una cita en Markdown 

Una cita anidada es una cita que esta dentro de otra por ejemplo
> Esto es una cita
>> Esto es una cita anidada

## BLOQUES DE CODIGO
Para usar bloques de codigo agregaremos las '' comillas por ejemplo si queremos usar html haremos esto
```html
<p>Hola Mundo</p>
```
## IMAGENES
Para poner imagenes en markdown usaremos el siguiente codigo
![imagen de un boxeador](imagenes/naoyainoue.jpg)
![anime](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.imdb.com%2Fes%2Ftitle%2Ftt3514596%2F&psig=AOvVaw0Oh_P3IcxQ5o1Re24fYUVw&ust=1762873719522000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCLCP1cDu55ADFQAAAAAdAAAAABAE)

