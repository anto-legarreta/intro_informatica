# Sistemas Operativos

Los sistemas operativos son el soporte lógico que controla el funcionamiento del equipo físico.
Este grupo de programas y funciones ocultan los detalles del hardware, ofreciendo una via de acceso sencilla a este.

* Gestiona la memoria RAM ejecutando aplicaciones y designando recursos
* Administra la CPU
* Direcciona entrada y salida de datos
* Administra la información para el correcto funcionamiento de la computadora
* Dirige autorizaciones de uso para el usuario
* Administra archivos

## Tipos de Sistemas Operativos

* Usuario
	* Multiusuario: Permite varios usarios simultaneamente
	* Monousuario: Permite ejecutar programas de un solo usuario a la vez

* Gestion de tareas
	* Multitarea: Ejecuta varios procesos al mismo tiempo
	* Monotarea: Ejecuta un proceso a la vez

* Gestion de recursos
	* Centralizado: Permite utilizar los recursos de un solo ordenador
	* Distribuido: Permite ejecutar procesos de mas de un ordenador al mismo tiempo

* Estructura interna
	* Monolitica: Programa unico compuesto de una serie de rutinas entrelazadas entre si para comunicarse
	* Jerárquica: Constituido por niveles definidos
	* Maquina virtual: Separa la multiprogramacion de la maquina extendida. Su objetivo es integrar distintos sistemas operativos dando la sensacion de ser varias maquinas diferentes.

## Kernel

El kernel es la capa fundamental de un SO, el encargado de comunicar y administrar los recursos de la computadora.

### Llamadas al sistema

Manera en la cual un programa solicita una accion al SO con el que interactúa. Su objetivo es separar las acciones que puede realizas un usuario (modo usuario) de las que no ya que podrian ser dañinas si no son controladas exclusivamente por el mismo SO (modo privilegiado).
 
### Tipos de Kernel

* Monolitico: Más rapido ya que se comunica con llamadas al sistema, pero el 70% de éste no es utilizado. Si un sistema falla, en este caso, todo el núcleo falla.
* Microkernel: Más lento ya que se comunica por paso de mensajes. Es mas fácil agregar nuevas funcionalidades pero requiere mas lineas de código.
* Híbrido: Es muy parecido al microkernel pero con mas codigo "no escencial". Agiliza la velocidad de un microkernel. Es compatible con varios dispositovos.
* Nanokernel: El código es más reducido que un microkernel pero es mas dificl de crear. Todos los servicios se comuncian con paso de mensajes. Es facil la modificacion del SO.

## Actividad sincrónica

![clase7_paddlet](https://user-images.githubusercontent.com/72288819/115946433-741ce600-a497-11eb-83e6-98f3f73453fd.png)

