# Portafolio personal

Portafolio de proyectos hecho con HTML, CSS y JavaScript puro (sin frameworks),
siguiendo la misma estructura de carpetas vista en clase (`styles/`, `javascript/`).

## Contenido
- `index.html` — estructura de la página: hero con foto, biografía, carrusel de proyectos y contacto.
- `styles/portfolio.css` — estilos, tema claro/oscuro y diseño responsive.
- `javascript/portfolio.js` — carrusel de proyectos, menú móvil, cambio de tema y validación del formulario.

## Antes de publicarlo
Reemplaza el contenido de ejemplo por el tuyo:
1. En `index.html`: tu nombre, biografía, la foto de perfil (`id="profilePhoto"`), tus proyectos reales (imagen, título, descripción y enlaces) y tus datos de contacto.
2. Revisa los enlaces `href="#"` de cada proyecto y colócales tu repositorio y demo real.

## Cómo subirlo a GitHub y desplegarlo con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `portafolio`).
2. Desde esta carpeta, en tu terminal:
   ```bash
   git init
   git add .
   git commit -m "Portafolio inicial"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/portafolio.git
   git push -u origin main
   ```
3. En GitHub, entra al repositorio → **Settings** → **Pages**.
4. En "Build and deployment" → **Source**, selecciona **Deploy from a branch**.
5. En **Branch**, selecciona `main` y la carpeta `/ (root)`, luego **Save**.
6. Espera uno o dos minutos: GitHub te dará la URL pública, con este formato:
   ```
   https://TU-USUARIO.github.io/portafolio/
   ```

## Enlaces del proyecto
(Complétalos después de subir el repositorio y activar Pages)

- Repositorio: `https://github.com/TU-USUARIO/portafolio`
- Portafolio desplegado (GitHub Pages): `https://TU-USUARIO.github.io/portafolio/`
