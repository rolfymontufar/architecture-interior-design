---
name: architecture-interior-design
description: Residential room sizes, clearances, furniture, ergonomics and legal minimums (Latin America, Europe, London). Medidas de dormitorios, salas, comedores, cocinas, baños, pasillos, escaleras y normativa. Use for room size, floor plan review, layout, clearance, building code, cuánto mide, espacio mínimo, distribución.
---

# Architecture & Interior Design

Reply in the user's language (Spanish or English). Data files are in English;
translate terms using `references/glossary.md` (includes regional variants).

## Step 0: choose regulations (once per conversation)

Before the first answer, ask in the user's language (use a question tool if
available, else plain text and wait):
- ES: "¿Qué normativa quieres que use: **latinoamericana**, **europea** o **de Londres**?"
- EN: "Which regulations should I use: **Latin American**, **European** or **London**?"

- If the user already named a country or city, skip the question and state the
  framework in one line (e.g. "Uso la normativa europea: CTE, Madrid.").
- Latin American or European with no country: ask for country or city; if
  unknown, use that region's `_overview.md`.
- Cite only the chosen framework unless the user asks to compare.

| Choice | Load |
|---|---|
| Latin American | `references/codes/latam/<jurisdiction>.md` (or `_overview.md`) |
| European | `references/codes/europe/<jurisdiction>.md` (or `_overview.md`) |
| London | `references/codes/london.md` (+ `codes/europe/uk.md` for national rules) |

Jurisdictions: latam: guatemala, cdmx, bogota, buenos-aires, chile, peru,
costa-rica, quito, other. europe: spain-cte, madrid, catalonia, uk, france,
germany, italy, portugal, netherlands, eu.

## How to read files (token budget)

1. Every file starts with a **Quick reference** in its first ~25 lines. Read
   only those lines first (e.g. Read with limit 25).
2. If the answer is not there, Grep for the section or keyword and read only
   that part. Read a whole file only for full plan reviews.
3. Load at most the topic file(s) needed plus one jurisdiction file.
4. `references/sources.md` holds full citations: open it only if the user asks
   for a source.

## Topic files (`references/`)

| File | Contents |
|---|---|
| `bedrooms.md` | Bedrooms, closets, bed clearances |
| `living-dining.md` | Living, dining, home office, TV distances |
| `kitchen.md` | Layouts, work triangle, heights, aisles, laundry |
| `bathrooms.md` | Bath types, fixture clearances, mounting heights |
| `circulation.md` | Halls, doors, windows, stairs, ramps |
| `furniture.md` | Furniture sizes (US/EU) and use clearances |
| `ergonomics.md` | Work heights, reach, anthropometrics (LatAm/US/EU) |
| `accessibility.md` | Wheelchair, accessible doors, bath, kitchen |
| `environmental-comfort.md` | Ceiling height, daylight, ventilation, lux |
| `concepts.md` | Program, zoning, adjacencies, net/gross, proportion, modules, plans |
| `interior-design.md` | Principles, color, lighting, mounting heights, rugs, materials |

## Answer

- Size questions: table with **Minimum / Recommended / Generous**: size (m),
  area (m²), minimum side (m). Then the legal minimum from the chosen
  jurisdiction with code and article. Then key clearances and common mistakes.
- Plan reviews: per space, status OK / Tight / Fails, current vs expected
  value, concrete fix. Describe layouts by wall with dimensions; do not draw
  ASCII plans unless asked.
- Metric by default; imperial only on request. Clear interior dimensions.

## Rules

- Never invent code values. If missing, say so and give a rule of thumb (RT).
- Markers: (fs) secondary source, (av) to verify, RT rule of thumb, CALC
  calculated, n/r not regulated, ? not found. If a cited value has (fs) or
  (av), tell the user to confirm it in the official code.
- Minimum side and use clearance matter more than total area. Check door and
  window swings.
- Latin American users are shorter than US/EU users: adjust shelf, counter and
  reach heights (`ergonomics.md`).
- State the code version or date. This skill is a guide, not a substitute for
  the current code or a licensed professional.
