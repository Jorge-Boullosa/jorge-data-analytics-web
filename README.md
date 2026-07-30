# Jorge Boullosa | Web de análisis de datos

Web sencilla y editable para presentar servicios de análisis de datos, informes, dashboards e indicadores.

## Archivos

- `index.html`: contenido de la web.
- `styles.css`: diseño visual.

## Cómo editarla

Puedes abrir `index.html` con cualquier editor de texto, por ejemplo Visual Studio Code, Bloc de notas o el editor de GitHub.

Partes principales que puedes cambiar:

- Título principal: busca `<h1>`.
- Servicios: busca la sección `id="servicios"`.
- Proyectos: busca la sección `id="portfolio"`.
- Sobre mí: busca la sección `id="sobre-mi"`.
- Contacto: busca la sección `id="contacto"`.

## Cómo añadir una foto

1. Crea una carpeta llamada `img`.
2. Mete dentro una foto, por ejemplo `foto-jorge.jpg`.
3. En `index.html`, sustituye este bloque:

```html
<div class="about-placeholder">
  <span>Aquí puedes añadir tu foto</span>
</div>
```

por este:

```html
<img class="about-photo" src="img/foto-jorge.jpg" alt="Foto de Jorge Boullosa">
```

Después añade al final de `styles.css`:

```css
.about-photo {
  width: 100%;
  border-radius: 24px;
  object-fit: cover;
  box-shadow: 0 18px 50px rgba(15, 23, 42, 0.10);
}
```

## Cómo publicarla en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y `styles.css`.
3. Entra en Settings → Pages.
4. En Branch, selecciona `main` y carpeta `/root`.
5. Guarda y GitHub te dará una URL pública.
