# Notes — preferencias y working notes

## Cómo enseña el usuario quiere aprender
- **Concepto primero, práctica después.** Explicar el modelo mental antes de mostrar YAML. No abrir con sintaxis.
- **Lecciones cortas, una victoria tangible cada una.** Nada de lecciones maratónicas.
- **Citar docs oficiales dentro de cada lección.** No confiar en conocimiento paramétrico; linkear a docs.github.com.
- **Idioma: español** (rioplatense ok).
- **Objetivo es fluidez de trabajo real**, no certificación. Priorizar leer/escribir/debuggear workflows reales.

## Publicación (requisito duro)
- Las lecciones se publican en **GitHub Pages** para leerlas desde el celular con quizzes funcionando.
- Cada lección es un HTML autocontenido (CSS + JS inline) — sin dependencias externas, así funciona offline/mobile.
- Para actualizar el sitio: `git push` y listo (Pages re-despliega desde `main`).

## Estado de publicación
- **Repo:** https://github.com/frandsr/github-actions-learning (público, cuenta personal `frandsr`).
- **Sitio (Pages):** https://frandsr.github.io/github-actions-learning/ — verificado HTTP 200.
- **Cuenta:** personal `frandsr` (NO la laboral `fdesautu-mundi`). La activa en `gh` ya es la personal.
- **Actualizar el sitio:** `git push` a `main` → Pages re-despliega solo (branch=main, path=/).
- El commit usó email francisco.desauturiestra@mundi.io; si querés un email personal en los commits, avisame y lo cambio.

## Stack para ejemplos
- Node/TypeScript como default en los ejemplos.
- Docker cuando aplique (interés del usuario, nivel inicial).
