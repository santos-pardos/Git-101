## DESHACER CAMBIOS
```
git log
Eliminar linea en archivo.txt
git checkout  fichero2
Eliminar liena en archivo.txt
git add .
git status
git restore --staged archivo.txt
git status
git add .
git reset HEAD  archivo.txt
git status
git chekcout archivo.txt
vim archivo.txt
git add .
git commit -m "cambios a deshacer"
git log
git log --oneline
git reset --soft HEAD~1
git status
git log
git commit -m "cambios a deshacer"
git reset --hard HEAD~1
ver archivo.txt
git status
git log
modificar archivo.txt
git add .
git commit -m "cambios a deshacer"
git log
git revert HEAD
modificar el mensaje. hace commit nuevo para deschacer cambios. mismo que reset pero con otro commit
git log
cat archivo.txt
verlo de forma grafia en sourcetree
```

## RESOLUCION DE CONFLICTOS
```
modificar archivo.txt
git add .
git commit -m "confictos 1"
modificar archivo.txt (modificar la misma linea)
git add .
git commit -m "conflictos 2"
modificar archivo.txt (modificar la misma linea)
git add .
git commit -m "conflictos 3"
ver commit en sourcetree (ver a modificación misma linea)
revert conflictos 1 de forma grafica
ver archivo.txt conflicto en sourcetree 
cat archivo.txt (ver el conflicto)
modificar y quitar los conflictos y hacer commit bien a mano o con vsc, sourcetree
```

## SUBIENDOO BAJAND CAMBIOS
```
ver os cambios si están sincronizados o no
sync con GitHub desktop o sourcetree
git status
git push origin main
modificar archivo.txt en GitHub y realizar un commit
git fetch
git pull
```

## ENCONTRAR ERRORES
```
modificar archivo2.txt
git add .
git diff   (son iguales entre ambas áreas)
git restore --staged archivo2.txt
git diff  (me muestra la diferencia)
git log
git log --graph
ver archivo.txt en sourcetree y ver log selecter y ver cambios
```
```
git blame archivo2.txt  
(te muestra los cambios y los commits y los no subidos)
modifica archivo2.txt
git blame
ver git blame en sourcetree (log selected)
```

## RAMAS - MERGE
```
coger repositorio de ramas y clonarlo
https://github.com/santos-pardos/git-merge.git
crear repositorio en blanco
mkdir demomerge
cd demomerge
git init
clear
copiar y pegar los códigos con sourcetree
git status
git add .
git commit -m "Commit inicial"
git brach develop
git checkout develop
git checkout -b feature/index
copiar y pegar los códigos con sourcetree
git add .
git commit -m "incializamos index"
copiar y pegar los códigos con sourcetree
git add .
git commit -m "cambiamos colores morados"
copiar y pegar los códigos con sourcetree
git add .
git commit -m "añadir los códigos de inicio"
git checkout develop
git merge feature/index
(usa la estrategia fast forward)
git log
git reset --hard 45vf657   (al inicial)
git merge --no-ff feature/index
(elegir mensaje de commit)
ver en sourcetree
```

## RAMAS - REBASE
```
coger repositorio de ramas y clonarlo
https://github.com/santos-pardos/git-merge-rebase.git
hacer lo mismo que en MERGE
.. 
..
git checkout develop
git rebase feature/index
..
..
```
## RAMAS - STASH
```
coger repositorio de ramas y clonarlo
https://github.com/santos-pardos/git-merge-rebase.git
(entramos dentro)
modificamos ficheros
git status
git stash
(mueve todo a un cajon)
git status
(modificamos otras ramas etc)
git stash apply
git status
realizar cambios stash con sourcetree
```

## SALTANDO ENTRE COMMITS
```
git log
git log --online
git checkout HEAD~1
git status
git checkout main
```


## TAGS
```
(apunta a commit específicos)
git checkout v1.0.0
(ver el cambio en sourcetree y cli)
(sirve para marcar un hito)
situarce en el ultimo commit
clear
git tag mi-nueva-etiqueta
git push origin main --tags
(crear etiquetas desde sourcetree)
```

## RELEASES  (extensiones de tags)
```
coger repositorio de ramas y clonarlo
https://github.com/santos-pardos/git-merge-rebase.git
ver tags y releases en GitHub
```

## ISSUES
```
mirarlo en GitHub
```

##  PULL REQUESTS
```
(Project manager - developers)
```

##  CICD
```
(Project manager - developers)
```
