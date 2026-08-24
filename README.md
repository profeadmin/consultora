# Consultora Admin - Sitio Web

Landing page de **Consultora Admin**: consultoría y asesoría administrativa para empresas. El objetivo principal del sitio es mostrar los servicios y conseguir contactos a través de WhatsApp.

Sitio 100% estático: **HTML + CSS + JavaScript** (vanilla), sin frameworks ni dependencias. Listo para publicar en GitHub Pages.

## Estructura del proyecto

```
consultora-admin/
├── index.html              # Página principal (única página, one-page)
├── logotipo.png            # Logotipo de la empresa
├── enlaces-sociales.md     # Enlaces de redes sociales (TikTok, Instagram, Facebook, YouTube)
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos del sitio
│   ├── js/
│   │   └── script.js       # Menú móvil, scroll suave, animaciones al hacer scroll
│   └── img/
│       └── favicon.svg     # Favicon
└── README.md
```

## Secciones

- **Inicio (Hero)**: título principal con llamada a la acción por WhatsApp.
- **Servicios**: 8 servicios administrativos, cada uno con botón "Solicitar información" que abre WhatsApp con un mensaje predefinido.
- **Nosotros**: descripción de la empresa y logotipo.
- **Contacto**: llamado a la acción con enlace directo a WhatsApp.
- **Footer**: datos de contacto, redes sociales y navegación.
- **Botón flotante** de WhatsApp visible en toda la página.

## Tecnologías

- HTML5 semántico
- CSS3 (variables CSS, flexbox, grid, animaciones)
- JavaScript vanilla (sin librerías)
- [Google Fonts](https://fonts.google.com/) (Sora e Inter)

## Cómo verlo en local

No requiere instalación ni servidor. Solo abre `index.html` en tu navegador:

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` con doble clic.

Opcionalmente, con un servidor local (por ejemplo con VS Code Live Server o `python -m http.server`).

## Publicar en GitHub Pages

1. Sube todos los archivos al repositorio (la raíz del sitio debe contener `index.html`).
2. En GitHub, entra a **Settings → Pages**.
3. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. El sitio estará disponible en `https://<usuario>.github.io/<nombre-del-repositorio>/`.

Todas las rutas del sitio son relativas, por lo que funciona tanto en subcarpetas de GitHub Pages como en un dominio propio.

## Personalización

- **Número de WhatsApp**: buscar `wa.me/573160537674` en `index.html` y reemplazarlo.
- **Redes sociales**: los enlaces están en el footer; también se guardan en `enlaces-sociales.md`.
- **Colores y estilos**: variables CSS al inicio de `assets/css/style.css`.

## Licencia

Todos los derechos reservados © Consultora Admin.
