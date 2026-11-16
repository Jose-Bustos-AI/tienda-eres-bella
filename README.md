# Eres Bella · tienda Shopify de demostración

Tienda de cosmética natural con sérums, cremas, aceites, jabones y un set de regalo: portada a pantalla completa con el set de regalo flotando sobre la foto, rutina de tres pasos, más vendidos con compra directa y colecciones de rostro y cuerpo.

**Verla publicada:** https://eres-bella-znud0un0.myshopify.com/ (contraseña de la tienda de prueba: `skaung`)

## Qué hay en este repositorio
Solo lo hecho a medida sobre el tema gratuito Horizon de Shopify: las secciones y fragmentos propios (prefijo `eb-`), las plantillas que los colocan y los ajustes del tema. El resto de Horizon no se incluye.

```
sections/eb-*.liquid     Secciones propias de la portada
snippets/eb-*.liquid     Estilos y fragmentos propios
templates/*.json        Plantillas con las secciones colocadas
sections/*-group.json   Cabecera y pie
config/settings_data.json  Colores, tipografías y ajustes del tema
```

## Cómo está hecha
- Shopify, tienda de desarrollo con el plan Basic
- Tema Horizon, el tema oficial y gratuito de Shopify
- Seis secciones de portada programadas a medida en Liquid: portada, compromisos, más vendidos, rutina en tres pasos, categorías y filosofía de marca
- Portada con titular animado, tarjeta flotante de producto, tres datos de confianza y cinta de frases en movimiento, que se desactiva si el visitante pide menos animación
- Paleta, tipografías (Cormorant y Jost) y botones redondeados propios de la marca
- Tienda, menús, correos y páginas de sistema en español

## Catálogo y compra
- 16 productos de rostro, cuerpo y cabello, cuatro de ellos en oferta con el precio tachado
- Set de rutina facial que agrupa tres productos con 9,80 € de ahorro
- Botón "Añadir al carrito" directo desde la portada
- Colecciones automáticas: Rostro y Cuerpo por tipo de producto, y Más vendidos por etiqueta
- Fotos de producto creadas para la marca
- Mercado España en euros, con el precio en formato español (24,90 €)
- Envío estándar a 3,95 €, gratis a partir de 39 €, y envío exprés a 6,95 €
- Pasarela de pago de prueba de Shopify activa
- Pedido de prueba completo: carrito, envío calculado, pedido pagado y correo de confirmación en español

## Detalles
- Sin apps de terceros: todo funciona con herramientas propias de Shopify (colecciones, mercados, envíos, pagos y correos)
- Tema subido con Shopify CLI y código revisado con Theme Check, sin errores en las secciones propias
- Estilos compartidos en un fragmento propio, para que cada sección funcione aunque se quite otra

## Cómo instalarlo
1. Instala el tema Horizon en tu tienda y descárgalo con Shopify CLI (`shopify theme pull`).
2. Copia encima las carpetas de este repositorio.
3. Súbelo con `shopify theme push` o pruébalo con `shopify theme dev`.

## Sobre esta tienda
Diseño y desarrollo de [Dania360](https://dania360.com). Es una tienda de ejemplo: la marca y los productos son inventados, las fotos se crearon para la marca y el pago es de prueba, no cobra nada. El código se publica para enseñar cómo está hecha; no tiene licencia de uso.

Más tiendas en el portafolio: https://tiendas.dania360.com
