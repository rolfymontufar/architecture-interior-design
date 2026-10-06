---
name: architecture-interior-design
description: Medidas, áreas mínimas y recomendadas, y holguras para arquitectura e interiorismo residencial según normativas latinoamericanas, europeas y de Londres (dormitorios, salas, comedores, cocinas, baños, pasillos, puertas, escaleras, mobiliario). Room sizes, minimum and recommended areas, and clearances for residential architecture and interior design under Latin American, European and London building codes (bedrooms, living and dining rooms, kitchens, bathrooms, hallways, doors, stairs, furniture). Usar cuando / Use when: cuánto mide, medidas de, espacio mínimo, distribución, planta, room size, minimum dimensions, floor plan, layout, clearance, building code.
---

# Arquitectura e Interiorismo / Architecture & Interior Design

Skill bilingüe (español / English) para dimensionar y evaluar espacios
residenciales con valores **mínimos**, **recomendados** y **holgados**, y
comparar requisitos normativos de **Latinoamérica**, **Europa** y **Londres**.

Bilingual skill (Spanish / English) to size and evaluate residential spaces
with **minimum**, **recommended** and **generous** values, and to compare
regulatory requirements across **Latin America**, **Europe** and **London**.

## Idioma / Language

- Responder en el idioma del usuario. / Reply in the user's language.
- Las referencias son bilingües: usar el término del idioma de la respuesta.
  / References are bilingual: use the term matching the reply language.
- Glosario de términos técnicos / Technical glossary: `references/glosario.md`.

## Cuándo usar / When to use

| Español | English |
|---|---|
| "¿Cuánto debe medir un dormitorio principal?" | "How big should a master bedroom be?" |
| "¿Cabe un comedor para 6 en 3 x 3.5 m?" | "Does a 6-seat dining table fit in 3 x 3.5 m?" |
| "¿Qué ancho mínimo exige la norma de Chile para un pasillo?" | "What is the minimum hallway width in Spain's code?" |
| "Revisa esta distribución de baño." | "Review this bathroom layout." |
| "¿Cuánto espacio dejo entre sofá y mesa de centro?" | "How much space between sofa and coffee table?" |

## Convenciones / Conventions

- **Unidades / Units:** métrico (m, cm, m²). Convertir a imperial solo si se
  pide. / Metric by default; convert to imperial only on request.
- **Medidas / Dimensions:** ancho x largo, medidas interiores libres (sin muros).
  / Width x length, clear interior dimensions (excluding walls).
- **Niveles / Levels:**
  - **Mínimo / Minimum:** funcional pero ajustado; suele ser el mínimo legal.
    / Functional but tight; usually the legal minimum.
  - **Recomendado / Recommended:** confortable para uso diario. / Comfortable for daily use.
  - **Holgado / Generous:** amplio, gama media-alta. / Spacious, mid-to-high end.
- **Normativa / Codes:** la norma local siempre prevalece. Usar solo el marco
  normativo elegido en el paso 0. / Local code always prevails. Use only the
  regulatory framework chosen in step 0.

## Paso 0: Elegir normativa / Step 0: Choose the regulatory framework

**Antes de responder la primera pregunta, preguntar al usuario qué normativa
usar**, en su idioma. / **Before answering the first question, ask the user
which regulations to use**, in their language.

- Español: "¿Qué normativa quieres que use: **latinoamericana**, **europea** o
  **de Londres**?"
- English: "Which regulations should I use: **Latin American**, **European** or
  **London**?"

Reglas / Rules:
- Usar la herramienta de preguntas si existe (p. ej. AskUserQuestion); si no,
  preguntar en texto y esperar la respuesta. / Use a question tool if available
  (e.g. AskUserQuestion); otherwise ask in plain text and wait for the reply.
- Si el usuario ya nombró un país o ciudad, no repetir la pregunta: deducir el
  marco y confirmarlo en una línea al inicio de la respuesta (p. ej. "Uso la
  normativa europea: CTE, Madrid."). / If the user already named a country or
  city, do not ask again: infer the framework and confirm it in one line at the
  top of the reply.
- Preguntar una sola vez por conversación; mantener la elección hasta que el
  usuario la cambie. / Ask once per conversation; keep the choice until the user
  changes it.
- Si elige Latinoamérica o Europa sin país, preguntar el país o ciudad; si no
  lo sabe, dar la tabla comparativa de esa región. / If they pick Latin America
  or Europe with no country, ask for the country or city; if unknown, give that
  region's comparison table.

| Elección / Choice | Archivo de normativa / Code file | Filas de las tablas por país / Country table rows |
|---|---|---|
| Latinoamericana / Latin American | `references/normativa/latinoamerica.md` | Solo LatAm / LatAm only |
| Europea / European | `references/normativa/europa.md` | Solo Europa / Europe only |
| Londres / London | `references/normativa/londres.md` (+ Reino Unido en `europa.md`) | Solo UK, con los valores de Londres por encima / UK only, London values override |

- No mezclar normas de otra región salvo que el usuario pida comparar. /
  Do not mix in other regions' codes unless the user asks to compare.
- Los valores de diseño (mínimo, recomendado, holgado) se dan siempre; la
  normativa elegida solo define el mínimo legal citado. / Design values are always
  given; the chosen framework only defines the legal minimum cited.

## Flujo de trabajo / Workflow

0. **Normativa / Framework:** ver paso 0. / See step 0.
1. **Contexto / Context:** tipo de espacio, usuarios, país o ciudad, nivel de
   acabado, accesibilidad. / Space type, occupants, country or city, finish
   level, accessibility needs.
2. **Cargar solo lo necesario / Load only what's needed** (ver índice / see index).
3. **Responder con la tabla de tres niveles** más el lado mínimo libre, no solo
   el área. / **Answer with the three-level table** plus minimum clear side,
   not area alone.
4. **Mínimo legal / Legal minimum:** añadir el mínimo de la normativa elegida
   (tabla por país al final del archivo, o `londres.md`) y citar la norma. /
   Add the minimum from the chosen framework (country table at the end of the
   file, or `londres.md`) and cite the code.
5. **Validar mobiliario y circulación** con `mobiliario.md` y `circulacion.md`.
   / **Check furniture and circulation** with `mobiliario.md` and `circulacion.md`.
6. **Señalar problemas y proponer ajustes** con medidas concretas. / **Flag
   issues and propose fixes** with concrete dimensions.

## Índice / Index

| Archivo / File | Contenido / Contents |
|---|---|
| `references/conceptos.md` | Conceptos base: programa, zonificación, proporción, modulación, planos / Core concepts: program, zoning, proportion, modules, plans |
| `references/interiorismo.md` | Principios, color, iluminación, alturas de instalación, alfombras, materiales / Principles, color, lighting, mounting heights, rugs, materials |
| `references/dormitorios.md` | Dormitorios, vestidor, clóset / Bedrooms, walk-in closet, wardrobe |
| `references/sala-comedor.md` | Sala, comedor, estudio / Living, dining, home office |
| `references/cocina.md` | Cocinas, despensa, lavandería / Kitchens, pantry, laundry |
| `references/banos.md` | Baños y aparatos sanitarios / Bathrooms and fixtures |
| `references/circulacion.md` | Pasillos, puertas, escaleras, rampas / Hallways, doors, stairs, ramps |
| `references/mobiliario.md` | Muebles y holguras / Furniture and clearances |
| `references/ergonomia.md` | Alturas, alcance, antropometría / Heights, reach, anthropometrics |
| `references/accesibilidad.md` | Accesibilidad universal / Universal accessibility |
| `references/confort-ambiental.md` | Techo, luz, ventilación / Ceiling height, daylight, ventilation |
| `references/normativa/latinoamerica.md` | Normas por país de Latinoamérica / Latin American codes by country |
| `references/normativa/europa.md` | Normas por país de Europa (incluye Reino Unido) / European codes by country (incl. UK) |
| `references/normativa/londres.md` | London Plan y estándares de vivienda de Londres / London Plan and London housing standards |
| `references/glosario.md` | Glosario ES-EN / ES-EN glossary |

Archivos de espacio (dormitorios, sala-comedor, cocina, baños, circulación,
accesibilidad, confort ambiental): **resumen rápido** al inicio y tabla
**mínimos normativos por país** (LatAm y Europa, con norma y artículo) al final.
Ir a `normativa/` solo para el detalle. / Space files open with a **quick
reference** and end with a **regulatory minimums by country** table (LatAm and
Europe, with code and article). Use `normativa/` only for full detail.

## Formato de respuesta / Response format

```
**Dormitorio principal / Master bedroom**
| Nivel / Level           | Medidas / Size (m) | Área / Area (m²) | Lado mín. / Min. side (m) |
|-------------------------|--------------------|------------------|---------------------------|
| Mínimo / Minimum        | ...                | ...              | ...                       |
| Recomendado / Recommended | ...              | ...              | ...                       |
| Holgado / Generous      | ...                | ...              | ...                       |

Norma / Code: <país / country>, <norma / regulation>: <mínimo / minimum>
Notas / Notes: holguras clave, errores comunes. / key clearances, common mistakes.
```

Revisión de plantas / Plan review: por espacio, estado **OK / Ajustado (Tight) /
No cumple (Fails)**, medida actual, medida esperada, corrección propuesta.

## Reglas / Rules

- No inventar valores normativos. Si un dato no está en las referencias,
  decirlo y dar una regla práctica marcada como tal. / Never invent code
  values. If data is missing, say so and give a rule of thumb labeled as such.
- Priorizar lado mínimo y holgura de uso sobre área total. / Prioritize
  minimum side and use clearance over total area.
- Considerar apertura de puertas y ventanas. / Account for door and window swings.
- Indicar la fecha o versión de la norma citada. / State the version or date
  of any cited code.
- Marcadores de confianza / Confidence markers: **(fs)** fuente secundaria /
  secondary source; **(av)** a verificar / to verify; **n/r** no regulado / not
  regulated; **?** no encontrado / not found; **RP** regla práctica / rule of
  thumb. Si el valor usado tiene (fs) o (av), avisar al usuario que lo confirme
  con la norma oficial. / If a value carries (fs) or (av), tell the user to
  confirm it against the official code.
- Usar el archivo canónico de cada métrica (otros archivos apuntan a él). /
  Use each metric's canonical file (other files point to it).
- Población latinoamericana es más baja que la europea o estadounidense: ajustar
  alturas de repisas, mostradores y alcance (ver `ergonomia.md`). / Latin American
  users are shorter than European or US users: adjust shelf, counter and reach
  heights (see `ergonomia.md`).
