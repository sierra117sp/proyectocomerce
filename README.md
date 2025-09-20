# Proyectocomerce

Sitio estático de ejemplo para una tienda (e-commerce) — HTML y SCSS.

Descripción
-----------

Proyecto sencillo de front-end que contiene una página estática (`index.html`), estilos en SCSS/CSS y recursos de imágenes dentro de `img/`.

Estructura principal
--------------------

- `index.html` — página principal.
- `styles.scss`, `_base.scss`, `_components.scss`, `_layout.scss` — fuentes SCSS.
- `styles.css`, `styles.css.map` — CSS compilado y sourcemap.
- `img/` — imágenes del proyecto.

Cómo ver el sitio
-----------------

1. Abrir `index.html` en un navegador. (Doble clic o arrastrar al navegador)
2. Si trabajas con SCSS y quieres recompilar manualmente, instala Sass e inicia la compilación:

```bash
# Instala sass (si no lo tienes)
npm install -g sass

# Compila SCSS a CSS (modo una vez)
sass styles.scss styles.css

# O compila en modo watch (recompila al guardar)
sass --watch styles.scss:styles.css
```

Notas de desarrollo
-------------------

- No hay servidor ni backend incluido. Es un sitio estático.
- Mantén los partials SCSS (`_*.scss`) en la raíz junto a `styles.scss` para que `sass` los incluya.

Contribuciones
--------------

1. Haz un fork.
2. Crea una rama con tu cambio: `git checkout -b feature/mi-cambio`.
3. Haz commit y push.
4. Abre un pull request describiendo los cambios.

Contacto
-------

Si necesitas más ayuda o quieres que agregue un README en español más detallado, dime qué se debe incluir (instalación, build, pruebas, etc.).