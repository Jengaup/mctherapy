# M.C. Therapy Center LLC — Sitio Web

Sitio web estático profesional para **M.C. Therapy Center LLC**, un centro de terapia pediátrica especializado.

---

## Publicar en GitHub Pages

### Opción más sencilla — desde Settings

1. Ve a tu repositorio en GitHub: `https://github.com/jengaup/mctherapy`
2. Haz clic en **Settings** → **Pages** (menú lateral izquierdo)
3. En **Source**, selecciona `Deploy from a branch`
4. En **Branch**, elige `main` y carpeta `/ (root)`
5. Haz clic en **Save**
6. En unos minutos tu sitio estará en: `https://jengaup.github.io/mctherapy/`

---

## Estructura del proyecto

```
mctherapy/
├── index.html                  <- Página principal
├── assets/
│   ├── css/
│   │   └── styles.css          <- Estilos principales
│   ├── js/
│   │   └── main.js             <- JavaScript
│   └── images/
│       ├── logo.png            <- REEMPLAZAR con el logo real
│       ├── favicon.png         <- REEMPLAZAR con favicon (32x32 px)
│       └── og-cover.png        <- REEMPLAZAR con imagen Open Graph (1200x630px)
└── README.md
```

---

## Lista de personalización

### Imágenes
- Reemplaza `assets/images/logo.png` con el logo real del centro
- Agrega `assets/images/favicon.png`
- Agrega `assets/images/og-cover.png` para compartir en redes sociales

### Datos de contacto (busca estas cadenas en index.html)
- `+1XXXXXXXXXX` → cambia al número de teléfono real
- `info@mctherapycenter.com` → cambia al correo real
- `[Dirección completa aquí]` → agrega la dirección real
- `[X:XX am – X:XX pm]` → agrega los horarios reales

### SEO
- Actualiza `og:url` con la URL real del sitio publicado

---

## Paleta de colores

| Color       | Variable CSS    | Hex       |
|-------------|-----------------|-----------|
| Turquesa    | `--turquoise`   | `#27C7D9` |
| Fucsia      | `--fuchsia`     | `#E61B8C` |
| Morado      | `--purple`      | `#6A1BB1` |
| Amarillo    | `--yellow`      | `#F7C948` |
| Blanco      | `--white`       | `#FFFFFF` |

Los colores se definen en `assets/css/styles.css` bajo `:root {}`.

---

## Tecnologias

- HTML5 semantico
- CSS3 con Custom Properties
- JavaScript vanilla (sin dependencias, sin build steps)
- Fuentes: Google Fonts (Poppins + Nunito)

Compatible directamente con GitHub Pages — sin instalaciones ni configuracion adicional.

---

Facebook: https://www.facebook.com/mctherapycenter

(c) M.C. Therapy Center LLC. Todos los derechos reservados.
