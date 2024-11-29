# Proyecto orientado a objetos - Aeropuerto

En este proyecto buscaremos una solucion para un Aeropuerto 
Se diseñara una aplicación donde tiene un menu para de cualquier persona, por una parte una aerolinea nueva quiera empezar operaciones en el aeropuerto, el cual se le mostrara el horario disponible que exista, en base a esto tendra que escoger una de las opciones disponibles para este. Y del otro lado al pasajero se le desplegara la informacion suya y del vuelo proximo a tomar y despegar.

Al agregar el UML logramos saber como los objetos intercatuan entre el sistema de una manera mas facil e intuitiva 

Para correr el codigo es necesario poner esto en la terminal:

g++ -std=c++11 AeropuertoMain.cpp

./a.out

En caso de no se ejecute, implementar lo siguiente:

Asegúrese de que los archivos de datos (aeropuertos.txt y datosVuelosC-1.txt) estén en el mismo directorio que el programa ejecutable.
Compile el programa principal:
bash
Copiar código
g++ AeropuertoMain.cpp -o Aeropuerto
Ejecute el programa:
bash
Copiar código
./Aeropuerto
Siga las instrucciones del menú para interactuar con el sistema.


Funcionalidades Principales


Clase Aeropuerto:
Representa un aeropuerto con información sobre su ubicación, número de puertas de embarque (gates), pistas de aterrizaje y horarios disponibles.
Permite visualizar y seleccionar horarios disponibles para aterrizaje y despegue.
Proporciona detalles sobre el aeropuerto, incluyendo su nombre, localización, número de puertas y pistas.


Clase Aerolinea:
Representa una aerolínea con su nombre, país de origen, ingresos y un itinerario asociado.
Permite registrar una nueva aerolínea e ingresar información relevante.
Calcula y muestra una comisión basada en los ingresos.
Proporciona detalles de la aerolínea, como su nombre, origen, ingresos y comisiones.


Clase Itinerario:
Representa un vuelo con información sobre su hora, fecha, destino, gate y precio del boleto.
Permite buscar vuelos ingresando criterios como hora, fecha y destino.
Proporciona un resumen detallado del itinerario, incluyendo información del pasajero y recordatorios para abordar.


Clase Pasajero:
Representa un pasajero con información personal como nombre, edad, nacionalidad y número de maletas.
Proporciona métodos para visualizar y editar la información del pasajero.


Clase Avion:
Representa un avión con detalles como modelo, fabricante y capacidad de pasajeros.
Muestra información sobre la aeronave.


El sistema utiliza archivos externos para leer y mostrar información inicial:
aeropuertos.txt: Contiene la lista de aeropuertos y sus datos principales.
datosVuelosC-1.txt: Incluye información de vuelos disponibles.

 Menú de Interacción
El programa principal (AeropuertoMain.cpp) ofrece un menú interactivo donde:

Las aerolíneas pueden ingresar al sistema para seleccionar horarios y gestionar su información.
Los pasajeros pueden buscar vuelos y recibir detalles de su itinerario.


