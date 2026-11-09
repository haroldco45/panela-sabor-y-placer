# Panela Sabor y Placer

App (PWA) de Vibras Positivas HM para **Panela Pulverizada Sabor y Placer**, 100% natural, producida y empacada por Martha Chaverra G. en la Finca El Placer, Yalí (Nordeste Antioqueño). Bolsa de 460 g.

## Qué trae
- Portada con la bolsa real flotando y fondo de panela en movimiento
- Historia de los arrieros y la caña (texto del empaque)
- 3 preparaciones: aguapanela, limonada de panela y chocolate
- Ficha del producto con contadores animados
- Familia Sabor y Placer: pulverizada, pastilla, redonda, cuadrada, porcionada y tacita; se agregan al pedido con un toque
- Pedido por WhatsApp (311 668 6640) con varias presentaciones, nombre y dirección
- `flyer.jpg`: flyer con QR a la app
- Español / Inglés
- Instalable (manifest + service worker), funciona sin internet
- Vista previa del enlace con foto real (`og.jpg`, 1200×630)

## Configurar
En `index.html`, bloque `CONFIG`:
- `whatsapp`: número con 57 adelante
- `precio`: precio por bolsa (0 = "precio a convenir")

## Publicar
Repo: `haroldco45/panela-sabor-y-placer` → Netlify: `panela-sabor-y-placer.netlify.app`.
Si el nombre del sitio en Netlify cambia, actualizar `og:image` y `og:url` en `index.html`.

Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados.
