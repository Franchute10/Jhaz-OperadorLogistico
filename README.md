# Jhaz Operador Logístico — Sitio web

Nuevo sitio web optimizado para captación de leads, SEO y motores de IA.

## Deploy en GitHub Pages (5 minutos, gratis)

1. Crear repo en GitHub → subir todos los archivos → Settings → Pages → main branch → root → Save
2. Live en `https://tunombre.github.io/repo/` en 2-3 minutos
3. Para `jhaz.com.pe`: agregar Custom Domain en Pages + 4 registros A DNS apuntando a IPs de GitHub

IPs de GitHub Pages: `185.199.108.153` / `.109.153` / `.110.153` / `.111.153`

## Archivos clave

- `index.html` — Home con cotizador en vivo
- `credito.html` — Landing de crédito 30 días
- `servicio-nacional.html` — Página de servicio (replicar por servicio)
- `blog.html` + `articulo.html` — Motor SEO de contenidos
- `portal.html` / `portal-dashboard.html` / `portal-envio.html` — Portal del cliente
- `llms.txt` — Para que ChatGPT/Perplexity/Claude indexen el sitio
- `robots.txt` — Allowlist explícita de crawlers de IA

## Próximos pasos post-deploy

1. Conectar formulario del cotizador a HubSpot Forms embed
2. Instalar Google Analytics 4 + Microsoft Clarity
3. Registrar en Google Search Console → enviar sitemap.xml
4. Fotos reales (reemplazar stock)
5. Agregar testimonios reales con nombre + empresa
