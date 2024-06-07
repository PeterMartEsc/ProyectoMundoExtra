# Requisitos

<div style="text-align: justify">

El alumno debe de crear la solución que cumpla con las siguientes restricciones:

- Al menos 5 tablas en una base de datos.
- Api Rest de cada una de las tablas.
- Documentación de la Api.
- Securización de los métodos de la API.
- Interacción con una web relacionada con el tema, así mostrar los datos implementados en la API y a través de javascript.
- Defensa, creación de un video demostrativo de máximo 10 minutos, que cumpla:
- Descripción del problema.
- Tecnologías utilizadas.
- Cobertura de código.
- Documentación de la API.
- Securización de a API a través de JWT.
- Demostración de funcionamiento.
- Un ejemplo podría ser el siguiente:

<br>

__Título:__ API REST para un Sistema de Gestión de Héroes de Videojuegos

__Descripción del Proyecto:__

Mi proyecto consiste en realizar un sistema completo para gestionar héroes de videojuegos utilizando una base de datos relacional. El sistema incluirá una API REST para interactuar con los datos de la base de datos, realizando la documentación detallada de la API, securizando los métodos para la manipulación de datos, y creando una interfaz web que permita la interacción con la API a través de JavaScript.

</div>

# Mi trabajo

La temática de mi trabajo será el videojuego <a src="https://es.wikipedia.org/wiki/Blasphemous">__Blasphemous__</a>.


Las tablas utilizadas serán las siguientes:

### Personajes

| id | nombre                                 | primeraAparicion |
|----|----------------------------------------|------------------|
| 1  | El Penitente                           | 1                |
| 2  | Quirce, el Devuelto por las Llamas     | 3                |
| 3  | Crisanta de la Agonía Vendada          | 2                |
| 4  | Afilaor, Centinela del Esméril         | 5                |
| 5  | Eviterno, el Primero de los Penitentes | 4                |


### Localizaciones

| id | nombre                              |
|----|-------------------------------------|
| 1  | Hermandad del Lamento Mudo          |
| 2  | Altos de la Archicatedra            |
| 3  | Muralla de las Santas Prohibiciones | 
| 4  | Lluvias Carmesí                     |
| 5  | Bajo Sus Suelos                     |

### Cuentas del Rosario

| id | nombre              | efecto                |
|----|---------------------|-----------------------|
| 1  | Oliva Congelada     | 50% de resistencia contra todos los ataques mientras la barra de vida esté por debajo del 20%  |
| 2  | Corazón Carmesí de un Miura  | Aumenta la velocidad de ataque en un 80% cuando la salud está por debajo del 20%.           |
| 3  | Precio de la Sangre | Aumenta ligeramente las lágrimas de enmienda obtenidas al matar a un enemigo                    |
| 4  | Esfera Besada por la Tormenta | Aumenta considerablemente la resistencia al daño por relámpago                              |

### Armas

| id | idPersonaje | nombre                |
|----|----|--------------------------------|
| 1  | 1  | Mea Culpa                      |
| 2  | 2  | Espada Prendida en Llamas      |
| 3  | 3  | Espada de las Cintas Carmesí   |
| 4  | 4  | Rueda de Afilar y Espadas      |

### Logros

| id | nombre           | descripcion                                    |
|----|------------------|------------------------------------------------|
| 1  | Duelo de Fe      | Vence a Crisanta de la Agonía Vendada          |
| 2  | Summa Blasphemia | Vence a Su Santidad Escribar                   |
| 3  | En nombre de las Altas Voluntades | Lleva todas ofrendas al Señor de las Orillas Saladas |
| 4  | Salto de fe      | Libérate de la Maldición de los Sin-Perdón.    |
| 5  | Nudosos son los caminos del Milagro | Escucha los ecos del pasado.|
| 6  | Lienzo de la luz y el tiempo | Desbloquea el final A.             |


### Herramientas Utilizadas

