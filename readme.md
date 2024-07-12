# Cafetería Agere

Ejemplo de solución

## Patron Sass 7-1

El desafío hace uso del patrón de diseño Sass 7-1 junto con el "archivo de la verguenza" donde se implementan los estilos que no sabemos clasificar.

En este caso los elementos overlay están implementados en `_map.scss` y en `_logo.scss`.
La técnica consiste en superponer dos elementos HTML haciendo uso de las propiedades `display: relative` para un contenedor padre y `display: absolute` en un contenedor hijo. Este hijo será quien esté desplazado a través de las propiedades `top, right, bottom, left` con respectivas unidades de medida.

## consideraciones

La propiedad `display: relative` esconderá el contenido si el contenedor padre tiene activa la propiedad `overflow: hidden`
