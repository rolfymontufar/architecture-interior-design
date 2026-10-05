---
name: architecture-interior-design
description: Medidas, áreas mínimas y recomendadas, y holguras para arquitectura e interiorismo residencial según normativas latinoamericanas y europeas (dormitorios, salas, comedores, cocinas, baños, pasillos, puertas, escaleras, mobiliario). Room sizes, minimum and recommended areas, and clearances for residential architecture and interior design under Latin American and European building codes (bedrooms, living and dining rooms, kitchens, bathrooms, hallways, doors, stairs, furniture). Usar cuando / Use when: cuánto mide, medidas de, espacio mínimo, distribución, planta, room size, minimum dimensions, floor plan, layout, clearance, building code.
---

# Arquitectura e Interiorismo / Architecture & Interior Design

Skill bilingüe (español / English) para dimensionar y evaluar espacios
residenciales con valores **mínimos**, **recomendados** y **holgados**, y
comparar requisitos normativos de **Latinoamérica** y **Europa**.

Bilingual skill (Spanish / English) to size and evaluate residential spaces
with **minimum**, **recommended** and **generous** values, and to compare
regulatory requirements across **Latin America** and **Europe**.

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
- **Normativa / Codes:** la norma local siempre prevalece. Si el usuario indica
  país o ciudad, usar `references/normativa/`. / Local code always prevails.
  If the user gives a country or city, use `references/normativa/`.

## Flujo de trabajo / Workflow

1. **Contexto / Context:** tipo de espacio, usuarios, país o ciudad, nivel de
   acabado, accesibilidad. / Space type, occupants, country or city, finish
   level, accessibility needs.
2. **Cargar solo lo necesario / Load only what's needed** (ver índice / see index).
3. **Responder con la tabla de tres niveles** más el lado mínimo libre, no solo
   el área. / **Answer with the three-level table** plus minimum clear side,
   not area alone.
4. **Si hay país:** añadir el mínimo normativo (tabla por país al final del
   archivo) y citar la norma. / **If a country is given:** add the regulatory
   minimum (country table at the end of the file) and cite the code.
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
| `references/normativa/europa.md` | Normas por país de Europa / European codes by country |
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
