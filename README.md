# Mira Productions — sitio web

Todo el sitio está en **un único `index.html`** (CSS, JavaScript y contenido). Se navega por fragmentos: `#inicio`, `#estudio`, `#proyectos`, `#servicios`, `#comunidad`, `#launcher`, `#tienda`, `#contacto`, `#noticia/ID`, `#proyecto/ID`.

## Editar
Busca `SITE_CONFIG` al inicio del `<script>`: noticias, proyectos, servicios, productos de Ko-fi, enlaces, launcher y colores. `heroImage` pone una imagen de fondo en el inicio (vacío = composición provisional). Las imágenes van en `assets/images/`.

## Formulario
No envía nada hasta poner un servicio externo (p. ej. Formspree) en `contact.formEndpoint`.

## Publicar en GitHub Pages
Sube la carpeta al repositorio → Settings → Pages → rama `main`, carpeta raíz.
