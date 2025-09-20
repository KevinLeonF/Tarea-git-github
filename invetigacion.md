## Tarea #1
## Parte I - **invetigacion**
1. ¿Qué es Git y para qué se utiliza?

Es un sistema controlador de de versiones de proyectos, gratuito y de codigo abierto utilizada mayormente para el desarrollo de software. Nos sirve para registrar cambios sobr el proyecto que se esta trabajando de manera que si es que ocurre un error en alguna parte se tenga una copia de una version anterior lo cual facilita mucho el trabajo entre muchos desarrolladores.

2. ¿Qué diferencia hay entre Git y GitHub?

Git es la herramienta que usamos para realizar los commits en nuestro equipo. Github es el repositorio remoto que se encuentra en la nube y es donde se sube el proyecto de trabajo, se encarga de guardar el repositorio y compartirlo con los colaboradores del mismo.

3. Explica en tus palabras qué es un repositorio.

Es el lugar en donde se guarda el proyecto en el que se esta trabajando con la finalidad de tener un registro de todos los cambios que se realizan y llevar un historial mejor estructurado.

4. ¿Qué significa hacer un commit en Git?

El commit es la forma de guardar los cambios que se acaban de hacer y se lo acompaña de un -m "" en el cual se pone una pequeña descripcion del cambio que sea directo y conciso para saber que se hizo.

5. Investiga y explica brevemente los siguientes comandos de Git:
      - git config --local user.name "<GitHub user name>"
        Configura el nombre de usuario en el repositorio local.
      - git config --local user.email "<GitHub email>"
        Configura el correo electronico de usuario en el repositorio local.
      - git init
        Inicializa la carpeta en el repositorio local.
      - git add
        Añade las carpetas y documentos nuevos para que se suban con el commit.
      - git commit
        Crea la nueva version del proyecto en el repositorio.
      - git push
        Sube los cambios del repositorio local al repositorio remoto.
      - git clone
        Crea una copia del repositorio remoto en nuestro equipo para trabajar desde ahi.
      - git init --initial-branch=main
        Inicializa el repositorio local con una rama principal que se llamara main.
      - git remote add origin https://github.com/<user-name>/tarea-git-github.git
        Vincula el repositorio local con el remoto.
      - git add .
        Añade todos los archivos que se modificaron para realizar el commit.
      - git commit -m "Initial commit"
        Crea la nueva version del repositorio pero esta vez con un comentario entre comillas.
      - git push --set-upstream origin main
        Sube los cambios en la rama main y crea un seguimiento de los siguientes git push. 
6. ¿Qué es un archivo README.md y por qué es importante?

Es un archivo Markdown que se crea como modo de presentacion del proyecto ya que es lo primero que se muestra por debado de los archivos que esten subidos en el repositorio, este puede contener una descripcion detallada o pequeña sobre lo que trata el proyecto.
