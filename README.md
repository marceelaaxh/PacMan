## Cambios realizados por Marce

### Punto uno - hacer a los fantasmas más listos
Se ha implementado una nueva lógica para hacer que los fantasmas sigan a Pac-Man de manera más inteligente:
- **Distancia euclidiana**: Se ha añadido un algoritmo que calcula la distancia más corta entre los fantasmas y Pac-Man. 
- **Movimiento basado en la cercanía**: Los fantasmas ahora evalúan varias direcciones posibles y eligen la que minimiza la distancia hacia Pac-Man.
- **Evitar atascos**: Si un fantasma no puede moverse en una dirección (debido a una pared), elige otra dirección aleatoriamente para continuar moviéndose.

### Nueva funcionalidad
- Los fantasmas ajustan su movimiento basándose en las opciones direccionales que los acercan a Pac-Man.

### Código clave
Se añadieron las funciones `distance` y `best_direction` para calcular la distancia más cercana entre Pac-Man y los fantasmas.
