# Carta · Artesanal Colombia — Hamburguesas Alfredo

Carta digital mobile-first. Sin dependencias, sin build, sin servidor.

- Hamburguesas, alitas, perros, salchipapa, menú kids, adicionales y bebidas.
- Carrito que arma el pedido y abre WhatsApp con el mensaje listo.
- Fuentes y fotos servidas localmente: carga sin internet y sin CDN.

## Editar

Los precios y productos están en `index.html`, en el bloque `var CARTA = { ... }`.
El número de WhatsApp está en `var CONFIG` (solo dígitos, con indicativo).

## Publicar

GitHub Pages sirve esta carpeta tal cual. El archivo `.nojekyll` evita el
procesamiento de Jekyll.
