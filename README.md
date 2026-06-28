# Carla Ottaviano — Portfolio

## Files
- `index.html` — Homepage (hero, work grid, about, footer)
- `case-study-ai-activity-suggestions.html` — AI Activity Suggestions case study
- `images/` — Put all your images here (create this folder)

## How to add images

Create a folder called `images/` and add these files:

| Filename | What to use |
|---|---|
| `hero-ai-suggestions.png` | Panel de sugerencias (imagen final, la que tiene los checkboxes y las actividades) |
| `entry-popover.png` | El popover "Check out the custom activities made for your lesson!" |
| `wireframe-panel.png` | Wireframe del panel de sugerencias |
| `wireframe-modal.png` | Modal "Create a lesson / Enhance my slides" (propuesta descartada) |
| `final-panel.png` | Mismo que hero, o variante del panel final |
| `comp-curipod.png` | Screenshot de Curipod |
| `comp-notion.png` | Screenshot de Notion AI |
| `comp-canva.png` | Screenshot de Canva Magic Write |
| `comp-quizizz.png` | Screenshot de Quizizz |
| `research-usability.png` | Slide "Usability is High" del research |
| `research-thoughts.png` | Slide "User Thoughts on the Feature" |
| `research-entrypoints.png` | Slide "Other Entry Points into Enhance with AI" |

(Si alguna imagen no carga, el portfolio muestra un placeholder automáticamente — no hay error visible.)

## Password

La contraseña por defecto es `helena2025`. Para cambiarla, buscá esta línea en ambos archivos HTML:

```
const PORTFOLIO_PASSWORD = 'helena2025';
```

Cambiala por la que quieras. Tiene que ser la misma en los dos archivos.

## Subir a GitHub Pages

1. Creá un repo en github.com (ej: `carla-portfolio`)
2. Subí todos los archivos (index.html, case-study-*.html, la carpeta images/)
3. Andá a Settings → Pages → Source: Deploy from branch → main → / (root)
4. En unos minutos tu portfolio va a estar en: `https://tu-usuario.github.io/carla-portfolio`

## Cambiar la contraseña después de publicar

Solo editá los dos HTML en GitHub directamente (click en el archivo → ícono del lápiz) y cambiá el valor de `PORTFOLIO_PASSWORD`.
