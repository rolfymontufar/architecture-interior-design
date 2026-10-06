# architecture-interior-design

Skill bilingüe de dimensiones para arquitectura e interiorismo residencial,
con normativas de Latinoamérica, Europa y Londres. Al empezar, pregunta qué
normativa usar.

Bilingual skill for residential architecture and interior design dimensions,
covering Latin American, European and London building codes. It first asks
which regulations to use.

## Instalación / Installation

| Herramienta / Tool | Ruta / Path |
|---|---|
| Claude Code (personal) | `~/.claude/skills/architecture-interior-design/` |
| Claude Code (proyecto / project) | `.claude/skills/architecture-interior-design/` |
| Claude.ai | Comprimir en `.zip` y subir en Settings > Capabilities > Skills / Zip and upload in Settings > Capabilities > Skills |
| GitHub Copilot (repo) | `.github/skills/architecture-interior-design/` |
| GitHub Copilot (personal) | `~/.copilot/skills/architecture-interior-design/` |

## Estructura / Structure

```
SKILL.md                         Instrucciones y flujo / Instructions and workflow
references/*.md                  Tablas por espacio / Tables per space type
references/normativa/*.md        Normas LatAm, Europa y Londres / LatAm, European and London codes
references/glosario.md           Glosario ES-EN / ES-EN glossary
SOURCES.md                       Fuentes y brechas por archivo / Sources and gaps per file
METODOLOGIA.md                   Cómo se recolectaron los datos / How the data was collected
```

## Metodología / Methodology

Los datos se recolectaron con agentes de investigación en dos iteraciones
(investigación y verificación) con reglas de fuente y marcadores de confianza.
Ver `METODOLOGIA.md`. / Data was collected by research agents in two
iterations (research and verification) with sourcing rules and confidence
markers. See `METODOLOGIA.md`.

## Licencia / License

MIT. Ver / See `LICENSE`.
