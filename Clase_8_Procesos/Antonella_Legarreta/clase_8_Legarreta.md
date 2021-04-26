# Procesos

Cuando la informacion que tiene un programa se carga en la memoria y se pone en ejecución, se le denomina proceso. El sistema operativo organiza el orden en que se ejecutan estos.
Se ejecutan uno a la vez y no se almacenan en la RAM, y son efimeros.

Los procesos pasan por estados:

* Nuevo: Cuando se crea
* Preparado: Cuando el SO lo carga en la memoria
* Ejecucion: Cuando se empieza a ejecutar
* Bloqueado: Cuando queda en espera para que otro proceso use los recursos
* Terminado: Cuando se termina de ejecutar

### Mecanismos de comunicación (IPC)

* Señales: Aviso entre procesos, el SO se encarga de que el proceso que recibe la señal tome una accion para gestionarla 
* Memoria compatida: Recurso compartido para que puedan intercambiar información

Cuando un proceso no puede resolverse instantáneamente se crean procesos "hijos" cuya funcion es realizar subtareas para que el proceso original pueda cumplir su objetivo.

* Procesos independientes: No pueden ser afectados ni afectar a otros procesos del sistema
* Procesos cooperativos: Si pueden afectar y ser afectado. Cualquier proceso que comparta recursos o datos con otro es considerado cooperativo.

## Actividad Sincrónica

![1](https://user-images.githubusercontent.com/72288819/115946945-f064f880-a49a-11eb-86b1-4142bef6b97a.jpg)
![2](https://user-images.githubusercontent.com/72288819/115946950-f2c75280-a49a-11eb-95d6-01d9d9975bad.jpg)
![3](https://user-images.githubusercontent.com/72288819/115946953-f4911600-a49a-11eb-8922-0a9b37bbc620.jpg)
