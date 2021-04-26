# Introduccion a Git

Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Su propósito es llevar registro de los cambios en archivos de computadora incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos en un repositorio de código.

El Campus Virtual ofrece una guía de instalación de este software.

* Repositorio Local: Es el que tiene todos los archivos que hayamos guardado, en la computadora.
* Commit: Paquete que nos permite hacer un seguimiento de los cambios que vamos realizando, nuestro historial.

### Comandos

```
git init // crea el repositorio local
git config user.name "nombre de usuario" // agrega nuestro nombre de usuario
git config user.email "nombreUsuario@email.com" // agrega nuestro email
git remote add origin <link del repositorio remoto> // apunta al repositorio remoto
git add . // agrega todos los archivos
git status // estado del seguimiento de archivos
git commit -m "mensaje" // 'commitea' los cambios hechos
```

_Es importante recordar que los archivos a los que queramos hacer `<commit>` deben tener seguimiento, o sea, previamente debemos hacer `<add>`_
