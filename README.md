<em>Screenmatch App</em>
## Descripción delproyecto:
En este proyecto se utiliza lo siguiente:
* Estructura de un Proyecto Spring: Se crea la estructura inicial de un proyecto Spring y se usan los paquetes, clases y el método run.
* Inferencia de Tipos en Java: Ejemplo práctico de inferencia de tipos con 'var' en el código Java.
* Consumo de API: Consumir APIs a través del método 'obtenerDatos', que devuelve los datos deseados en formato Json.
* Modularización de Código: Se enfoca en la importancia de tener un código modularizado y de fácil mantenimiento.
* Serialización y Deserialización:Cómo transformar JSON en clases y cómo esto es útil para el proyecto.
* Creación de Interfaces e Implementación de Métodos: Se utilizó la creación de una interfaz con un método genérico que utiliza Generics, así como la implementación de este método en una clase separada.
* Inclusión de Nuevas Dependencias en el Proyecto: Cómo agregar una nueva dependencia al archivo .pom.xml y cómo este proceso es gestionado por Maven.

## Descripcion breve de clases del proyecto:

* La clase de conexion a consumir el API: ConsumirAPI.java
* La clase de conversion de datos al obtenerlos del API: ConvierteDatos.java
* La clase principal que contiene el flujo de ejecucion del código: Principal.java
* La clase de ejecución del código: ScreenmatchApplication.java

## Ejemplo de API a consumir
* https://www.omdbapi.com/?t=game+of+thrones&apikey=574c144b
* Respuesta JSON
* {
*   "Title": "Game of Thrones",
*   "Year": "2011–2019",
*   "Rated": "TV-MA",
*   ....    
    "Ratings": [
        {
            "Source": "Internet Movie Database",
            "Value": "9.2/10"
        }
    ],
    "Metascore": "N/A",
*   ....
    "Response": "True"

# Funcionalidades
- `Funcionalidades`:
- Abrir la clase Principal.java
- Ejecutar la clase Principal.java
- En la linea de comandos aparecera el mensaje: Por favor escribe el nombre de la serie que deseas buscar
- Teclear: gameo of thrones
- Mostrará información de la consulta al API con sus respectivos capítulos
- DatosSerie[titulo=Game of Thrones, totalDeTemporadas=8, evaluacion=9.2]
- Unaired Original Pilot
- Winter Is Coming
- The Kingsroad
- Lord Snow
- Cripples, Bastards, and Broken Things
- ...

## Fin de la descripción del proyecto
  
