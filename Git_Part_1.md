## Git
## 3 Areas - Working Directory   /   Staging Area      /    Local Repository
##            (modified)           (staged/preparado)        (commited/enviado)
##                        git add                   git commit
```
git --version
mkdir CursoGit
```
```
git config --global user.name "Santos"
git config --global user.email "santos@gmail.com"
git config --list
```
```
git init
```
Abrir Carpeta CursoGit01
Crear archivo.txt


SEGUNDO ESTADO
```
git add archivo.txt
git status
```

Crear archivo2.txt
```
git status
```

Editar archivo2.txt  (modificado el dia 2)
```
git status
git add
git status
```
Edito archivo1 y 2
```
git status
git add --all
```
TERCER ESTADO
```
git status
git commit -m "primer codigo"
git status
Edito archivo1 y 2
git status
git add archivo2.txt
git status
git commit   (vim agrego comentario y salgo)
git status
```
```
git log 
```

GITHUB
Crear Repositorio PruebaCursoGit
Explicar las lineas
```
git remote add origin https://github.com/santos-pardos/PruebaCursoGit.git
gir remote -v
git push -u origin main (validarse en GitHub)
```
Explicar ficheros, logs, commits.
Cambiamos archivo2 en VSC
```
git status
git add archivo2.txt
git commit -m "arreglando texto"
(ver que no sale en github esta en local)
git push origin main
```

Modificar archivo.txt en Github
```
git log (3 vs 4 en VSC)
git pull origin main
git log

git help
git help --all
git help push
```

REPAIR
```
Modificación en Working Directory
Crear archivo3.txt desde VSC
Escribir: linea1
git status
git clean (error)
git clean -f
Crear archivo3.txt
git status (untrateked)
git add archivo3.txt
git commit -m "Haciento commmmit para hcer track del archivo"
git status
Escribir: linea2
git status
Crear archivo4.txt 
Escribir: linea1
git status
(Git clean solo limpia los untracked file)
git clean -n   (te dice lo que borra)
git clean -f
git status
git restore archivo3.txt
git status
Ver que linea2 archivo3.txt había sido eliminado
Editar archivo3.txt y crear archivo4.txt con VSC 
Gestion de working area con extensión VSC
```
```
De Staging Area a Working Directory
modificar archivo.txt
git add archivo.txt
git status
git restore --staged archivo.txt
Modificar entre areas con VSC Extension
```
```
De Local Repository a Staging Area
Hacer commmit con VSC extension y con linea de comando. Crear 5 commit
En archivo4.txt agregar 5 lineas con 5 commits.
git log
git reset --hard bf4b09f2fb1fe05df75d273f45495c46971d3d05

```









