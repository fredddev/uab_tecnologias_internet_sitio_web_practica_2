# Grupo 1 — Proyecto Sitio Estático Accesible

Este es el sitio web del **Grupo 1** para la materia de UAB, donde cada integrante presenta su **serie o película favorita**.  
El sitio está construido únicamente con **HTML5 y CSS**, cumpliendo con criterios de **semántica, accesibilidad (A11y)** y **SEO básico**.

## Integrantes (orden alfabético en PascalCase)

- Freddy Vincenty Paniagua  
- Jhilda Achacollo  
- Jheny Chirinos Moreira  
- Kevin Stiven Copali Mendieta  
- Marco Antonio Copa Sarzuri  
- Peter Camacho Cardozo  

## Estructura del proyecto

```
/ (raíz del sitio)
├── index.html      ← Freddy (plantilla base con ejemplo de Suits)
├── jheny.html
├── kevin.html
├── marco.html
├── peter.html
├── jhilda.html
├── ada.html        ← Declaración de accesibilidad (A11y)
└── styles.css      ← Único archivo de estilos
```

## Instrucciones para cada integrante

1. Copiar `index.html` y renombrarlo con su nombre (ej. `kevin.html`).  
2. Editar las secciones marcadas con comentarios `<!-- CAMBIAR ... -->`.  
   - **Título (`<title>`)** → poner su nombre y su obra favorita.  
   - **Meta descripción** → breve texto con su nombre y la obra.  
   - **Encabezado `<h3>`** → “Reseña de [Nombre]: [Obra]”.  
   - **Sinopsis `<p>`** → redactar un resumen personal.  
   - **Lista `<ul>`** → género, temporadas/duración, plataforma.  
   - **Enlace externo** → Wikipedia, IMDb, sitio oficial u otro recurso confiable.  
   - **Imagen `<img>`** → usar un póster local (`.jpeg`/`.png`) con `alt` descriptivo.  
   - **Figcaption** → breve descripción de la imagen.  
   - **ID de sección** → cambiar `freddy-h` por `[su-nombre-h]`.  
3. Verificar que la navegación con **teclado (Tab)** funciona correctamente.  
4. Revisar contraste y foco visible (no ocultar con CSS).  

## Accesibilidad (A11y)

- Skip link al inicio (`Saltar al contenido`).  
- Estructura con landmarks (`header`, `nav`, `main`, `footer`).  
- Foco visible en enlaces y botones.  
- Contraste suficiente (texto oscuro sobre fondo claro).  
- Textos alternativos (`alt`) en imágenes.  
- Enlaces con texto significativo.  

## SEO básico

- Títulos y descripciones únicos por página.  
- Uso de `lang="es"`.  
- Enlaces con `rel="noopener noreferrer"` al abrir en nueva pestaña.  
- URL canónica en cada archivo.  
