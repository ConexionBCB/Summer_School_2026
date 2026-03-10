# Escuela de Verano 2026

Curso avanzado de bioinformática en formato **teach‑the‑teacher** (20–24 de
julio de 2026, de lunes a viernes).

## Página web

El sitio del curso está construido con [Jekyll](https://jekyllrb.com/) para
[GitHub Pages](https://pages.github.com/).

- **Sitio en producción:** una vez activado GitHub Pages para este repositorio,
  estará en  
  `https://conexionbcb.github.io/Summer_School_2026/`
- Asegúrate de que el valor de `url` en `_config.yml` coincide con tu URL de
  GitHub Pages (por ejemplo, `https://conexionbcb.github.io`).

## Ejecutar en local

```bash
bundle install
bundle exec jekyll serve
```

Después abre  
[http://localhost:4000/Summer_School_2026/](http://localhost:4000/Summer_School_2026/).

## Estructura

- `index.md` — Página de inicio (presentación, perfil de participantes, resumen
  de la semana).
- `pages/` — Programa general, una página por día (lunes–viernes) y logística.
- `materials/day1/` … `materials/day5/` — Materiales teóricos y prácticos por
  día; añade aquí diapositivas, cuadernos y datos, y enlázalos desde las
  páginas de cada día.
- `_layouts/` — Plantillas de diseño (maquetación general, páginas internas e
  inicio).
- `assets/css/style.css` — Estilos inspirados en la identidad de Conexión BCB.

Edita `_config.yml` para cambiar el título del sitio, la descripción o la URL
base.
