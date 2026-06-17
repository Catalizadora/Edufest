# edufest — Presentación EduFest 2026 (archivo histórico)

## Identity (single source of truth — validar contra código, no memoria)
- Canonical slug: edufest
- GitHub: Catalizadora/Edufest
- Lovable project: N/A
- Supabase ref: N/A   ← single-file HTML estático, sin backend
- Domain(s): N/A
- Hosting: N/A (archivo histórico, presentación ya ejecutada)
- Stack: single-file HTML/CSS/JS (presentación EduFest 2026)


> "Innovar Hoy — Luciana García Agrícola · EduFest 2026". Presentación single-page completada.

## Qué es

Single-file HTML (`index.html`) con la presentación de EduFest 2026. Stack:

- Tipografía: Playfair Display + DM Sans + JetBrains Mono (Google Fonts)
- Paleta oscura: `--bg #0f0630`, gold `#dba13a`, cyan `#38d6d2`, coral `#e8505b`, magenta `#c44bbb`
- Layout fullscreen (`100vh/100vw`, `overflow:hidden`)

El proyecto está completado, ya se presentó en EduFest 2026.

## REGLA OPERATIVA — Archivo histórico

- NO tocar el contenido — es referencia de un evento ya ejecutado.
- Si se necesita reusar el layout o paleta para otra presentación, COPIAR a un repo nuevo (`edufest-2027`, etc.), no editar este.
- Sirve como referencia visual / template para futuras presentaciones similares.

## Memoria (Mem0)

- **Namespace obligatorio**: cuando llames `memory_save` del MCP `mem0`, pasa SIEMPRE:
  - `scope: "project_team"`
  - `project: "edufest"`
- **Antes de `memory_search`**, considera filtrar por `scope: "project_team"` para evitar contaminación con otros proyectos.
