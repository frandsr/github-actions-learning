# Mission: GitHub Actions (CI/CD)

## Why
Quiero ganar fluidez real con CI/CD usando GitHub Actions: poder leer, escribir y debuggear workflows con soltura, y poder decir con honestidad "sé hacer CI/CD con GitHub Actions". Es el área que menos domino y la quiero sacar de mi lista de puntos ciegos.

## Success looks like
- Leer un workflow ajeno y explicar qué evento lo dispara, qué jobs corre y qué hace cada step.
- Escribir desde cero un workflow de CI para un proyecto Node/TypeScript (instalar deps, lint, tests) que corra en cada push y PR.
- Debuggear un workflow que falla: leer los logs, ubicar el step roto y arreglarlo.
- Construir y publicar artefactos: una imagen Docker y/o un paquete (npm) desde un workflow.

## Constraints
- Soy desarrollador; CI/CD y automatización es lo que menos domino.
- Aprendo CONCEPTO PRIMERO, después práctica: el modelo mental antes del YAML.
- Lecciones cortas, cada una con UNA victoria tangible.
- Objetivo: fluidez para el trabajo real, NO una certificación.
- Las lecciones deben leerse desde el celular (publicadas en GitHub Pages) con los quizzes funcionando.

## Stack
- Node / TypeScript (principal).
- Docker / contenedores (interés, nivel inicial).
- Destino a futuro: publicar paquetes/artefactos (npm, releases, imágenes).

## Out of scope (por ahora)
- Certificación oficial.
- Self-hosted runners avanzados, matrices complejas, monorepos gigantes.
- Deploy a clouds específicas (AWS/GCP/Azure) — se verá más adelante si la misión lo pide.
