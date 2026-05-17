# Proyecto: Aceptación de Carga — Palmero San Luis S.A.

Aplicación web single-file (HTML + CSS + JS vanilla) que reemplaza
una planilla Excel/VBA. Calcula aceptación de carga de generadores.

## Workflow de commits

- Después de cada cambio lógicamente completo, ejecutá automáticamente:
  `git add -A && git commit -m "<mensaje descriptivo>"`
- Usá conventional commits: `feat:`, `fix:`, `style:`, `refactor:`, `docs:`.
- NO hagas `git push` salvo que te lo pida explícitamente.
- Mensajes en español, en presente: "agrega nota de créditos al pie",
  "corrige cálculo de potencia aparente", etc.

## Stack

- Archivo único: `aceptacion_carga_palmero.html`
- Sin build, sin dependencias externas (salvo Google Fonts).
- Branding Palmero ya aplicado: variables CSS en `:root`
  (`--negro`, `--naranja`, `--crema`, tipografía Mona Sans).

## Reglas de estilo

- Mantené las variables de marca; no introduzcas colores hardcodeados.
- Comentarios en español.
- Conservá el patrón `── SECCIÓN ──` en los headers del CSS.