# Git

## ¿Qué es Git?

Git es un sistema de control de versiones, es el conjunto de herramientas que tenemos disponibles para poder gestionar de una forma eficiente las distintas versiones de nuestros proyectos.

Sigamos estos pasos para tener git instalado y funcionando en Windows

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F1.jpg?alt=media&token=c399d7ec-73e5-446b-a724-012a7d0c2e4d)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F1.jpg?alt=media&token=c399d7ec-73e5-446b-a724-012a7d0c2e4d)

Ve a https://git-scm.com/ y descarga el paquete de instalación

Ahora debes elegir la opción según la arquitectura de tu computadora (32bit o 64bit)

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F3.PNG?alt=media&token=c36591b6-4c77-47e7-868b-2e80cfd356fc)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F3.PNG?alt=media&token=c36591b6-4c77-47e7-868b-2e80cfd356fc)

Ahora debes ejecutar el archivo descargado y verás una pantalla como esta

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F4.PNG?alt=media&token=5204f0a1-e1c7-4a8e-9d84-87e8b7917719)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F4.PNG?alt=media&token=5204f0a1-e1c7-4a8e-9d84-87e8b7917719)

Ahora elige la carpeta donde ubicaras los archivos de git

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F5.PNG?alt=media&token=fb3ab0d0-ad64-4236-83b3-0c8dc108ba78)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F5.PNG?alt=media&token=fb3ab0d0-ad64-4236-83b3-0c8dc108ba78)

Asegúrate de tener seleccionado git bash que es la herramienta principal con la que trabajaremos y con esto se terminará la instalación

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F6.PNG?alt=media&token=1fac830a-2077-4480-9a5e-c91cb8e6bfe2)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F6.PNG?alt=media&token=1fac830a-2077-4480-9a5e-c91cb8e6bfe2)

Asegúrate de tener visual studio code por default

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F7.PNG?alt=media&token=5a46c202-5cf5-4aaa-ae2f-96b37701d567)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F7.PNG?alt=media&token=5a46c202-5cf5-4aaa-ae2f-96b37701d567)

Asegúrate de tener "Use windows default console windows"

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F8.PNG?alt=media&token=027ddfd8-31d3-4ee0-acbb-4e23c36bdde3)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F8.PNG?alt=media&token=027ddfd8-31d3-4ee0-acbb-4e23c36bdde3)

## ¿Qué es GitHub?

GitHub es un servicio de alojamiento que ofrece a los desarrolladores repositorios de software usando el sistema de control de versiones, Git.

Existen varios aspectos que hacen que GitHub sea una opción eficiente para el control y gestión de tus proyectos.

Estos son algunos de ellos:

GitHub permite que alojemos proyectos en repositorios de forma gratuita.
Los repositorios son públicos, sin embargo Github tiene una forma de pago que te permite alojar tus proyectos de forma privada.
Permite que puedas compartir tus proyectos de una forma mucho más fácil.
Te permite colaborar para mejorar los proyectos de otros y a otros mejorar o aportar a los tuyos.
Ayuda reducir significativamente los errores humanos, a tener un mejor mantenimiento de distintos entornos y a detectar fallos de una forma más rápida y eficiente.
Es la opción perfecta para poder trabajar en equipo en un mismo proyecto.
Ofrece todas las ventajas del sistema de control de versiones, Git, pero también tiene otras herramientas que ayudan a tener un mejor control de nuestros proyectos.

## Los beneficios de usar Git

- Velocidad.
- Diseño sencillo.
- Fuerte apoyo en el desarrollo no lineal.
- Completamente distribuido.
- Capaz de manejar grandes proyectos.

Además con Git puedes trabajar offline y te crea códigos hexadecimales para hacer referencias

## Los tres estados de Git

- Working Directory
- Staging Area. Esta es una área de preparación.
- Git Directory (repository)
  Estos tres estados representan el ciclo de vida de nuestros archivos dentro de la plataforma.

[![N|Solid](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F2.PNG?alt=media&token=404e04b4-5479-4303-af91-786a03364edd)](https://firebasestorage.googleapis.com/v0/b/andresnaranjo-marcapersonal.appspot.com/o/git%2F2.PNG?alt=media&token=404e04b4-5479-4303-af91-786a03364edd)

## Comandos útiles de la terminal

```sh
- cd = que nos permite movernos dentro de carpetas.
- cd … = podemos salir de las carpetas.
- mkdir = Para crear carpetas vamos a usar mkdir y ponemos el nombre de la carpeta que vamos a crear.
- ls = Con el comando ls vamos a ver las carpetas que tenemos creadas.
- clear = Para limpiar la terminal vamos a usar el comando clear. Este nos sirve para hacer scroll e ir al principio de la terminal.
- touch = El comando touch nos permite crear archivos.
- rm = Para borrar archivos vamos a usar el comando rm y el nombre del archivo.
- rm -rf = De la misma forma para borrar carpetas usamos rm -rf y el nombre de la carpeta.
```

## Configurar nuestro usuario

- git config --global user.name "Andrés Felipe Naranjo Quintero"
- git config --global user.email "afnarqui@hotmail.com"

## Comandos útiles de git

```sh
- git init = Para crear nuestro primer repositorio vamos a crear el comando git init y el nombre de nuestro repositorio.
- git status = Para saber el estado de mis archivos.
- git add = Para agregarlos al working staging vamos a usar el comando add lo cual podemos verificar usando de nuevo el git status.
- git rm --cached = Para sacar el archivo de git vamos a usar el comando git rm --cached y el nombre del archivo.
- git commit = para confirmar los archivos
- git commit -m = se le da un mensaje al commit
- git log = nos permite visualizar los commit enviados
- git log --oneline --graph = nos permite a nivel visual ver las ramas
- git tag -m = nos permite etiquetar las versiones
- git tag -l = nos permite ver las etiquetas
- git tag -d nombre del taga = para borrar la etiqueta
- git tag -f -a  nombre tag  -m "mensaje nuevo"  id
- git config --global alias.superlog "log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
- git config --global --unset alias.superlog
- git remote add origin https://github.com/afnarqui/git.git
- git push -u origin master
```

repositorio en Github. [public repository][afn]

[afn]: https://github.com/afnarqui/git
