# Donde fuimos dos ♡

Sitio web romántico, estático y gratuito para GitHub Pages. Incluye corazones animados, portada, galería, historia, carta y visor de fotos.

## Publicarlo en GitHub

1. Crea un repositorio **público** nuevo, por ejemplo `donde-fuimos-dos`.
2. Sube a la raíz del repositorio `index.html`, `style.css`, `script.js`, `fotos.json` y la carpeta `fotos/`.
3. En GitHub abre **Settings → Pages → Build and deployment**.
4. Elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.
5. Espera a que GitHub publique. Tu enlace será parecido a `https://TU-USUARIO.github.io/donde-fuimos-dos/`.

## Agregar fotografías después

1. En el repositorio abre la carpeta **fotos**.
2. Pulsa **Add file → Upload files** y selecciona todas las imágenes que quieras.
3. Confirma con **Commit changes**. ¡Listo! La galería se actualiza automáticamente al volver a cargar el sitio.

Admite JPG, JPEG, PNG, WEBP, GIF y AVIF. No hace falta modificar `index.html`, `script.js` ni `fotos.json`. La galería consulta la API pública de GitHub para listar el contenido de la carpeta `fotos`.

**Importante:** esta función automática requiere que el repositorio sea público y que el sitio se abra en GitHub Pages. Al abrir `index.html` directamente desde el equipo no puede enumerar la carpeta. Si tienes miles de visitas en poco tiempo, GitHub puede limitar temporalmente la consulta pública; para ese caso puede usarse un archivo `fotos.json` con los nombres.

## Personalizar

- Modifica los textos de `index.html`.
- Los colores y tipografías están en `style.css`.
- La portada y la galería se adaptan a móviles.
- Las fotografías que subas a un repositorio público podrán ser vistas por cualquiera que tenga el enlace y también por visitantes del repositorio. Pide consentimiento antes de publicar fotos privadas.
