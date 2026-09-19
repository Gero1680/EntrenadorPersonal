# Mi Entrenador — GitHub Pages

## Publicación

1. Crea un repositorio nuevo en GitHub, por ejemplo `mi-entrenador`.
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio.
3. En GitHub entra en:
   **Settings → Pages**
4. En **Build and deployment**, selecciona:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Guarda.
6. GitHub mostrará una URL parecida a:

   `https://TU-USUARIO.github.io/mi-entrenador/`

## Instalar en Android

Abre esa URL con Chrome en Android.

Si el navegador reconoce la PWA:
**⋮ → Instalar aplicación** o **Añadir a pantalla de inicio**.

## Importante

GitHub Pages proporciona HTTPS, necesario para que el Service Worker y la instalación PWA funcionen.

Los datos del entrenamiento se guardan localmente en el dispositivo mediante `localStorage`. Si borras los datos del navegador o cambias de dispositivo, el historial local no se transfiere automáticamente.
