# Kyoko Collection Bot — sitio estático

## Antes de publicar
- Abre `privacy.html` con un editor de texto y completa los dos campos entre corchetes de la sección 13 con el responsable autorizado y un correo de contacto real del proyecto. No publiques tu correo personal ni otros datos personales innecesarios. Comprueba que el responsable pueda atender solicitudes de privacidad y eliminación de datos. Revisa la política con el responsable antes de publicarla; no es una garantía legal.
- La integración de Pinterest está pendiente de aprobación; no se presenta como activa. Se conservan Unsplash y Pexels como servicios opcionales de la v0.9.3; retíralos de la política si se eliminan del bot.
- Confirma que la información de catálogo siga vigente. La cantidad de fichas con imagen puede ser menor que el catálogo total.

## Publicar en GitHub Pages
1. Crea un repositorio público llamado `kyoko-collection-bot` en una cuenta autorizada (https://github.com/new). Puedes inicializarlo con un README.
2. Descomprime el ZIP y sube `index.html`, `privacy.html` y `styles.css` a la raíz del repositorio con Add file > Upload files. Puedes subir también este README y `.nojekyll` (opcional). No subas el ZIP como único archivo ni archivos del motor, `.env`, bases de datos o claves.
3. Confirma los cambios (Commit changes) en la rama `main`.
4. En Settings > Pages, elige Deploy from a branch, `main`, `/(root)` y Save.
5. Cuando se despliegue el sitio, abre el enlace que muestra GitHub Pages. Comprueba que ambas páginas abran sin iniciar sesión.

## Enlaces para el formulario de Pinterest
Sustituye USUARIO por el nombre de la cuenta que posee el repositorio:
- Sitio web: `https://USUARIO.github.io/kyoko-collection-bot/`
- Política de privacidad: `https://USUARIO.github.io/kyoko-collection-bot/privacy.html`

Son ejemplos, no enlaces activos hasta que se publique el repositorio. No se garantiza la aprobación de Pinterest ni de Partner Search.

Documentación: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
