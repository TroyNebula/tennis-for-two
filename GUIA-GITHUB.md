# Tu primera publicación en GitHub

Creadora: **Troy Nebula**.

## 1. Preparar la carpeta

Descomprime `Tennis-for-Two-Gamers-GitHub.zip`. Abre la carpeta `tennis-for-two-gamers`. Debes ver `index.html` y los demás archivos. Sube estos archivos, **no el ZIP**.

## 2. Crear el repositorio

1. Entra en tu cuenta de https://github.com.
2. Pulsa **+ → New repository**.
3. Nombre: `tennis-for-two`.
4. Descripción sugerida: `Adaptación táctil de Tennis for Two para dos jugadores. Creada por Troy Nebula.`
5. Elige **Public** si quieres compartirlo públicamente. En cuentas gratuitas, GitHub Pages requiere un repositorio público.
6. No añadas otro README ni selecciones una licencia diferente: el paquete ya contiene la documentación y el archivo `LICENSE` con PolyForm Noncommercial 1.0.0.
7. Pulsa **Create repository**.

## 3. Subir el juego

1. En el repositorio vacío, pulsa **uploading an existing file**. Si ya contiene archivos: **Add file → Upload files**.
2. Arrastra los archivos de dentro de la carpeta descomprimida. `index.html` debe quedar en la raíz del repositorio, no dentro de una segunda carpeta.
3. Texto del cambio: `Primera versión de Tennis for Two`.
4. Pulsa **Commit changes**.

Los archivos `.nojekyll` y `.gitignore` pueden estar ocultos en el ordenador. Si no consigues seleccionarlos, puedes crearlos desde **Add file → Create new file**. `.nojekyll` puede contener una línea vacía; `.gitignore` solo ayuda a evitar subir archivos temporales. No necesitas terminal ni Git instalado para esta primera subida.

## 4. Activar el enlace para jugar

1. En el repositorio, entra en **Settings → Pages**.
2. En **Build and deployment → Source**, elige **Deploy from a branch**.
3. En **Branch**, selecciona `main` y `/(root)`.
4. Pulsa **Save**.
5. Espera a que GitHub termine la publicación. La sección Pages mostrará el enlace del juego.

Subir el código y publicar el juego son dos pasos distintos. GitHub Pages es lo que permite jugar en el navegador desde un enlace.

## 5. Probar y guardar como app

Abre el enlace en iPad/iPhone en horizontal. Comprueba ambos mandos y que, al no devolver un saque válido, el punto va a quien sacó. En Safari: **Compartir → Añadir a pantalla de inicio**.

## Documentación oficial

- Subir archivos: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Crear un sitio con GitHub Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Configurar la publicación: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
