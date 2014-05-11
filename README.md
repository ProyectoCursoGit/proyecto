## Proyecto Curso Git
Práctica final del curso 'Desarrollo de software colaborativo con Git, 1ª edición' del CEVUG.

### Plantilla personalizada

La plantilla utilizada en este proyecto puede encontrarse
[aquí](https://github.com/ProyectoCursoGit/template_git_personalizado). Se trata de un
fork de otra plantilla a la que hemos añadido nuestros propios hooks.

    ⇒  git clone git@github.com:ProyectoCursoGit/proyecto.git --template template_git_personalizado/template
    Clonar en «proyecto»...
    remote: Counting objects: 124, done.
    remote: Compressing objects: 100% (97/97), done.
    remote: Total 124 (delta 52), reused 88 (delta 16)
    Receiving objects: 100% (124/124), 44.48 KiB | 0 bytes/s, done.
    Resolving deltas: 100% (52/52), done.
    Checking connectivity... done

    ⇒  cd proyecto
    ⇒  ls .git/hooks
    pre-commit  prepare-commit-msg

    ⇒  touch prueba.bak
    ⇒  git add prueba.bak
    ⇒  git commit
    No puede haber archivos terminados en .bak
