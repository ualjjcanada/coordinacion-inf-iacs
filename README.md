# coordinacion-inf-iacs

## Generar la página

El contenido se edita en `index.md` y la plantilla en `_layouts/default.html`.
Con Ruby y Jekyll instalados, genera el sitio estático con:

```sh
jekyll build
```

El resultado se guarda en `docs`. Después de cada cambio, vuelve a generar el
sitio e incluye los archivos generados en el commit.

## Publicar en GitHub Pages

1. Sube los cambios a la rama `main` del repositorio.
2. En GitHub, abre **Settings > Pages** y selecciona **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/docs`, y guarda la configuración.

La página estará disponible en <https://ualjjcanada.github.io/coordinacion-inf-iacs/> cuando finalice la publicación.
