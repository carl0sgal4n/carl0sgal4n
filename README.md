# Web personal de Carlos Galán

Portfolio estático en HTML y CSS. No requiere instalar programas ni ejecutar una compilación.

## Verla en tu ordenador

Descarga los archivos, descomprime el ZIP y abre `index.html` con tu navegador. Para editar, abre `index.html` y `styles.css` en [Visual Studio Code](https://code.visualstudio.com/). Guarda y actualiza la pestaña del navegador.

## Publicarla en GitHub Pages

1. En GitHub, crea un repositorio **público** llamado `TUUSUARIO.github.io` (sustituye `TUUSUARIO` por tu usuario real). Si ya tienes uno con ese nombre, úsalo.
2. Dentro del repositorio: **Add file → Upload files**. Sube `index.html`, `styles.css` y `README.md` a la raíz del repositorio, **sin subir el ZIP**, y pulsa **Commit changes**.
3. Ve a **Settings → Pages → Build and deployment**. En **Source**, elige **Deploy from a branch**; en **Branch**, elige `main` y la carpeta `/ (root)`. Guarda.
4. Tras la publicación, entra en `https://TUUSUARIO.github.io/`. Puede tardar unos minutos. Si aparece un 404, revisa el nombre del repositorio, que `index.html` esté en la raíz y el estado en **Settings → Pages**.

## Mejorarla poco a poco

- Textos: modifica los párrafos dentro de cada sección de `index.html`.
- Enlace de LinkedIn: busca `https://www.linkedin.com/` y sustitúyelo por tu URL exacta. Es un enlace temporal.
- Proyectos: duplica un bloque `<article class="project-card">…</article>` y edita su título, resumen y etiquetas. Añade un enlace público cuando el trabajo esté listo.
- Estilo: modifica los colores al comienzo de `styles.css`, dentro de `:root`.
- Foto y CV: añádelos cuando decidas qué versiones publicar; no incluyas teléfono, dirección ni datos privados en un repositorio público.
- Cada cambio publicado se hace editando los archivos en GitHub y confirmándolo con **Commit changes**.

La página carga dos fuentes de Google Fonts. Si no hay conexión, utiliza Arial como alternativa.
