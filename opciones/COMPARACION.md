# Comparación de las 5 opciones de README

## Cómo se hicieron
Descargué la lista **awesome-github-profile-readme** completa, revisé los README de sus 180 perfiles y su sección de
herramientas, y medí qué técnicas usan. Lo que más se repite en los buenos perfiles:

- Una imagen al lado del texto con `align="right"` (39 perfiles).
- Secciones desplegables con `<details>` (30) y tablas para organizar en columnas (26).
- Bloques de código como diseño (27).
- **Lo que distingue a los mejores:** imágenes SVG propias guardadas en el repo (Marton Lederer, Livio Brunner) en vez de
  banners genéricos, y contenido que se actualiza solo con GitHub Actions (Simon Willison).

Con eso, cada opción usa **tu mundo real** en lugar de una plantilla de "developer": el libro contable, la ruta de carga,
la hoja de Excel y el script de conciliación.

## Sistema de diseño (igual en las 5)
| Nombre | Color | Para qué |
|---|---|---|
| Pizarra | `#0F1720` | Fondo de tarjetas e imágenes (combina con el oscuro de GitHub) |
| Papel | `#E9E2D0` | Texto principal, como el papel de un libro contable |
| Verde libro | `#2E6B4F` | Color de marca: los libros de contabilidad de tapa verde |
| Menta | `#7FC8A9` | Verde legible para detalles y selección de celdas |
| Ámbar carga | `#E0A43A` | El acento: contenedores de flete. Se usa poco, solo para lo importante |

Tipografías: **Big Shoulders Display** (aire industrial de logística) en la opción 2 y **JetBrains Mono** en la 4,
cargadas por Readme Typing SVG.

## Tabla comparativa
| # | Archivo | Estilo | Qué destaca | Animación | Le conviene más a… |
|:-:|---|---|---|:-:|---|
| 1 | [opcion-1.md](opcion-1.md) | Minimalista | Un párrafo claro, tu regla de oro en español e inglés y una tabla de 4 áreas | Ninguna | Clientes de consultoría contable y gerentes que leen rápido |
| 2 | [opcion-2.md](opcion-2.md) | Dinámico: "ruta de carga" | Animación propia: un camión recorre tus 4 frentes de trabajo + texto que se escribe solo | Alta (un solo momento) | Primera impresión fuerte: empresas de logística, startups, reclutadores |
| 3 | [opcion-3.md](opcion-3.md) | Estadísticas: "estado financiero" | Tus estadísticas presentadas como balance, composición y flujo | Baja (datos en vivo) | Reclutadores técnicos. **Solo después de activar las contribuciones privadas** (abajo) |
| 4 | [opcion-4.md](opcion-4.md) | Terminal: "script de conciliación" | Tu perfil como un script de Python real + gráfico de contribuciones en una terminal | Media (consola que escribe) | Equipos de desarrollo y empresas que buscan Python para logística |
| 5 | [opcion-5.md](opcion-5.md) | Portafolio: "hoja de cálculo" | Encabezado propio con forma de hoja de Excel, tabla de servicios y proyectos desplegables | Ninguna | Quien quiere contratarte: empresas, transportadoras, restaurantes |

## Inspiración en la lista
1. Gift Egwuenu (*Minimalistic*) y Nate Moore (*Simple but Innovative*)
2. DenverCoder1 (*Dynamic Realtime*) + Marton Lederer y Livio Brunner (SVG propios)
3. Anurag Hazra (*Dynamic Realtime*) y Simon Willison (*GitHub Actions*)
4. Thai Braga (*Code Mode*) + herramienta "Github Readme Insight Terminal Ascii" (sección Tools)
5. Martin Heinz (*A Little Bit of Everything*) y Livio Brunner (*Retro*)

## ⚠️ Antes de usar las opciones 3 o 4
Tu perfil público muestra **0 contribuciones en el último año**, porque tu trabajo está en repos privados.
Para que cuenten (sin mostrar el código ni el nombre de los repos):
GitHub → tu foto → **Settings** → **Public profile** → sección *Contributions & activity* → marca
**Include private contributions on my profile** → *Update preferences*. `[VERIFICAR]` el nombre exacto en tu pantalla.

## Servicios verificados (21 oct 2026)
Respondieron con imagen: `skillicons.dev`, `capsule-render.vercel.app`, `readme-typing-svg.demolab.com`,
`github-readme-stats.vercel.app`, `streak-stats.demolab.com`, `github-readme-insight-terminal-asci.vercel.app`, `img.shields.io`.
Las dos imágenes propias están en [`assets/`](../assets) y no dependen de ningún servicio.

**Descartados:**
- `github-profile-trophy` y `github-readme-activity-graph`: su servidor público responde 402 (suspendido).
- `ghchart.rshah.org`: funciona, pero dibuja los días vacíos en blanco y se ve mal en tema oscuro.
- `include_all_commits` de github-readme-stats: falla a ratos en el servidor público.
- Tu README actual usa `github-readme-streak-stats.herokuapp.com`, que ya no existe.

**Mejora opcional para la opción 3:** `github-candles` (licencia MIT, sección Tools de la lista) convierte tus
contribuciones en un gráfico de velas de bolsa. Necesita un workflow de GitHub Actions; lo agrego si eliges esa opción.

## Lo que falta completar
- `[COMPLETAR-correo]`, `[COMPLETAR-URL-LinkedIn]`, `[COMPLETAR-WhatsApp]`
- Otras herramientas exactas (VBA, Power BI, SQL…)
- Descripción y enlace de los proyectos de TMS, nómina y control de horas (opción 5)
- Al copiar la opción 2 o 5 al README principal, la ruta `../assets/` pasa a `assets/` (lo hago yo en el PR).
