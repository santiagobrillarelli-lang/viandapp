# ViandApp

Web para que Clara, Matu y Santi armen juntos el pedido a Anshus y lo manden por WhatsApp.

- `index.html`: toda la app (HTML, CSS y JS en un solo archivo).
- `firestore.rules`: reglas de la base de datos de Firebase.

Los datos de conexión a Firebase van en `window.FIREBASE_CONFIG`, dentro de `index.html`. Sin esos datos la app funciona en modo de prueba y guarda los pedidos solo en el navegador.

Se publica con GitHub Pages desde la rama `main`.
