# Maquinas virtuales

## Escritorio Remoto

Un escritorio remoto es una tecnología que permite a un usuario trabajar en una computadora a través de su escritorio gráfico desde otro dispositivo terminal ubicado en otro lugar. Se emplea en el terreno de la informática para nombrar a la posibilidad de realizar ciertas tareas en una computadora (ordenador) sin estar físicamente en contacto con el equipo. Esto es posible gracias a programas informáticos que permiten trabajar con la computadora a distancia.

## Máquinas virtuales

Software capaz de contener un SO, pareciendo una computadora de verdad. 

Las maquinas de sistema emulan una computadora completa. Se crean en el Hipervisor, una capa de software que se instala sobre la parte fisica de la computadora. Asigna recursos físicos.

Hipervisor tipo 1: Corre directamente sobre la parte fisica y sobre este se crean una o mas maquinas virtuales
Hipervisor tipo 2: Corres sobre el SO y es mas lento que el anterior.

Las maquinas de procesos emulan procesos concretos, como, por ejemplo, una aplicación.

En servidores, las máquinas virtuales aprovechan los recursos físicos.

## Contenedores

Es un concepto de empaquetacion de software que incluye la aplicación y todas sus dependencias de ejecución.

* Mas faciles y rápidos de configurar
* Reduce el tamaño del desarrollo
* Aumenta la productividad ayudando a ejecutar las aplicaciones en entornos aislados reduciendo los recursos
* Gestión múltiple, nos permite utilizar varias herramientas para controlarlo
* Permiten ejecutar en un entorno aislado
* Mayor protección para las aplicaciones

## Orquestadores

Sistemas de automatización del despliegue, ajuste de escala y manejo de aplicaciones en contenedores.

* Configuración automática
* Despliegue y levantamiento autmático de servicios basados en contenedores
* Balanceado de carga
* Autoescalado y autoreinicio de contenedores
* Control de la "salud" de cada contenedor
* Intercambio de datos y networking
* Mantenimiento de parámetros "secretos" y configuraciones
