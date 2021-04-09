# **PRIMEROS PASOS CON GIT Y GITHUB**
Se tienen varias formas de trabajar con el controlador de versiones GIT; ya sea por el mismo GitHub, una IDE o por terminal, aqui se vera un poco de todo.
1. **Crear un repositorio en GitHub**
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-15-44.png)
Aqui se puede observar la pestaña de creacion; en dondes se tendra que agregar un titulo al repositorio que sera parte de la direccion, se puede agregar el primer README por defecto o un .gitignore.
# 
2. Se crea un repositorio local
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-19-42.png)
`git init` creara un repositorio local en la carpeta que nosotros estemos

`git status` se puede observar todo lo relacionado al repositorio local

`echo README.md > "Mi projecto` es un comando de la terminal de linux, creara un archivo con titulo "README.md con nombre "Mi projecto"
Con el comando anterior creara un archivo cualquiera, a continuacion se deben agregar al repositorio local, esto se hace de la siguiente manera:
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-21-38.png)
`git add  .` agregara todos los archivos  nuevos que encuentre, tambien se podria haber hecho `git add "Nombre del archivo` para agregar un archivo especifico.
Para hacer un commit: `git commit -am "hola mundo"`
# 
3. **Realizar un primer push **
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-24-09.png)
El comando `git push` carga contenido de un repositorio local a uno remoto
```

git commit -m "first commit"

git remote add origin https://github.com/RepositoryName

git push -u origin master
```
Para poder hacer un push es necesario primero hacer un commit
# 
## Branch
En GitHub tenemos disitntas ramas en las que podemos trabajar, tenemos una rama principal llamada master, luego se pueden crear otras de prueba.
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-38-27.png)
`git branch nombre-nueva-rama` nos creara una nueva rama
`git checkout nombre-rama` nos mandara a la rama que quieramos
Ahora que nos encontramos en la rama nueva, se trabajara un poco en ella:
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-40-59.png)
para poder subir esta rama, es con el mismo comando anterior, solo que en vez de poner master, se agrega  el nombre de la rama nueva `git push -u origin test` en mi caso
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-41-36.png)
En GitHub podemos observar la creacion de la nueva rama
# 
## Pull Request
Pull Request es una peticion de validacion que se mergeara de una rama a otra
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-42-13.png)
Podemos hacerlo con este boton, o ir a la seccion de Pull Request
Luego se continua realizando la accion:
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-42-53.png)
Se puede dejar un comentario para explicar un poco el commit de Pull Request
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-43-31.png)
Esta es la ventana de validacion final, si existieran conflictos en un codigo, se pueden resolver aqui, como se vera mas adelante, si no hay conflictos se puede dejar otro comentario y tocar Merge Pull request.
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2001-01-03.png)
Aqui se pueden observar que nos dice que existen conflictos que se deben resolver antes de mergear
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2001-01-19.png)
y aqui se pueden observar los conflictos que hay que resolver, se resuelven y se puede seguir tranquilamente con el merge
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-43-52.png)
Esto nos indira que se realizo satisfactoriamente la Pull Request y el merge
# 
A partir de ahora se empezara a trabajar con la IDE VS Code para clonar el repositorio creado.
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-48-08.png)
Lo podemos hacer a partir de esta seccion en VS Code 

------------

Nota: tener en cuenta que se debe tener instalado el plugin de GitHub anteriormente, si no lo tiene puede buscarlo en la zona de Extensiones o con el siguiente [link.](https://code.visualstudio.com/docs/editor/githubhttp:// "link.")

------------


- Luego de presionar el boton, si no inicio sesion en github con VS Code seguramente se lo pida,  luego ir a Clone From Github.
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-48-34.png)
Nos saldra una casilla con todos nuestros repositorios existentes.

------------

Ahora para hacer una prueba, tratamos de hacer git push al repositorio local que teniamos anteriormente.
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-51-44.png)
Se puede ver que esta accion ya no es valida, ya que se conecto un nuevo repositorio local con el repositorio remoto.

- A cotnuacion se puede observar los cambios que sufrio el proyecto en la seccion Source Control, (tener en cuenta que previamente se debe guardar el archivo con CTRL+S), aqui veremos los cambios 
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-57-56.png)
y  el signo + en el archivo que sufrio los cambios se lo agrega al repositorio remoto.
![](https://github.com/galiasmu/LAB-4/blob/master/Pictures/Screenshot%20from%202021-04-09%2000-56-08.png)

Tener en cuenta que cualquiera de los pasos realizados se pueden hacer de cualquiera de las tres formas mostradas (IDE, GITHUB  o una terminal), tambien se podria haber descargado git bash, la terminal del controlador de versiones git.
