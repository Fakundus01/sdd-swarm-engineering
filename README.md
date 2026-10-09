# SDD Swarm Engineering

Una sola página (`index.html`, sin build) que explica cómo el [SDD Universal](https://github.com/Fakundus01/sdd-universal) dejó de ser solo spec-driven development: los conectores (Docker, uv, Serena MCP, GitHub MCP, CodeGraph MCP, Cerebro MCP), cómo corre una tarjeta en el loop (worktree → implementer → reviewer con mutantes → handback), y tres corridas reales a escala chica, mediana y grande — con sus números, no hipotéticas.

Prueba piloto: esta página la armó el propio swarm, con datos verificados en vivo (versiones de Docker/uv/Serena, conectores respondiendo) y citas reales sacadas con `mcp__cerebro__buscar`.

Para verla: abrí `index.html` en cualquier navegador, o activá GitHub Pages en **Settings → Pages → Deploy from branch (main, /)**.

## Los tres pilotos citados adentro

- **Chico** — [`estudio-raiz-landing`](https://github.com/Fakundus01/estudio-raiz-landing): modo LITE, un solo agente.
- **Mediano** — `sdd-universal`, rama `v0.37-plan`: loop corto de 2 tarjetas en worktrees paralelos.
- **Grande** — `sdd-universal`, loop `obsidian-cerebro` (v0.36): 10 tarjetas, swarm completo.
