TALENTO MARKET - PLATAFORMA DE RECLUTAMIENTO

CONTENIDO
- index.html: sitio público y panel de Recursos Humanos.
- netlify/functions/applications.mjs: API centralizada para postulaciones y evaluaciones.
- netlify.toml y package.json: configuración de despliegue.

REQUISITOS PARA QUE LAS POSTULACIONES SE COMPARTAN ENTRE EQUIPOS
1. Subir esta carpeta a un repositorio GitHub.
2. En Netlify, crear un sitio nuevo importando ese repositorio.
3. En Site configuration > Environment variables, crear TM_ADMIN_KEY con una clave larga y privada.
4. Volver a desplegar el sitio. Netlify Functions y Netlify Blobs guardarán los registros centralmente.
5. Probar una postulación desde un celular y abrir Gestión RR. HH. desde otra computadora.

IMPORTANTE
- No basta con arrastrar únicamente index.html a Netlify: eso publicaría solo la página, sin API ni almacenamiento compartido.
- Debe desplegarse el proyecto completo mediante Git conectado a Netlify o Netlify CLI para compilar y publicar la función.
- La clave TM_ADMIN_KEY no debe compartirse con postulantes ni incluirse en el HTML.
- Los 24 postulantes son registros demostrativos. En Gestión RR. HH. inicia sesión y pulsa “Registrar los 24 postulantes demostrativos” para copiarlos al registro central. Sus respuestas técnicas, STAR y casos quedan visibles; STAR y caso permanecen pendientes de rúbrica.
- Para uso real, completar aviso de privacidad, consentimiento y controles de retención de datos conforme a la normativa aplicable.
