# Inventario de publicaciones

App web para el inventario mensual de revistas, libros y folletos. Funciona en el celular:
lee QR o código de barras con la cámara, cuenta por paquetes y por peso, suma ubicaciones,
y genera el reporte para sucursal (WhatsApp, Excel, PDF).

- `index.html`: la app completa.
- `config.js`: conexión con Supabase (Project URL y clave pública).
- `sw.js`: permite abrirla sin internet.

Usuarios: se crean en Supabase → Authentication → Users.
