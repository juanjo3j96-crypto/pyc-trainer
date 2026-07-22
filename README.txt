PyC TRAINER — FUNCIONES PROTECTIVAS

Contenido
- index.html: aplicación completa y banco inicial de 90 preguntas.
- manifest.webmanifest + sw.js + icon.svg: permiten instalarla como PWA y usarla sin conexión después de la primera carga.

Uso rápido
1. Para probar en un PC, abre index.html.
2. Para usarla cómodamente en el móvil e instalarla, publica la carpeta en un alojamiento HTTPS (GitHub Pages, Netlify, servidor interno, etc.).
3. Abre la URL desde el móvil y elige «Añadir a pantalla de inicio» o «Instalar aplicación».

Datos
El progreso, preguntas falladas, marcadas y eliminadas se guardan en localStorage del navegador. Desde Ajustes se puede exportar/importar una copia JSON.

Edición del banco
Las preguntas están en la constante QUESTIONS dentro de index.html. Cada registro contiene id, función, categoría, dificultad, enunciado, opciones, respuesta, explicación, fuente y posición.

Nota técnica
El banco combina criterios de la Guía SRZ001, NZC001, SDC005, la tabla formativa aportada y principios funcionales. Debe contrastarse siempre con la versión vigente de las normas, los criterios del gestor y el esquema concreto del proyecto.
