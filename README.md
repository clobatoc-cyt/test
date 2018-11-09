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