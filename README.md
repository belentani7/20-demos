# 20-demos

Demos y simulaciones HTML para el portfolio de **Pedro Belentani**.

## Contenido

| Archivo | Descripción |
|---|---|
| `PEDRO_BELENTANI_PORTFOLIO.html` | Portfolio completo con Three.js, GSAP y Lenis (loader, cursor, contadores, partículas) |
| `LINKEDIN_SIMULATION.html` | Simulación fiel de perfil de LinkedIn (experiencia, skills, proyectos, actividad) |
| `MALT_FREELANCE_SIMULATION.html` | Simulación de perfil freelance de Malt (servicios, tarifas, reviews, idiomas) |
| `googlw.html` | Landing cyberpunk "Omega Core // Judas Experience" con efectos CRT/glitch |

## Tipografía

Todos los demos usan tipografía premium en lugar de las fuentes por defecto
(no se usan Inter ni Roboto):

| Demo | Tipografías |
|---|---|
| `PEDRO_BELENTANI_PORTFOLIO.html` | Sora (cuerpo) + Space Grotesk (titulares) |
| `LINKEDIN_SIMULATION.html` | Manrope |
| `MALT_FREELANCE_SIMULATION.html` | Plus Jakarta Sans |
| `googlw.html` | Chakra Petch + Share Tech Mono |

## Verificación

- Etiquetas HTML balanceadas (abre/cierra) en los 4 archivos.
- JavaScript inline validado con `node --check`.
- `googlw.html` fue reconstruido completo (el original estaba truncado a mitad
  del CSS, sin body, y con un keyframe inválido `calc(-1px)`).

## Requisitos de red

Los demos cargan recursos vía CDN (Google Fonts, Font Awesome, GSAP, Three.js,
Lenis). Necesitan conexión a internet la primera vez. Sin conexión, se degradan
a las fuentes del sistema y sin efectos 3D/scroll.
