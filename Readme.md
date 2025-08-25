Git Fundamentos
Fecha: 24 de agosto de 2025

## Comandos de Git utilizados desde la consola de Visual Studio Code

1. **Consultar configuracion de Git (nombre, email y color)**
    Comando: "git config --list"
    Resultado: confirmacion de los datos ya configurados

2. **Navegacion entre carpetas**
    Comandos: "dir" "cd"
    Resultado: ubicacion deseada donde crear la carpeta

3. **Creacion de repositorio**
    Comando: "git init AprendiendoGit"
    Resultado: "Initialized empty Git repository in C:/Users/..."

4. **Creacion de Readme.md e index.html**
    Comandos: "New-Item Readme.md" "New-Item index.html"
    Resultado: archivos creados en la carpeta actual

5. **Abriendo el repositorio/archivo**
    Comandos: "code ."/"code Readme.md"
    Resultados: repositorio actual/archivo especificado abierto en Visual Studio Code

6. **Consultar estado del repositorio**
    Comando: "git status"
    Resultado: informacion de la rama, los commits y cambios

7. **Añadir cambios a la zona de intercambio temporal**
    Comandos: "git add Readme.md" "git add ."
    Resultado: archivos seleccionados listos para el commit

8. **Confirmar cambios**
    Comando: "git commit -m "Mensaje" "
    Resultado: cambios a la zona de intercambio temporal guardados y añadidos al repositorio

9. **Vinculacion con GitHub**
    Comando: "git remote add origin https://github.com/Ariadna-S708/AprendiendoGit.git"
    Resultado: repositorio remoto vinculado con el repositorio de GitHub

10. **Verificar el repositorio remoto vinculado**
    Comando: "git remote -v"
    Resultado: listado de URLs configuradas del repositorio remoto

11. **Subir cambios a GitHub**
    Comando: "git push -u origin master"
    Resultado: cambios locales subidos a GitHub, rama master establacidad como predeterminada y confirmacion del envio