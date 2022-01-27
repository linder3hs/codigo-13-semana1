# Codigo 13

## Comando para GIT

```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git
- 👁️ crear una 📁 carpeta oculta llamada ```.git```


```
git status
```
- Poder listar y ver si los archivos estan listo para subir
- :eye: en caso los archivos no esten listos se veran de color rojo y cuando lo esten seran de color verde


```
git add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir los guada en un stash

```
git commit -m "comentario"
```
- Crear un punto en la linea de tiempo ⏰ de nuestros cambios y a estos se le es posible adjuntar un comentario
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github


```
git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la nube, en este caso github

```
git branch
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente


```
git checkout -b nombre_del_branch
```
- Sirve para crear un branch nuevo y poder trabajar en el


```
git checkout nombre_del_branch
```
- Sirve para poder moverme entre ramas
- :eye: Si el checkout no tiene el -b solo es para moverse
