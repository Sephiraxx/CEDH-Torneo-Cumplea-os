# Publicar el proyecto con GitHub Pages

## 1. Subir los archivos

Creá un repositorio nuevo en GitHub y subí **el contenido de esta carpeta**, no la carpeta contenedora.

La raíz del repositorio debe quedar así:

```text
README.md
index.md
_config.yml
assets/
mazos-y-guias/
```

## 2. Activar GitHub Pages

1. Abrí el repositorio en GitHub.
2. Entrá en **Settings**.
3. Abrí **Pages** en el menú lateral.
4. En **Build and deployment**, seleccioná **Deploy from a branch**.
5. Elegí la rama **main**.
6. Elegí la carpeta **/ (root)**.
7. Presioná **Save**.

## 3. Abrir el sitio

La dirección tendrá este formato:

```text
https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/
```

GitHub mostrará el enlace definitivo en la misma pantalla de **Settings → Pages**.

## Actualizaciones

Cada cambio enviado a la rama `main` volverá a desplegar el sitio automáticamente.

## Importante

- No cambies el nombre de la carpeta `mazos-y-guias` sin actualizar los enlaces.
- Los enlaces usan `relative_url`, por lo que funcionan tanto en un repositorio de proyecto como en un sitio de usuario.
- Los archivos `.txt` se publican como descargas directas.
