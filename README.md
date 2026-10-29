# Plantilla NoExpertise · Clínica y salud

Web limpia para clínicas, dentistas y fisios, con cita por WhatsApp y preguntas frecuentes.

- Sectores: clinica, dental, fisio. Estilo: limpio. Plan mínimo: presencia.
- Secciones: hero, servicios, equipo, citas, preguntas, contacto.
- SEO de base incluido (`src/lib/seo.ts`): canónica, og:image, JSON-LD del negocio y de las preguntas frecuentes, `robots.txt`, `sitemap.xml` y `llms.txt`; `noindex` si `seo.indexable: false`.
- Contenido editable en `site.yaml`; metadatos en `template.yaml`; reglas para el agente en `CLAUDE.md`.

```
npm ci
npm run dev      # desarrollo
npm run build    # web estática en dist/
```

Basada en [AstroWind](https://github.com/onwidget/astrowind) © onWidget, licencia MIT (`LICENSE-ASTROWIND.md`). Imágenes de relleno (`public/placeholders/`) generadas para esta plantilla, sin licencias de terceros.
