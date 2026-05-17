# Aceptación de Carga — PALMERO

App web para la gestión de aceptación de carga de PALMERO.

## Archivo principal

- `aceptacion_carga_palmero.html.html` — app completa en un único archivo HTML (sin framework, sin build).

## Brand system

| Token | Valor |
|---|---|
| `--negro` | `#2C2825` |
| `--naranja` | `#F4552A` |
| `--crema` | `#FAF9F4` |

Fuente: **Mona Sans** (Google Fonts), pesos 200–900, variable width.

## Convenciones de diseño

- Fondo oscuro (`--negro`) con trama institucional PALMERO en diagonal.
- Cards con borde sutil y acento naranja superior al hover.
- Barras de título con forma pill (`border-radius: 4px 20px 20px 4px`) en naranja sólido u outline.
- Header sticky con línea inferior naranja de 3px.
- Todo el texto UI en mayúsculas con `letter-spacing` amplio.

## Notas de desarrollo

- Es una SPA estática — sin servidor, sin dependencias npm.
- Para previsualizar: abrir el HTML directamente en el browser.
- Mantener todo en el archivo único; no fragmentar en módulos externos salvo que se lo indique explícitamente.
