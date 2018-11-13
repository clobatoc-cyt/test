# TEST GIT:
* Tested commands:
  * __*git config --list*__: Lista la configuración de git
  * *git config --global \<info variable of git\> "\<value\>"*: Asigna información
  a la variable interna de git, la información asignada va en el campo \<value>
  * __*git status*__: Lista el estado de los fichero modificados del repositorio y 
  que no han recibido un commit, si están modificados y no preparados para el 
  commit en rojo (no se encuentran en estado staged); si están modificado y 
  preparados para el commit en verde (en estado staged)
  * __*git add \<nombre del archivo\>*__: Prepara para el comit el archivo con nombre
  \<nombre del archivo\> que previamente se modificó (modificación de archivo o 
  directorio).
  * __*git add --all*__: Prepara para el commit todos los archivos que previamente
  se modificaron (modificación o añadido de archivos y direcctorios)
  * __*git commit -n "\<commit message\>"*__
  * __*git log*__
  * __*git log -v -p*__
  * __*git log --pretty=format:"%h %s" --graph*__: Muestra el log en modo
  gráfico, con el commit hash abrebiado y con el tema (subject) del commit
    * __*\<format\> options*__:
      * __*%H o %h*__: El commit hash completo o abrebiado.
      * __*%T o %t*__: Hash del arbol completo o abrebiado.
      * __*%P o %p*__: Hash de las confirmaciones padre completo o abrebiado.
      * __*%a\<opcion\>*__: Datos del autor  de la modificación según opción.
        * __*n*__: Nombre del autor.
        * __*e*__: Dirección de correo.
        * __*d*__: Fecha de autoría \(respeta formato --date\)
        * __*r*__: Tiempo desde la modificación del autor.
      * __*c\<opcion\>*__: Datos del que realiza el commit.
        * __*n*__: Nombre del confirmador.
        * __*e*__: Dirección de correo confirmador
        * __*r*__: Fecha de realización del comit
      * __*s*__: Asunto del commit.
  * __*git checkout -- \<archivo\>*__: Descarta los cambios realizados en 
  \<archivo\> en el directorio de trabajo \(es decir, están esos cambios sin
  entrar preparados para el commit \(no en staged\)\)
  * __*git commit --ammend*__: Modificar texto del commit si no está subido al 
  repositorio remoto
  * __*git*__: