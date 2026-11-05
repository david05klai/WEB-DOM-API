# Explorador de publicaciones

Abre `PAGES/Index.html` directamente en el navegador. Si tu navegador bloquea peticiones desde archivos locales, sirve la carpeta `WEB-DOM-API` con `python -m http.server 8000` y abre `http://localhost:8000/PAGES/Index.html`. Necesitas conexión a Internet para obtener `/posts` y `/users` de JSONPlaceholder.

Haz clic en cualquier tarjeta (o enfócala y presiona Enter/Espacio) para ver ID, nombre, usuario, correo, teléfono y sitio web del autor. Cierra la ventana con Escape, la X o clic afuera.

JSONPlaceholder simula el POST; las publicaciones creadas aparecen en la sesión actual, pero no se guardan en el servidor.
