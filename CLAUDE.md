---
type: tool
domain: infra
summary: Repositorio especial de GitHub para la organización arigroup. Contiene únicamente el perfil público de la organización (profile/README.md), que es desplegado automáticamente por GitHub en la página principal de la organización github.com/arigroup.
tags:
  - github
  - org-profile
  - readme
  - infra
---

# .github — Perfil de Organización GitHub

Este repositorio es el repositorio especial `.github` de la organización **arigroup** en GitHub. Su único propósito es exponer el perfil público de la organización a través del archivo `profile/README.md`.

## Estructura

```
profile/
  README.md   # Perfil público de la organización (visible en github.com/arigroup)
```

## Contenido del perfil

El `profile/README.md` presenta a la empresa **Ari** con:
- Canales de contacto: teléfono, WhatsApp, correo de ventas (`hola@somosari.com`) y soporte (`ayuda@somosari.com`).
- Redes sociales: Instagram y Facebook bajo el handle `@somosarilatam`.

## Notas

- No contiene workflows reutilizables, templates de issues/PRs, ni código ejecutable.
- Cualquier archivo colocado aquí en el futuro (p. ej. `.github/workflows/`) aplicaría configuraciones por defecto a toda la organización.
