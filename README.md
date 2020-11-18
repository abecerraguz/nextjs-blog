# HACIENDO UN SUB MODULO

## Dentro de la carpeta donde se desea hacer el sub módulo

Recuerda el sub módulo debe estar versionado y también el proyecto que lo contiene.

~~~html
 git submodule add https://github.com/abecerraguz/components.git
~~~

## Clonando un proyecto con submódulos

Para clonar un proyecto con submódulos se introduce el siguiente comando

~~~html
 git clone git@github.com:abecerraguz/nextjs-blog.git
~~~

Tenemos que tener en cuenta que esto solo trae los directorios sin los ficheros. Para poder recuperar los ficheros y actualizarlos, debemos hacer lo siguiente:

Para recuperar los ficheros:

~~~html
 git submodule init
~~~

Para actualizarlos:

~~~html
 git submodule update
~~~

También podemos ahorrarnos las dos últimas líneas con --recursive:

~~~html
 git clone --recursive git@github.com:abecerraguz/nextjs-blog.git
~~~

Para actualizar el Submodulo
~~~html
 git submodule update --remote
~~~


