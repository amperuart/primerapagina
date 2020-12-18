<!--  ESTADOS DE GIT  -->

1. Working directory (Directorio de trabajo)
    - Es donde tenemos nuestros archivos
    - Nuestro proyecto

2. Staging area (Área de preparación)
    - Todo lo que está listo para realizar cambios
    - Todo lo que hemos modificado

3. .git Directory
    - Todos los cambios confirmados o cambios realizados

1      -       2       -       3
    (git add)     (git commit)

git config user.name "usuario"
git config user.email "correo"

pwd - ubicación
mkdir - crear carpeta
touch - crear archivo
cd - para moverse entre carpetas
cd .. - (subir de nivel)
ls - listar

git init
git add .
git commit -m ""
git log --oneline
git status

.gitignore

clear

git log --oneline --decorate --graph --all
git checkout ######
    para volver en el tiempo

git branch
    x default siempre se crea master
git checkout NOMBRE
    para cambiar de branch

git merge development
    desde el master por ejemplo

github
    git push -u origin master
        O branch en general
    git pull origin BRANCH
    git clone LINK