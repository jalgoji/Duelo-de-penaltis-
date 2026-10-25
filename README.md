# Penaltis · Duelo

Prototipo PWA para dos jugadores en el mismo móvil.

## Archivos
- `index.html`: juego, interfaz y lógica.
- `manifest.webmanifest`: nombre y ajustes de instalación.
- `sw.js`: almacenamiento en caché para el modo sin conexión.
- `icon.svg`: icono de la aplicación.

## Publicar gratis con GitHub Pages
1. Crea una cuenta en GitHub si no tienes una.
2. Crea un repositorio público, por ejemplo `penaltis-duelo`.
3. Sube estos cuatro archivos a la raíz del repositorio.
4. En el repositorio, entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique la web. Abre el enlace que te indique GitHub en Safari en el iPhone.
7. En Safari, pulsa **Compartir → Añadir a pantalla de inicio**.

## Probar el modo sin conexión
Abre el juego con internet una vez y espera a que cargue por completo. Después prueba a activar el modo avión y vuelve a abrirlo desde el icono de la pantalla de inicio.

## Nota de privacidad
La pantalla oculta la selección en la interfaz para jugar pasando el mismo móvil entre jugadores. No es un sistema de seguridad criptográfica: alguien con conocimientos técnicos podría inspeccionar el código o el estado del navegador.
