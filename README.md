# Zarilu pastelería · página web

Página para clientes de Zarilu pastelería: catálogo, armado del pedido y envío por WhatsApp.
Se publica en Cloudflare Pages (sitio estático, sin compilación).

## Archivos

- `index.html`: la página.
- `productos.js`: productos, tamaños y precios. **Es el único archivo que hay que reemplazar cuando cambian los precios.**
- `img/`: fotos de los productos, logo y QR de Instagram.
- `_headers`: le indica a Cloudflare que siempre sirva los precios actualizados.

## Configuración en Cloudflare Pages

- Framework preset: **None**
- Build command: *(vacío)*
- Build output directory: **/**

## Cómo actualizar precios

1. Pedile a Claude el `productos.js` actualizado.
2. En GitHub, entrá al repositorio, tocá **Add file → Upload files**, arrastrá el `productos.js` nuevo y tocá **Commit changes**.
3. Cloudflare publica el cambio solo en uno o dos minutos.
