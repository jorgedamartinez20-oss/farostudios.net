# Faro Studios — Landing page

Sitio estático (HTML/CSS/JS puro, sin build) listo para GitHub Pages.

```
index.html
assets/
  css/style.css
  js/main.js
  img/            (fotos reales tomadas del diseño en Figma)
```

## Subir a GitHub Pages

1. Crea un repo nuevo en GitHub (puede ser público o privado si tienes GitHub Pro/Team).
2. Sube todo el contenido de esta carpeta a la raíz del repo:

   ```bash
   cd faro-studios-web
   git init
   git add .
   git commit -m "Landing page Faro Studios"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Build and deployment → Source: "Deploy from a branch"**, elige la rama `main` y la carpeta `/ (root)`. Guarda.
4. En un par de minutos tu sitio queda publicado en:
   `https://TU-USUARIO.github.io/TU-REPO/`

Si quieres tu propio dominio (ej. farostudios.com), agrégalo en la misma sección de Pages, en "Custom domain", y crea el registro DNS (CNAME) correspondiente con tu proveedor de dominio.

## Notas

- Las fotos en `assets/img/` son las mismas del diseño en Figma, sin comprimir (pesan ~18 MB en total). Si en algún momento el sitio se siente lento, puedo comprimirlas sin perder calidad visible.
- El botón "Solicitar cotización" del footer/CTA apunta a un `mailto:` de ejemplo (`hola@farostudios.com`) — cámbialo por tu correo real o un formulario cuando lo tengas.
- El menú es responsive (hamburguesa en móvil) y usa las mismas 7 secciones del diseño original: Inicio, Eventos, Corporativo, Audio, Academia, Nosotros, Contacto.
- Tipografías: Fraunces (títulos) + Manrope (texto), cargadas desde Google Fonts.
