# GitHub Actions Resources

## Knowledge

- [GitHub Docs — Understanding GitHub Actions](https://docs.github.com/en/actions/get-started/understanding-github-actions)
  Fuente primaria. Definiciones oficiales de workflow, event, job, action, runner, step. Usar para: el modelo mental y cualquier definición canónica.
- [GitHub Docs — About workflows](https://docs.github.com/en/actions/concepts/workflows-and-actions/about-workflows)
  Cómo un evento dispara workflows en `.github/workflows`. Usar para: el flujo evento → workflow → jobs → runners → steps.
- [GitHub Docs — Workflow syntax for GitHub Actions](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
  Referencia completa del YAML: `on`, `jobs`, `runs-on`, `steps`, `uses`, `run`. Usar para: sintaxis exacta al escribir workflows.
- [GitHub Docs — Events that trigger workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)
  Catálogo de eventos (`push`, `pull_request`, `schedule`, `workflow_dispatch`, etc.). Usar para: elegir el disparador correcto.
- [GitHub Docs — Building and testing Node.js](https://docs.github.com/en/actions/use-cases-and-examples/building-and-testing/building-and-testing-nodejs)
  Ejemplo oficial de CI para Node/TypeScript. Usar para: la primera lección práctica de CI.

## Wisdom (Communities)

- [GitHub Community Discussions — Actions](https://github.com/orgs/community/discussions/categories/actions-and-packages)
  Foro oficial moderado. Usar para: dudas reales, workflows que rompen, patrones de la comunidad.
- [r/github](https://www.reddit.com/r/github/)
  Subreddit general de GitHub. Usar para: troubleshooting informal y ver cómo otros resuelven CI/CD.
- [Awesome Actions (GitHub)](https://github.com/sdras/awesome-actions)
  Lista curada de actions y recursos. Usar para: descubrir actions reutilizables en vez de reinventar steps.

## Gaps
- Falta una fuente fuerte específica para publicar paquetes npm desde Actions (se buscará al llegar a esa lección).
- Falta recurso sobre buenas prácticas de seguridad con `secrets` y permisos del `GITHUB_TOKEN` (futuro).
