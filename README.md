# P10 - GitHub Actions: variables de contexto

Práctica 10 de Tecnologías de Servicios para Ciencia de Datos (ULPGC).

- `.github/workflows/p10-contextos.yml`: workflow principal. Usa los contextos
  `github`, `env`, `vars`, `inputs`, `job`, `steps`, `runner`, `secrets`,
  `strategy`, `matrix` y `needs`.
- `.github/workflows/p10-reutilizable.yml`: workflow reutilizable que usa el
  contexto `jobs` para exponer sus salidas.

Lanzamiento manual: pestaña **Actions** > *P10 - Contextos de GitHub Actions* >
**Run workflow** (entradas `entorno`, `ejecutar_pruebas`, `etiqueta`).

Ejecución de prueba del evento `pull_request` (rama `prueba-pr`).
