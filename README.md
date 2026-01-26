# Parking-Automatizado-con-Control-de-Aforo-en-Tiempo-Real

#Tipo de Licencia

#**RESUMEN**
Mi maqueta del parking automatizado estará compuesta por un sistema de sensores colocados estratégicamente en la entrada.
Al detectarse un vehículo en el acceso, el sistema activará de forma automática la subida de la barrera y mostrará en el panel un mensaje de _BIENVENIDO_. De igual modo, al detectar un vehículo en la salida, la barrera se abrirá y el panel mostrará un mensaje de _HASTA LUEGO, BUEN VIAJE_.
Cada plaza estará equipada con un sensor de ocupación que enviará información al controlador principal, que en nuestro caso usaremos Arduino.
Según el estado de cada plaza, se encenderá una luz verde (libre) o roja (ocupada). Estos datos se reflejarán simultáneamente en el panel LED, donde se mostrará el número de plazas disponibles. Existirá otro panel superior donde solamente figure el estado del parking, es decir cuando el sistema detecte que quedan plazas libres dentro del parking lo indicará con un mensaje de "_PARKING LIBRE_" y cuando detecte que todas las plazas están ocupadas, el panel indicará claramente "_PARKING COMPLETO_". Además, el panel contará con un reloj digital que mostrará la hora en tiempo real, aportando un aspecto más completo y realista al conjunto.

#**ABSTRACT**
My model of the automated parking garage will consist of a system of sensors strategically placed at the entrance.
When a vehicle is detected at the entrance, the system will automatically raise the barrier and display a "WELCOME" message on the panel. Similarly, when a vehicle is detected at the exit, the barrier will open and the panel will display a "GOODBYE, HAVE A GOOD TRIP" message.
Each parking space will be equipped with an occupancy sensor that will send information to the main controller, which in our case will use an Arduino. 
Depending on the status of each space, a green (free) or red (occupied) light will illuminate. This data will be simultaneously displayed on the LED panel, which will show the number of available spaces. 
There will be another panel above that only displays the parking garage's status; that is, when the system detects that there are free spaces within the garage, it will indicate this with a "_PARKING AVAILABLE_" message, and when it detects that all spaces are occupied, the panel will clearly indicate "_PARKING FULL_". In addition, the panel will feature a digital clock that displays the time in real time, giving the whole a more complete and realistic look.
