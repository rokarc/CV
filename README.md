# CV


Este link sirve para ver online los archivos html representados graficamente. Renderizado. :P
- http://htmlpreview.github.io


Copiar de GitHub la url del repo, haciendo click en boton **Raw**. y de ahi copio la url, por ejemplo :
- http://htmlpreview.github.io/?https://raw.githubusercontent.com/rokarc/CV/master/CVRox2015.html


1-Para subir archivos desde mi maquina

Para subir archivos desde mi maquina:

Agregar archivo a al directorio del cual voy a hacer cambios.

```
git status 

git add "archivo"

git status

git commit -m "comentario" <archivo>

git status

git push origin master
```

2-En caso de hacer cambios desde la web...

va a pedir sincronizar los cambios con los que tengo en mi maquina...

```
git pull origin master

git push origin master

git status
```


**Resumen Git:**
- Baja desde el repo en internet `git pull origin master`
- Sube hacia el repo en internet `git push origin master`
- Cambios los guarda en commits `git commit -m "mensaje" <archivo>`
- Estados del repo Git en local `git status`
- Comenzar nuevo repo Git vacio `git init`


# Recursos Utiles:
- Fuentes Tipografias: http://www.google.com/fonts
- Patrones en Imagenes: http://subtlepatterns.com/thumbnail-view
- Patrones Degradados CSS: http://bennettfeely.com/gradients
- Patrones Degradados CSS: http://lea.verou.me/css3patterns


3- Cuando creo dir en git web busco el boton clonar que copia la url.

Voy a la consola y posicionada en el dir que voy a sincronizar escribo.
Ojo es git el que va a crear el dir contenedor del nuevo proyecto.

por ejemplo: git clone https://github.com/rokarc/InfoRoxy.git

una vez creado el directorio puedo empezar a trabajar.
