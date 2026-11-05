---
title: "Publicando nuestro sitio Hugo en GitHub Pages"
date: 2026-11-05 18:45:00
draft: false
---
En esta práctica desplegamos nuestro sitio estático de **Hugo** en Internet a través de **GitHub Pages** siguiendo la filosofía **KISS**:

- Configuramos `baseURL = "https://elasi2007og-hub.github.io/mi-sitio-hugo/"` y `publishDir = "."` en `hugo.toml` para generar el HTML plano directamente en la raíz del repositorio.
- Añadimos `static/.nojekyll` para evitar que GitHub procese el repositorio con Jekyll.
- Utilizamos la función `relURL` de Hugo en `layouts/partials/header.html` para que la hoja de estilos (`css/estilo.css`) y el menú de navegación resuelvan correctamente bajo la subruta `/mi-sitio-hugo/`.

Puedes consultar el código fuente y el sitio compilado en mi [repositorio de GitHub](https://github.com/elasi2007og-hub/mi-sitio-hugo) y visitar mi [perfil de GitHub (P1.1)](https://github.com/elasi2007og-hub/elasi2007og-hub).
