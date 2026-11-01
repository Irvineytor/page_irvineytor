# Portfolio de Irvin Aguirre

Sitio estático en español, listo para publicar en un hosting web. No requiere Node.js, base de datos ni compilación.

## Archivos

- `index.html`: contenido y estructura de la página.
- `styles.css`: diseño adaptable a celular, tableta y escritorio.

## Personalización antes de publicar

1. Confirma las fechas y nombres de puestos de tu CV, en especial la estancia en Sist3c.
2. Revisa que quieras mostrar públicamente el correo que aparece en los botones de contacto.
3. Sustituye o complementa los casos con enlaces a repositorios, demos o imágenes propias cuando estén disponibles.
4. Si prefieres que el CV sea descargable, coloca una versión pública y depurada del PDF en esta carpeta y agrega un enlace; el sitio no publica el archivo personal automáticamente.
5. La tipografía usa Google Fonts. Si quieres que el sitio no dependa de un tercero, elimina el enlace a Google Fonts del encabezado y deja las fuentes alternativas del sistema.

## Publicación

Sube `index.html` y `styles.css` al directorio público de tu hosting web, normalmente `public_html` en HostGator o la raíz configurada para `irvineytor.tech` en tu VPS. Asegúrate de que el dominio apunte al hosting elegido y tenga HTTPS habilitado desde su panel de control.

El diseño es independiente del servidor: sirve con Apache o Nginx como archivos estáticos. No contiene formularios, rastreadores ni dependencias de ejecución.
