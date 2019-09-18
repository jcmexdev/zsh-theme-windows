# Guía para cambiar el tema de zsh en Windows 

1. Abre la consola de Linux (Ubuntu en este caso) y ubícate en home con el comando **cd ~**
![Open linux terminal](https://raw.githubusercontent.com/jcmexdev/zsh-theme-windows/master/img/opening-linux-terminal.PNG)

1. Ubica el archivo .zshrc (este archivo contiene la configuración del tema), para esto ejecuta el comando **ls -la** y se te mostrara una lista como la siguiente, donde se observa el archivo que buscamos en la parte inferior resaltado en rojo.
![Find zshrc file](https://raw.githubusercontent.com/jcmexdev/zsh-theme-windows/master/img/find-zshrc-file.PNG)


1. Modificamos el archivo con el comando **nano  .zshrc**
![Find zshrc file](https://raw.githubusercontent.com/jcmexdev/zsh-theme-windows/master/img/edit-zshrc-file.PNG)

Ejecutamos el comando y nos muestra el editor de archivos, solo hay que cambiar el valor **"robbyrussell”** de la clave **ZSH_THEME** por alguno que te guste de la lista disponible en el siguiente enlace:  [Temas para zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes "Temas para zsh")

En este caso yo lo voy a cambiar por el tema **“af-magic”** entonces queda así:
![Edited zshrc file](https://raw.githubusercontent.com/jcmexdev/zsh-theme-windows/master/img/edited-zshrc-file.PNG)


Después de cambiar el nombre del tema presionamos **control + x **y nos preguntara si queremos guardar los cambios, colocamos la letra **Y**, enseguida nos preguntara el nombre del archivo y por defecto nos coloca el nombre por defecto **.zshrc** solo presionamos la tecla de enter y listo.
	
Con lo siguiente ya solo necesitamos un comando mas y es **source .zshrc** para recargar la configuración, nuestra terminal ya tendrá el nuevo tema:
![Edited zshrc file](https://raw.githubusercontent.com/jcmexdev/zsh-theme-windows/master/img/new-theme.PNG)
	
**nota: si la terminal de hyper no se actualiza simplemente ciérrala y ábrela de nuevo y listo quedara de esta manera:**
![Edited zshrc file](https://raw.githubusercontent.com/jcmexdev/zsh-theme-windows/master/img/hyper-terminal.PNG)

**Espero que esta guía les sea de utilidad, me ayudarian mucho con 1 estrelita :) saludos y suerte.**
