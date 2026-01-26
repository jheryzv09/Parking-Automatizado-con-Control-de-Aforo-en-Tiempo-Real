# Parking automatizado con control de aforo en Tiempo Real

# RESUMEN

Mi maqueta del parking automatizado estará compuesta por un sistema de sensores colocados estratégicamente en la entrada. Al detectarse un vehículo en el acceso, el sistema activará de forma automática la subida de la barrera y mostrará en el panel un mensaje de _BIENVENIDO_. De igual modo, al detectar un vehículo en la salida, la barrera se abrirá y el panel mostrará un mensaje de _HASTA LUEGO, BUEN VIAJE_.

Cada plaza estará equipada con un sensor de ocupación que enviará información al controlador principal, que en nuestro caso usaremos Arduino. Según el estado de cada plaza, se encenderá una luz verde (libre) o roja (ocupada). Estos datos se reflejarán simultáneamente en el panel LED, donde se mostrará el número de plazas disponibles. 

Existirá otro panel superior donde solamente figure el estado del parking, es decir cuando el sistema detecte que quedan plazas libres dentro del parking lo indicará con un mensaje de "_PARKING LIBRE_" y cuando detecte que todas las plazas están ocupadas, el panel indicará claramente "_PARKING COMPLETO_".

Además, el panel contará con un reloj digital que mostrará la hora en tiempo real, aportando un aspecto más completo y realista al conjunto.

# ABSTRACT

My automated parking project will consist of a system of sensors strategically placed at the entrance. When a vehicle is detected at the access point, the system will automatically raise the barrier and display a _WELCOME_ message on the panel. Likewise, when a vehicle is detected at the exit, the barrier will open and the panel will show a _GOODBYE, HAVE A SAFE TRIP_ message.

Each parking space will be equipped with an occupancy sensor that will send information to the main controller, which in our case will be an Arduino. Depending on the status of each space, a green light (free) or red light (occupied) will turn on. This data will be simultaneously reflected on the LED panel, where the number of available spaces will be displayed.

There will also be an upper panel that shows only the overall parking status. When the system detects that there are free spaces inside the parking lot, it will indicate this with a _PARKING AVAILABLE_ message. When it detects that all spaces are occupied, the panel will clearly display _PARKING FULL_.

Additionally, the panel will include a digital clock showing the real-time hour, providing a more complete and realistic look to the system.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

