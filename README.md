## Practica1Softca

## Crear repositorio
	1. Se crea un repositorio en nuestro GitHub llamado Practica1Softca

[Crear repositorio](https://github.com/new)

	2. Se clona nuestro repositorio en local con el comando

	git clone https://github.com/franciscofsg/Practica1Softca.git

    

## Screenshots

![Screenshot1](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/1.gitclone.png?raw=true)

# README
	3. Se crea en nuestro repositorio local un documento README.md con el comando touch README.md, y tambien se crea una carpeta con los screenshots de los comandos usados hasta el momento

## Screenshots

![Screenshot2](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/2.readme.png?raw=true)

    4. Añadimos al README.md los comandos utilizados hasta ahora y hacemos un commit inicial con el mensaje commit inicial.

![Screenshot4.1](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/4.1commitinicial.png?raw=true)

![Screenshot4.2](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/4.2.readme.png?raw=true)

     5. Subimos los cambios al repositorio remoto con el comando git push origin main

![Screenshot5](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/5.push_inic.JPG?raw=true)

   ## Ignorar archivos
    6. Creamos en el repositorio local un fichero llamado privado.txt con el comando:

    touch privado.txt

    7. Creamos en el repositorio local una carpeta llamada privada con el comando

    mkdir privada 

    8. Realizamos los cambios oportunos para que tanto el archivo como la carpeta sea ignorada por git:

     Creamos un archivo en la carpeta local con extension .gitignore

     Se añade *.txt para ignorar archivos .txt y privada/ para ignorar la carpeta privada.

    git add .
    git commit -m "añadido fichero .gitignore"

![Screenshot6](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/6.ignore.png?raw=true)

![Screenshot7](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/7commit_ignore.png?raw=true)
    

## Añadir fichero 1.txt

    9. Añadimos el fichero 1.txt al repositorio local.

    touch 1.txt
    git add .
    git commit -m "añadido 1.txt"

![Screenshot8](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/8.png?raw=true)


## Crear el tag v0.1

    10. git tag v0.1


## Subir el tag v0.1

    11. Subir los cambios al repositorio remoto

    git push --tag origin master

## Crear una rama v0.2

    12. Creamos una rama v0.2 con el comando

![Screenshot12](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/12.branch.jpg?raw=true)

    13. Posicionamos nuestra carpeta de trabajo en esta rama.

![Screenshot13](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/13.check.png?raw=true)

## Añadir fichero 2.txt

    14.  Añadimos un fichero 2.txt en la rama v0.2.

![Screenshot14](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/14.touch.png?raw=true)

## Crear rama remota v0.2

    15. Subimos los cambios al repositorio remoto.

git push origin v0.2

![Screenshot15](https://github.com/franciscofsg/Practica1Softca/blob/main/Screenshots/15.push.png?raw=true)


## Merge directo

16. Nos posicionamos en la rama main.

git checkout main

17. Hacemos un merge de la rama v0.2 en la rama main.

git merge v0.2 -m "merge v0.2 sin conflictos"











