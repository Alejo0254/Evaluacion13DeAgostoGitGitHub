# Evaluacion13DeAgostoGitGitHub
>CD.. : Se utiliza para regresar a la carpeta anterior.
> 
> CD : Se utiliza para cambiar de directorio o para ingresar un archivo de directorio.

# 2
>ls: Se utliza para ingresar a la lista de carpetas y documentos guardados en el pc

> ls -all: elimina los archivos no seguidos en tu directorio de trabajo.

>mkdir: Se utiliza para crear una carpeta.

>touch: se utiliza para crear un documento finalizado en el tipo de documento que se desea guardar.

>pwd: Nos permite saber donde estamos ubicados.

>cat: Muestra el estado del directorio en el que estas trabajando y instancia preparada.

# 3
> Configurar el nombre de usuario
git config --global user.name "Nombre de Usuario"

> Configurar el correo electrónico
git config --global user.email correo@correo.com

# 4 
> git add . : sirve para agragar un archivo a la sala de espera.

>git commit -m "first commit" : lo pasa a un area de confirmacion.

>git push -u origin main:  Permite publicar sus cambios de código local en un repositorio remoto

# 5

> permite a otras personas revisar los cambios que has echo en una rama de un repositorio git una vez ves se abre es posible debatir y ver que cambios se han echo, se pueden añadir comentarios, sugerencias.

>segunda pregunta
> 
El proceso es el mismo para todos ya que primero deberemos crear una rama en nuestro repositorio:

git checkout -b nombre-de-la-rama Tras esto, haremos los cambios que correspondan, tocaremos el código del proyecto y haremos un commit:

git add . git commit -m "feat(subscriptions): enable subscription payment" Hablando de commits, te recomendamos que leas este artículo sobre cómo escribir buenos commits en Git.

Una vez hayamos hecho el commit, simplemente tendremos que hacer un push al origin:

git push -u origin nombre-de-la-rama En este momento ya podremos crear una Pull Request en la plataforma en la que tengamos alojado nuestro código.

Ahora que ya sabemos qué es y cómo crear una Pull Request, vamos a hablar de las buenas prácticas que hay que seguir cuando creamos la Pull Request y asignamos revisores.
