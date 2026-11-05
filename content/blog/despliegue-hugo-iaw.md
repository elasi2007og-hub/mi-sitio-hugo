---
title: "Despliegue de sitios estáticos con Hugo en IAW"
date: 2026-10-25 12:00:00
draft: false
---
En esta entrada repasamos las ventajas de utilizar un generador de sitios estáticos como **Hugo** en el módulo de **Implantación de Aplicaciones Web (IAW)**:

- **Velocidad y seguridad:** al compilar a HTML y CSS puros, no requiere base de datos ni ejecución de código dinámico en el servidor.
- **Plantillas modulares:** gracias a los parciales (`layouts/partials/header.html` y `footer.html`), mantenemos una cabecera y pie de página consistentes en todas las secciones.
- **Control de versiones con Git:** tanto el código fuente en Markdown como el sitio estático generado quedan versionados en [GitHub](https://github.com/elasi2007og-hub/elasi2007og-hub).
