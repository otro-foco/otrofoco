# OtroFoco — sitio inicial

Sitio estático listo para GitHub Pages, sin compilación ni dependencias de JavaScript.

## Antes de publicarlo

1. El correo `rgimenez@otrofoco.com.ar` y el teléfono/WhatsApp `+54 9 11 3701-2533` ya están incorporados. Verificá que el correo esté operativo y que Rocío autorice publicar su teléfono personal. El botón de contacto usa `mailto:`; no hay formulario ni envío desde el servidor.
2. Pedile a Rocío que revise los textos y la identidad visual: este diseño es un punto de partida, no una identidad definitiva.
3. Si no querés usar Google Fonts, podés retirar la línea `@import` de `styles.css`; se utilizarán las fuentes alternativas.

## Publicación en GitHub Pages

1. Creá un repositorio de GitHub (por ejemplo, `otrofoco-web`).
2. Subí a la **raíz** los archivos `index.html`, `styles.css`, `script.js`, `favicon.svg` y `CNAME`.
3. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main` y carpeta `/(root)`.
4. En **Settings → Pages → Custom domain**, verificá que figure `otrofoco.com.ar`.
5. En NIC Argentina / DNS, configurá los registros del dominio para GitHub Pages siguiendo la documentación oficial: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site . **No borres los MX, SPF, DKIM ni DMARC de Zoho.**
6. Una vez propagado el DNS y disponible el certificado, activá **Enforce HTTPS**.
7. Probá el sitio en celular y escritorio, todos los enlaces y el botón de correo.

## Cómo editar

- **Textos y secciones:** `index.html`.
- **Colores, fuentes, espaciados, tamaños:** `styles.css`. Colores principales al comienzo en `:root`.
- **Menú de celular y año automático:** `script.js`.
- **Ícono de pestaña:** `favicon.svg`.
- **Dominio:** `CNAME`.

## Servicio de marcas e INPI

Se agregó una sección informativa de orientación inicial para el registro de marcas. El sitio no promete registros exitosos ni servicios legales. Antes de ofrecer gestión de trámites a terceros, verificar los requisitos del INPI y, si corresponde, trabajar con un agente de propiedad industrial o abogado habilitado.

## Ideas para la segunda versión

- Sustituir la ilustración abstracta por un diseño de Rocío.
- Incorporar proyectos reales con descripción del problema, proceso y solución.
- Agregar correo profesional visible y, si corresponde, redes sociales.
- Añadir una política de privacidad si se incorpora un formulario o analítica.
- Optimizar SEO, imágenes y accesibilidad después de las primeras pruebas.


## Actualización: identidad visual
- Se incorporó `logo-otrofoco.png`, basado en la imagen elegida para la marca.
- Se reemplazó el símbolo provisional en la cabecera, portada y pie de página.
- Se conservaron los verdes y se añadieron acentos dorados.
- En contacto se dejó **WhatsApp** y correo; se quitó el enlace duplicado de llamada telefónica.
- Para cambiar el logo más adelante, sustituir `logo-otrofoco.png` por una imagen con el mismo nombre.
