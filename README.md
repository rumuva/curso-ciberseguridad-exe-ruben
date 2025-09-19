# Curso de Ciberseguridad (50 h) – Basado en 'Ciberseguridad para Torpes – Ed. Ampliada'

**Autor:** Rubén Muñoz Valadés – Docente SSCE0110  
**Fecha:** 2025-09-19

Este repositorio contiene un **curso online** listo para presentar a empresas o publicar como **GitHub Pages**.
Está maquetado para que puedas **importar los contenidos en eXeLearning** (copiar/pegar por iDevices) y exportar a **SCORM 1.2/HTML5**.

## Estructura
- `/docs` — sitio web (GitHub Pages). Abre `docs/index.md`.
- `/content` — fuentes en Markdown (una lección por archivo).
- `/scorm` — paquete HTML + `imsmanifest.xml` (SCORM 1.2) sencillo.
- `/assets` — logo y multimedia.
- `/exe` — guion para **eXeLearning** (JSON con iDevices sugeridos).
- `README.md` — esta guía.
- `LICENSE` — licencia MIT (puedes cambiarla).

## Publicar en GitHub Pages
1. Sube este repositorio a GitHub.
2. En *Settings → Pages*, elige **Deploy from Branch** y carpeta **/docs**.  
3. Tu sitio quedará disponible en `https://<tuusuario>.github.io/<repo>/`.

## Usar en eXeLearning
1. Abre eXeLearning (≥ 2.8).  
2. Crea un proyecto nuevo y, por cada **lección**, añade iDevices recomendados (ver `/exe/idesign.json`).  
3. Copia/pega el contenido desde `/content/*.md`.  
4. Exporta **HTML5** o **SCORM 1.2** y prueba en un LMS (Moodle) o navegador.

## Créditos
Basado en el libro **“Ciberseguridad para Torpes – Edición Ampliada”** de Rubén Muñoz Valadés – Docente SSCE0110.  
Logo en `/assets/logo.png`.
