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
git push -u origin master  (validarse en GitHub)
```
Explicar ficheros, logs, commits.
Cambiamos archivo2 en VSC
```
git status
git add archivo2.txt
git commit -m "arreglando texto"
(ver que no sale en github esta en local)
git push origin master
```

Modificar archivo.txt en VSC
```
git log (3 vs 4 en VSC)
git pull origin master
git log

git help
git help --all
git help push
```







