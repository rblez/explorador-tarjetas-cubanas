# Explorador de tarjetas cubanas

Página interactiva que identifica tarjetas bancarias cubanas en vivo: escribes o pegas un número y te dice la red, el producto, la moneda y el banco emisor, con la anatomía del número por segmentos y la validación del dígito de control (Luhn).

La tarjeta se dibuja como la original de cada banco — BANDEC, BPA, Banco Metropolitano, la Clásica de Fincimex y la Tropical — sin nombre del titular, fecha de vencimiento ni códigos de seguridad.

## Datos

Todos los datos vienen del catálogo abierto **[qvapay/cuban_cards_prefixes](https://github.com/qvapay/cuban_cards_prefixes)**, cargados en vivo desde su CDN de jsDelivr (`prefixes.json` y `validators.json`). Esta página no guarda ni envía el número a ningún servidor: la identificación ocurre entera en el navegador.

## Uso

Abre `index.html` en el navegador o visita la versión publicada en GitHub Pages. Sin dependencias ni paso de build.

## Créditos

Datos: comunidad de QvaPay (MIT). Logos e isotipos: propiedad de cada banco, reproducidos con fines de identificación.
