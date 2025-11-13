# 2526_ASIX1_0373_AE1llenguatgesdemarquessistem_misapuntes_
Repositorio sobre lo que iremos haciendo a lo largo del año
# ¿Qué es GitHub?
GitHub es una plataforma web que permite **almacenar**, **colaborar** y **versionar** proyectos usando Git.
Para que sirve:
- Para presentar o compartir el trabajo
- Seguir y administrar los cambios del codigo a lo largo del trabajo
- Dejar que otros usuarios revisen tu codigo y realicen sugerencias para mejorarlo 
- Para poder usar los comandos y sincronizarlo con el repositorio en la pagina tenemos que descargar la app **Git**

<img src="imagenes/git.jpg" alt="Logo git" width="300">

## ¿Como crear un repositorio en GitHub?
**1º Paso** 
Entramos a git hub y ponemos nuestra cuenta 

**2º Paso** <br>
Arriba a la derecha veremos un circulo con nuestra foto de perfil le damos click y veremos un apartado de perfil

![pasouno](imagenes/paso1.png)

**3º Paso**<br>
Entramos ahi y se nos abrira una nueva interfas. En la parte de arriba veremos un apartado que se llama repositorio

 ![pasodos](imagenes/paso2.png)

 **4º Paso**<br>
 Hacemos click y le damos a **nuevo** 

 ![pasotres](imagenes/paso3.png)<br>

**5º Paso**<br>
A continuacion veremos una interfaz donde nos pedira llenar los datos como el nombre, si queremos que sea privado o publico **(si mas adelante vamos a querer utilizar el github pages lo tenemos que poner en publico tambien lo podremos cambiar mas adelante)** entre otras cosas, lo llenamos depende de como lo pida el profesor. Marcamos la opcion Readme para que el repositorio se cree y se inicialice automaticamente en GitHub <br>
**En caso que no se marque esta opcion el repositorio se creara vacio** <br>

![pasocuatro](imagenes/paso4.png)

**6º Paso**<br>
Una vez creada el repositorio local, nos desplazamos a la raíz del repositorio clonado para trabajar con él, realizar modificaciones y sincronizar los cambios con GitHub cada vez que queramos, y para hacer esto implementamos estos comandos

- **git init:** 
Este comando nos servira para inicializar el repositorio de nuestro local con el de la pagina web

![gitinit](imagenes/gitinit.png)

- **git add . :**
Este comando servira para agregar los elementos que hemos puesto en la nueva version

![gitadd](imagenes/gitadd.png)

- **git commit -m "AÑADIR TITULO":**
Este comando servira para añadir una descripcion de lo que agregamos al repositorio

![gitcommit](imagenes/gitcommit.png)

- **git push origin main:**
Este comando servira para sincronizar los elementos y subirlos tambien a la pagina del git

![gitpush](imagenes/gitpush.png)

## A- Crear un repositorio local nuevo desde línea de comandos (GIT).
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

## B- Sincronizar un repositorio local ya existente desde linea de comandos
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
**1º Paso**<br>
Vamos al repositorio, le hacemos click en la pestaña verde que se llama **Code** y copiamos la url que nos sale 

![importarrepositorio](imagenes/importar.png)

**2º Paso**<br>
En repositorios vamos a crear un repositorio nuevo

![importarrepositorio](imagenes/importar2.png)

Veremos una opcion que nos pondra **importar repositorio**

![importarepositorio](imagenes/importar3.png)

En **old repository’s clone URL** pegamos la URL del repositorio que queremos importar mientras que en **Repository Name** ponemos el nombre que queremos que tenga nuestro repositorio clonado

![importarrepositorio](imagenes/importar4.png)

**3º Paso** <br>
Por ultimo paso elegimos si queremos que el repositorio sea privado o publico 
## ¿Como activar GitHub Pages?
**1º Paso** <br>
Iremos a nuestro repositorio al apartado configuracion 

![githubpages](imagenes/pages.png) 

**2º Paso** <br>
Iremos a la opcion **PAGES** que esta en la parte inferior izquierda <br>
**Recuerda que el repositorio tiene que ser publico para poder hacer esto** <br>
![githubpages](imagenes/pages2.png) 

**3º Paso** <br>
Escogemos a que rama asociar pages por defecto a **main** y a que carpeta por defecto **root** y guardamos la configuracion 

![githubpages](imagenes/pages3.png)

# MARKDOWN 
Es un lenguaje de marcado de codigo abierto creado por John Gruber. Contiene texto plano formateado. Este archivo se compone de un nombre y una extension que en este caso la de Markdown es **.md** 
## Etiquetas Negrita, cursiva y texto tachado
- Hay 2 formas de poner en negrita las frases o palabras. Se usa doble * o el doble guion bajo __ <br>
**TEXTO EN NEGRITA** o __TEXTO EN NEGRITA__         <!-- Se usa doble * o el doble guion bajo __ -->

Esta seria la sintaxis:

![negrita](imagenes/negrita.png)

- Hay 2 formas de poner en cursiva las frases o palabras. Se usa un * o un guion bajo _ <br>
*TEXTO EN CURSIVA* o _TEXTO EN CURSIVA_             <!-- Se usa un * o una guion bajo _ -->

Esta seria la sintaxis:

![cursiva](imagenes/cursiva.png)

- Hay 2 formas de poner en negrita y cursiva las frases o palabras. Se usa triple * o triple guion bajo <br>
***TEXTO EN NEGRITA Y CURSIVA*** o ___TEXTO EN NEGRITA Y CURSIVA___   <!-- Se usa triple * o triple guion bajo ___ -->

Esta seria la sintaxis:

![negritacursiva](imagenes/negritacursiva.png)

- Para poner texto tachado las frases o palabras usaremos este signo ~ <br>
~~TEXTO TACHADO~~                   <!-- se usa ~~ al inicio y final-->

Esta seria la sintaxis:

![tachado](imagenes/tachado.png)

## ENCABEZADOS
Usamos # para crear titulos. Cuantos mas # mas pequeño es el encabezado. Esta es la sintaxis:

![encabezado](imagenes/encabezados.png)

Y se veria asi en la pagina:

# Encabezado 1              <!--En este caso puse encabezado como ejemplo, pero ahi iria el titulo de tu documento -->
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

## LISTAS
Esta es la sintaxis de una lista no ordenada:

![listadesordenada](imagenes/listadesordenada.png)

Y se veria asi en la pagina:
 - Elemento 1                   
 - Elemento 2          <!-- elementos vendria a ser el ejemplo aqui ustedes pueden poner cualquier cosa sin importar el orden ya que  es desordenada-->
 - Elemento 3 

Esta es la sintaxis de una lista enumerada:

![listaordenada](imagenes/listaordenada.png)

Y asi se veria en la pagina:
1. Elemento 1
2. Elemento 2           <!-- elementos vendria a ser el ejemplo aqui ustedes pueden poner cualquier cosa, aqui el orden si importaria-->
3. Elemento 3
    1. Sub-elemento

## CITAS Y CITAS ANIDADAS
<!--Citas-->
Una cita es para resaltar o citar texto, igual que en los correos o articulos. Se usa este simbolo >
Esta es la sintaxis:

![cita](imagenes/cita.png)

Y se veria asi en la pagina:
> Esto es una cita en Markdown 
<!--Citas anidadas-->
Una cita anidada es una cita que esta dentro de otra
Esta es la sintaxis:

![citasanidadas](imagenes/citasanidadas.png)

Y asi se veria en la pagina:
> Esto es una cita
>> Esto es una cita anidada

## BLOQUES DE CODIGO
Para usar bloques de codigo agregaremos las ´´´ comillas por ejemplo si queremos usar html o cualquier otro lenguaje de programacion

Esta es la sintaxis:

![bloquescodigo](imagenes/bloques.png)

Y asi se veria en la pagina:

```html
<p>Hola Mundo</p>
```

## IMAGENES
- Para poner imagenes en markdown desde nuestra pc local, osea descargada usaremos el siguiente codigo, no olviden de poner bien la ruta:
La sintaxis seria la siguiente:

![*TEXTO*](**RUTA DE LA IMAGEN**)

![imagen](imagenes/imagen.png)

Y asi se veria en la pagina:

![imagen de un boxeador](imagenes/naoyainoue.jpg)

- Para poner imagenes en markdown desde una pagina web pondremos el siguiente codigo, recuerda que debe de estar en formato **PNG, JPEG, JPG**:
La sintaxis seria la siguiente:

![*TEXTO*](**RUTA DE LA IMAGEN**)

![imagen2](imagenes/imagen2.png)

Y asi se veria en la pagina:

![anime](https://m.media-amazon.com/images/M/MV5BOWE2OTJkNzAtZWU1NC00YmQyLTk5ZWMtNzQ4MjQyZTI5YjhlXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg)

## ENLACES
Primero se incluye el texto del link entre corchetes y posteriormente el link entre parentesis

La sintaxis seria la siguiente:

![enlaces](imagenes/enlaces.png)

Y en la pagina se veria asi

[Pagina web del record actual de cada boxeador](https://boxrec.com/es)

## TABLAS 
Se usan barras verticales | para separar columnas y guiones - para crear el encabezado.

La sintaxis seria la siguiente:

![tabla](imagenes/tabla.png)

Y en la pagina se veria asi:

| NOMBRE | EDAD | PAIS |
| ----------- | ---- | ------------- |
| Mariano | 20 | Perú |
| David | 20 | Colombia |
| Carlos | 20 | Uruguay |
| Adrian | 21 | Paraguay |

## HTML
¿Que es HTML?

LENGUAJE DE MARCAS HTML (1991)

Sirve para estructurar contenidos en páginas web, lo q hace es definir enlaces entre diferentes documentos que están entrelazados entre sí. No se dedica para poder interactuar con el contenido solo estructura. 
Cada etiqueta de html empiezan con un menor que y acaban con un menor que y en el medio el nombre de la etiqueta 

![etiqueta](imagenes/etiqueta.png)

<etiqueta>

**Hipertext**: Es el texto que que se enlaza con otros contenidos. Esto es la base del funcionamiento de la web tal y como la conocemos, que no es mas que paginas y recursos interconectados.

**markup**: Todas las paginas estan construidas por etiquetas

**Lenguaje**: Formado por etiquetas que generan hipertextos
Todas las etiquetas tienen etiquetas de inicio y algunas no tienen de cierre; inicio: '<p>' y cierre '</p>'

**Atributo**: Están dentro siempre de las etiquetas de apertura nunca los de cierre, por ejemplo:

Aqui class es el nombre del atributo y editor-note es el valor del atributo, en este caso, el atributo class permite darle al elemento un nombre identificativo, que se pueda utilizar luego para apuntarle al elemento informacion de estilo y demas cosas.

La sintaxis seria la siguiente:

![atributo](imagenes/atributo.png)

Y en la pagina web se veria asi:

<p class=”editor-note”>Mi gato es muy gruñón</p>

## ESTRUCTURA DE HTML

Esta es la estructura de html a continuacion les ire diciendo que es cada etiqueta que hay dentro y su funcion.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estructura de HTML</title>
    <link rel="icon" href="multimedia/kiwi.svg">
</head>
<body>

</body>
</html>

```

 < !DOCTYPE html > : 
 
 Indica que el documento está escrito en HTML5. Esto ayuda al navegador a interpretarlo correctamente.

 ![docttype](imagenes/doctype.png)

 < html lang="es" > : 

 Es la etiqueta raíz de todo el documento. El atributo lang="es" indica el idioma (en este caso, español).

![lang](imagenes/lang.png)

< head > : 

Contiene información interna o metadatos del sitio que no se muestran directamente en la página.

![head](imagenes/head.png)

< /head > : 

Cierra la sección del encabezado.

![cierrehead](imagenes/cierrehead.png)

< meta charset="UTF-8" > : 

Define el tipo de codificación de caracteres (UTF-8 permite usar tildes, ñ, etc.).

![metacharset](imagenes/metacharset.png)

< meta name="viewport" content="width=device-width, initial-scale=1.0" > : 

Hace que la página se vea bien en dispositivos móviles.

![meta](imagenes/meta.png)

< title > : 

Título que aparece en la pestaña del navegador.

![title](imagenes/title.png)

< p > : 

Es un párrafo de texto.

![p](imagenes/p.png)

< body > : 

Aquí va todo el contenido visible de la página: texto, imágenes, enlaces, botones, etc.

![body](imagenes/body.png)

< /body > : 

Cierra el cuerpo del documento.

![cierrebody](imagenes/cierrebody.png)

< /html > : 

Cierra el documento HTML.

![cierrehtml](imagenes/cierrehtml.png)


## ELEMENTOS DE BLOQUE HTML

- **Encabezados y titulos**

Los titulos y encabezados van desde el < h1 > hasta el < h6 >, y se veria tal que asi en nuestra pagina web:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estructura de HTML</title>
    <link rel="icon" href="multimedia/kiwi.svg">
</head>
<body>
     <h1> TITULO PRINCIPAL</h1>
    <h2> SUBTITULOS </h2>
    <h3> SUB-SUBTITULO </h3>
    <h4> ENCABEZADO 4 </h4>
    <h5> ENCABEZADO 5 </h5>
    <h6> ENCABEZADO 6 </h6>
</body>
</html>

El codigo que usaremos sera el siguiente: 

![encabezadohtml](imagenes/encabezadohtml.png)

- **Salto de linea**
Para hacer un salto de linea en html usaremos el < br >

A continuacion les pondre un ejemplo de como se veria
<p>Hola me llamo Mariano</p> <br>
<p>Hola me llamo Johan</p>

El codigo que implementamos fue el siguiente: 

![saltodelinea](imagenes/saltodelinea.png)

- **Separador**
Para incluir un separador en html usaremos el < hr >. Esto sirve para separar secciones de contenido dentro de una página web con una línea horizontal.

A continuacion les pondre un ejemplo de como se veria

<h2>Separador</h2><hr>
<p>Esto es un separador</p>

El codigo que implementamos fue el siguiente:

![separador](imagenes/separador.png)

## ELEMENTOS DE LINEA

- **Enfasis o cursiva**
Para usar enfasis o cursiva usaremos el < em >

A continuacion les pondre un ejemplo de como se veria en la pagina y el codigo implementado

![cursivahtml](imagenes/cursivahtml.png)

<em>Hola soy Mariano</em>

- **Negrita**
Para poner en negrita un texto usaremos el < strong >, tambien se podria usar el < br > pero es muy antiguo y habria navegadores que tendrian problema en reconocerlo

A continuacion les pondre un ejemplo de como se veria en la pagina y el codigo implementado

![negritahtml](imagenes/negritahtml.png)

<br>Me gusta el chocolate</br>
<strong>Me gusta el chocolate</strong>

## RESUMEN DE NORMAS BASICAS DE HTML
- Las etiquetas de html normalmente vienen en pares, con una etiqueta de cierre y otra de apertura
- Algunas etiquetas son vacias osea que no tienen etiqueta de cierre como por ejemplo: < img >, < br >, y < input >
- Las etiquetas siempre deben anidarse correctamente para que funcionen 
- Las atributos de las etiquetas se esepcifican en la etiqueta de apertura y su formato es **nombre=="valor"**
- Aunque las etiquetas y atributos funcionen con mayusculas o minusculas, la recomendacion es que todo se escriba en minuscula

## COMENTARIOS
En un documento html podemos poner anotaciones que no se veran en la pagina web, pero son muy utiles para el desarrollador web, ya que hay que pensar que no siempre trabajaremos solos y es muy importante comentar el codigo fuente sobre todo si se trata de un documento muy largo

La estrucutra de un comentario es la siguiente
<!-- Esto es un comentario en HTML -->

![comentariohtml](imagenes/comentariohtml.png)

Y en un documento se veria asi

![comentariohtml2](imagenes/comentariohtml2.png)

## LISTAS
- **Listas ordenadas**

Son aquellas en las que el orden de los elementos si importan. Estan dentro del elemento < ol > que significa **orden list** y dentro de ahi van las < li > que significa **list item**. Aqui al abrir la etiqueta dentro de ahi podemos escribir **type=""** y dentro de las comillas poner A, a, l, 1 para que coja diferentes estilos la lista.

A continuacion les pondre un ejemplo de como se veria en la pagina y el codigo implementado

![ordenlist](imagenes/ordenlist.png)

<ol>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Naranja</li>
</ol>

Tambien podemos añadir parametro como **start=n** que se fuerza la numeracion a partir de un determinado valor, añadiendo el parametro **value=n** se fuerza a que el elemento tenga el numero de orden que indiquemos 

- **Listas desordenadas**

Son aquellas en las que el orden de los elementos no importan. Estan dentro del elemento < ul > que significa **unordered list** y dentro de ahi van las < li > que significa **list item**. Aqui al abrir la etiqueta dentro de ahi podemos escribir **type=""** y dentro de las comillas poner DISC, SQUARE y CIRCLE, para que coja diferentes estilos la lista

A continuacion les pondre un ejemplo de como se veria en la pagina y el codigo implementado

![ul](imagenes/ul.png)

<ul>
    <li>Platano</li>
    <li>Kiwi</li>
</ul>

## RUTAS
- **Ruta relativa**: Especifica la ubicacion del archivo en relacion con la ubicacion del documento actual

A continuacion les pondre un ejemplo de como se veria en la pagina y el codigo implementado

En este ejemplo pondremos una imagen en el indice

![rutarelativa](imagenes/rutarelativa.png)

El codigo implementado sera el siguiente

![ejemplo](imagenes/ejemplorutarelativa.png)

**alt** es el texto que saldria si en caso no carga la imagen, tambien podemos ajustar las medidas de las imagenes con **width** y **height**

- **Ruta absoluta**: Especifica la ubicacion del archivo en la web, comenzando desde el dominio. Es util cuando el archivo se encuentra en un servidor diferente o en una ubicacion especifica de la web. Aqui no hace falta tener la imagen descargada. Pondrias el mismo codigo que en el de la ruta relativa y solo cambiariamos el src que esta vez seria la url de la imagen

## IMAGENES 
Son un recurso importante para las paginas webs ya que las hacen mas llamativas y nos permite proporcionar informacion de manera visual. La etiqueta que usaremos sera **< img >**, usaremos el atributo **< src >** para poner la ubicacion de la imagen. Tambien usaremos **alt** que es el texto que saldria si en caso no carga la imagen, tambien podemos ajustar las medidas de las imagenes con **width** y **height**