# INVESTIGACION
## HEADERS
los headers nos sirven para darle estructura a los titulo y subtitulos de nuestro documento.
* \### con este headers nos daria un tamaño de letra como para un complemento de subtitulo:
### ejemplo headers uno
* \## el caso de este nos dara un tamaño presiso para subtitulos:
## ejemplo headers dos
* \# este es el tamaño mas grande el cual se utiliza para los titulos:
# ejemplo headers tres
como podemos observar nos deja una linea la cual delimita el inicio de un titulo, hace un enfasis a la iniciación.

## lists
los lists los utilizamos para darles formato a las listas que utilizemos.
* \* esta por ejemplo es la que estamos utilizando en este momento, como un elemento principal.
* ejemplo lists 1
* con un tab como separador, y un * crearemos un subelemento.
    * ejemplo lists 2

## images 
si tenemos la imagen dentro de nuestro repositorio solo necesitaremos, utilzar 
* \!\[GitHub Logo]\(images/logo.jpg)

![GitHub logo]()
si teemos la imagen en una nube o la necesitamos directo de internet
* Format:\!\[Alt Tex]\(url)

con eso anadiremos la imagen a nuestro documento directamente.

## emphasis
como podemos deducir sirve para darle un *resalte* _resalte_ **resalte** __resalte__ al texto, es solo para añadir, una exaltacion por alguna palabra;
* \*resaltee\*, \_resalte\_, \*\*resalte\*\*, \_\_resalte\_\_. 

## URL
los url no son mas que link de internet, o direcciones electronicas, entonces veamos como referencias una direccion electronica.
* \[nombre\]\(direccion\)

[Google](http://google.com)

## citas
las citas se usan mayormente para referencias las palabras de autores, y asi no cometer plagio.
\> utilizamos este simbolo y escribimos lo citado
por ejemplo como dijo teresa 
>ENTRE SER O NO SER, YO SOY XD

## BACKSLASH ESCAPES 
tomando en cuenta que muchas de los simbolos de teclador generan algun tipo de herramienta en markdown, se implemento una herramienta que le quita la funcion a muchas otras, la cual es la diagonal inversa
* \ 

\\* \ asi se veria un lists si le interponemos un BACKSLASH.

## tablas
las tablas se crean manualmente
* |,- no sirven para ser filas y columnas

* x | y
* --|--
* 3 | 0

x | y
--|--
3 | 0

## bloques de codigo

\`\`\` js 

function test\()\{

 console.log("look, ma', no spaces");

\}

\`\`\`

```js
fuction test(){
    console.log("lock, ma', no spaces");
}
```
recordando que esta herramienta no compila el codigo, solo es una ayuda para dar ejemplos del mismo.

## escrito y dirigido por ANGEL ALEJANDRO RUIZ MAY 