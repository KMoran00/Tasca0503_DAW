# Diseño de Interfaces Web (DIW)

## Introducción

Durante este sprint DIW ha girado en torno a: metaetiquetas HTML, SEO técnico, Bootstrap local, tipografías y usabilidad.

## Metaetiquetas principales

- **charset**: Codificación de caracteres (UTF-8).
- **viewport**: Comportamiento en dispositivos móviles.
- **description**: Descripción para los motores de búsqueda.
- **keywords**: Palabras clave del contenido.
- **author**: Autor o equipo responsable.
- **robots**: Permisos de indexación (index, follow).

## SEO técnico: etiquetas semánticas

- `header` · `nav` · `main` · `section` · `aside` · `footer`
- `h1` único por página, seguido de `h2`, `h3`.
- Atributo `alt` en todas las imágenes.

## Bootstrap local

```css
css/bootstrap.min.css + js/bootstrap.bundle.min.js
```

## Tipografías (@font-face)

```css
@font-face {
    font-family: MiFuente;
    src: url(fonts/mifuente.woff2) format(woff2);
}
body { font-family: MiFuente, sans-serif; }
```