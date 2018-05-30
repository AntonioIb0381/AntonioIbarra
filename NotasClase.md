#Notas de Clase

##COMANDOS TERMINAL:

- **touch**  crear archivos (importante poner su extension de tipo de archivo)
- **mkdir** crear directorios o carpetas
- bandera **-p** crea directiorios madre si no existen
- **ls** listar archivos y carpetas
- **ls -a** mostrar adicionalmente directorios ocultos
- **ls -l** igual a **ll** directorio en forma de lista
- **clear** limpiar consola
- **pwd** mostrar ruta
- **cd** cambiar de directorios
- **cd ..** regresar al directorio anterior
- **rm** remover archivos
- **echo** entre comillas texto que queremos agregar a un archivo + archivo.ext
- **>** redireccionar
- **cat** muestra el contenido de un archivo
- **rmdir** remover directorios vacios
- **rm - r** borrar directorios completos
- **mv** mover archivos (archivo.extencion - ruta)
- **mv** renombrar arcivos (archivo.ext - nuevomonbre.ext)
- **cp** copiar archivos (archivo.txt - ruta)


##EJEMPLOS DE IDENTACION:

1. Primer elemento
    - Primer Objeto
    - Segundo Objeto
      - Tercer nivel

2. Segundo elemento


##Otras caracterisicas

>¨esto es una cita¨

~ 3 de estos simbolos abren un bloquie de codigo, de igual forma se debe cerrar el bloque con 3 simbolos iguales. Ejemplo:

~~~
<html>

</html>
~~~

comilla simple es para poner codigo de una sola linea:

`function startLearning();`

podemos poner link con corchetes y adelante entre parentesis la liga

[este es un link](https://dillinger.io/)

para imagenes:

![mi imagen](http://jsequeiros.com/sites/default/files/imagen-cachorro-comprimir.jpg)  


## GIT

**github: antonioib0381@gmail.com**
**pswd: Sain2309**

same 4 Gitlab

comando para iniciar repositorio: **git init** (dentro de la carpeta donde queremos tenerlo)

comando para checar estado: **git status**

comando para seguir un archivo y agregarlo: **git add** + archivo

comando para hacer checkpoint: **git commit** + **-m** y entre comillas agregar comments

comando para checar los commits que hemos hecho:  **git log**

comando para movernos a dif git: **git checkout** + hash

comando para regresar a la cabeza de la rama: **git checkout HEAD**

para crear una nueva linea de tiempo: **git branch** + nombre de la nueva branch

las ramas del repositorio se definiran como **branch**

**commit** son los checkpoint

**git remote add origin**  + url para agregar el repo remoto

**git remote -v** verificar repositorios remotos

**git push -u origin master** primera vez para sincronizar repo remoto


##Gitlab  **crear repo privado**

## html

**encabezado:**

<!DOCTYPE html>
<html>

</html>


**dentro de head, info y encabezado del navegador**
<head>
</head>

**para usar caracteres especiales y acentos: siempre dentro del emcabezado**
<meta charset="utf-8">

**cuerpo:**

<body>
    <h3>Hola a todos, buen día ñaca ñaca</h3>
    <p> este es un parrafo </p>
</body>

**lista con viñetas NO ordenada**
        <ul>
        <li>Uno</li>
        <li>Dos</li>
        <li>Tres</li>
        </ul>

**lista con viñetas ordenada**
                <ol>
                <li>Uno</li>
                <li>Dos</li>
                <li>Tres</li>
                </ol>        
