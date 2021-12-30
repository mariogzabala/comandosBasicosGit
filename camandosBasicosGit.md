## CONFIGURACION GLOBAL
```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
## CONFIGURACION LOCAL
```
$ git config --local user.name "John Doe"
$ git config --local user.email johndoe@example.com
```
## INICIAR UN REPOSITORIO GIT EN LOCAL
```
$ git init
```
## INICIAR UN REPOSITORIO EN REMOTO
 - En github crear un repositorio ```CON``` readme
 - Copiar la url del repositorio creado
 - Clonar el repositorio la PC
 - Ingrear a la raiz del repositorio creado 

## INICIAR UN REPOSITORIO EN REMOTO PARA UNIR A UN REPOSITORIO LOCAL
 - En github crear un repositorio ```SIN``` readme
 - En el directorio raiz de nuestro proyecto, ingresamos los siguientes comandos:
```
git remote add origin < url del repo >
git branch -M main
git push -u origin main
```

## VER ESTADO DEL REPOSITORIO
```
$ git status
```

## GUARDAR CAMBIOS
```
$ git add nombre del archivo
$ git add . // todos los archivos
```

## VERSIONAR CODIGO
```
$ git commit -m"titulo del commit"
```

## SUBIR LOS CAMBIOS
```
$ git push
```

## BAJAR LOS CAMBIOS
```
$ git pull
```
