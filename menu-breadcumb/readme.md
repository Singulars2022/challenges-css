# Instrucciones

Escribe el código HTML y CSS necesario para conseguir el diseño esperado. [Diseño](https://oscarm.tinytake.com/msc/NjU2MDY3M18xOTA2NjY1Ng)

**Reestricción**: Utiliza el pseudo-selector ::after o ::before para implementar la solución

# Solución

## ¿Cómo he planteado el problema?
Primero le he quitado el estilo a las listas y he convertido la lista desordenada (ul) en un flex para que los items estuvieran todos en la misma fila.

Despues he utilizado el tag "after" para añadir los slash (/) despues de cada elemento pero al haces esto ha puesto 2 slash así que he utilizado un after en los elementos de la lista (li) para deshacerme de uno.

Finalmente le cambie quite las decoraciones de los enlaces y les cambie el color.

## ¿Cuál ha sido la parte más difícil?
Averiguar porque me aperecían 2 slash y quitar uno de ellos.

## ¿He aprendido algo nuevo? Cita las páginas y recursos que has visitado también
https://developer.mozilla.org/en-US/docs/Web/CSS/::after
