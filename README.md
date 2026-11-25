# Disuco — Sitio web

Sitio estático (HTML + CSS + JS, sin dependencias) de **Disuco**: *Building Bridges; Integrating Logistics*.

## Estructura

```
disuco-website/
├── index.html          # Página principal (Home, Services, Our Story, About, Contact)
├── css/styles.css      # Estilos y diseño responsive
├── js/main.js          # Menú móvil y navegación activa
└── assets/
    ├── logo-mark.svg       # Isotipo de Disuco
    ├── petals.svg          # Elemento decorativo
    └── hero-logistics.png  # Ilustración principal
```

## Ver en local

Abre `index.html` en el navegador, o ejecuta:

```bash
python3 -m http.server 8000
```

y visita http://localhost:8000

## Subir a GitHub

```bash
git init
git add .
git commit -m "Sitio web de Disuco"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/disuco-website.git
git push -u origin main
```

## Publicar con GitHub Pages

1. En el repositorio: **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. Guarda. En unos minutos el sitio estará en `https://TU-USUARIO.github.io/disuco-website/`.
4. Para usar tu dominio propio, escríbelo en *Custom domain* y configura el DNS (registro CNAME hacia `TU-USUARIO.github.io`).

## Pendiente de personalizar

- **Formulario de contacto:** cambia `YOUR_FORM_ID` en `index.html` por el ID de tu formulario de [Formspree](https://formspree.io) (u otro servicio).
- **Datos de contacto y LinkedIn:** en el footer de `index.html`.
- **Imágenes:** `hero-logistics.png` se extrajo de una captura; reemplázala por el archivo original en alta resolución.
- **Textos de Services:** revisa que coincidan con tu oferta actual.
