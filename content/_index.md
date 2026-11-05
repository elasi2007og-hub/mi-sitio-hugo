---
title: "Portal Web de Asier Orgaz Gabriel — 2º ASIR (IAW)"
draft: false
---
¡Hola! Bienvenido a mi sitio web estático desarrollado con **Hugo** y desplegado en **GitHub Pages** para el módulo de **Implantación de Aplicaciones Web (IAW)** de **2º ASIR**.

En este proyecto aplico el flujo completo de publicación de sitios estáticos en producción:

1. **Edición de contenido y plantillas:** Contenido escrito en Markdown (`content/`) separado de la estructura HTML (`layouts/`) y los parciales reutilizables (`layouts/partials/header.html` y `footer.html`).
2. **Rutas adaptadas a subruta (`relURL`):** Uso de `{{ "css/estilo.css" | relURL }}` y `{{ .Site.Home.RelPermalink }}` para que todos los estilos y enlaces funcionen correctamente bajo `https://elasi2007og-hub.github.io/mi-sitio-hugo/`.
3. **Generación en la raíz (`publishDir = "."`):** Construcción del HTML plano mediante el comando `hugo` en la raíz del repositorio junto al fichero `.nojekyll`.

## Secciones disponibles

- **[Blog técnico](blog/):** Artículos sobre la creación del sitio con Hugo (P1.2) y su puesta en producción con GitHub Pages.
- **[Página de contacto](contact/):** Datos de contacto académico y enlaces directos a mis repositorios.

## Sobre mí

Soy **Asier Orgaz Gabriel**, estudiante de **2º de Administración de Sistemas Informáticos en Red (ASIR)**. Puedes consultar mi perfil y mi presentación de la práctica **P1.1** en mi [perfil de GitHub (`elasi2007og-hub`)](https://github.com/elasi2007og-hub/elasi2007og-hub).
