# Metodología de Recolección / Data Collection Methodology

> Cómo se construyó y verificó el contenido de esta skill. / How the content of
> this skill was built and verified.
> Fecha / Date: 4 y 5 de octubre de 2026 / October 4 and 5, 2026.
> Herramienta / Tool: Claude Code (Claude Opus 5.5) con agentes de investigación
> en paralelo y búsqueda web / with parallel research agents and web search.

## 1. Alcance / Scope

| Decisión / Decision | Valor / Value |
|---|---|
| Tipo de proyecto / Project type | Vivienda residencial / Residential housing |
| Idiomas / Languages | Español e inglés en el mismo archivo / Spanish and English in the same file |
| Unidades / Units | Métrico: m, m², holguras en cm / Metric: m, m², clearances in cm |
| Medidas / Dimensions | Interiores libres, ancho x largo / Clear interior, width x length |
| Regiones / Regions | Latinoamérica, Europa y Londres / Latin America, Europe and London |
| Niveles por espacio / Levels per space | Mínimo, Recomendado, Holgado / Minimum, Recommended, Generous |

### Ciudades de referencia / Reference cities

Muchos países regulan por municipio o por región. Se eligió la ciudad principal
como referencia. / Many countries regulate at municipal or regional level. The
main city was chosen as reference.

| País / Country | Referencia / Reference |
|---|---|
| Guatemala | Ciudad de Guatemala (RG-1) + normas FHA |
| México | CDMX (NTC Proyecto Arquitectónico 2024) |
| Colombia | Bogotá (POT, NSR-10) |
| Argentina | Ciudad de Buenos Aires (Código de Edificación, Ley 6100) |
| España / Spain | CTE (nacional / national) + Madrid + Cataluña |
| Chile, Perú, Costa Rica, Reino Unido, Francia, Alemania, Italia, Portugal, Países Bajos | Norma nacional / National code |
| Ecuador | Quito (RTAU) |
| Londres / London | London Plan + Housing Design Standards LPG (agregado / added 2026-10-06) |

## 2. Proceso / Process

| Fase / Phase | Qué se hizo / What was done |
|---|---|
| 0. Esqueleto / Skeleton | Estructura de la skill, plantillas de tablas con columna de fuente / Skill structure, table templates with a source column |
| 1. Mapa de conceptos / Concept map | 28 conceptos mínimos: 19 de arquitectura (A1 a A19) y 9 de interiorismo (B1 a B9), en `references/concepts.md` / 28 core concepts: 19 architecture, 9 interior design |
| 2. Iteración 1 / Iteration 1 | 7 agentes en paralelo, uno por área: conceptos e interiorismo; dormitorios y mobiliario; sala-comedor y ergonomía; cocina y baños; circulación, accesibilidad y confort; normativa LatAm; normativa Europa / 7 parallel agents, one per area |
| 3. Iteración 2 / Iteration 2 | 4 agentes de verificación: revisar cada valor marcado "a verificar" contra fuentes primarias, corregir errores, resolver contradicciones entre archivos, agregar resumen rápido; 1 agente para normas de accesibilidad de LatAm / 4 verification agents plus 1 for LatAm accessibility |
| 4. Integración / Integration | 1 agente llenó las tablas comparativas por país usando solo los datos ya recolectados en `normativa/` (sin nuevas búsquedas) / 1 agent filled per-country tables using only data already in `normativa/` |
| 5. Revisión final / Final review | Sin TODOs pendientes, sin contradicciones conocidas, tamaño de archivos, reglas de confianza en `SKILL.md` / No TODOs, no known conflicts, file sizes, confidence rules |

## 3. Reglas de captura / Capture rules

1. **Nada inventado / Nothing invented:** cada número lleva un ID de fuente; cada
   archivo termina con su lista de fuentes. / Every number has a source ID; each
   file ends with its source list.
2. **Fuentes primarias primero / Primary sources first:** texto oficial de la norma
   (boletines oficiales, PDFs de ministerios, gov.uk, codigotecnico.org,
   Légifrance, BCN Chile, gob.pe), luego normas técnicas (EN, ISO, DIN, NKBA),
   luego fabricantes, luego guías de diseño. / Official code text first, then
   technical standards, then manufacturers, then design guides.
3. **Nivel Mínimo = norma; Recomendado = guía de industria** (NKBA, Neufert,
   London Housing Design Guide). Cuando no hay estándar, el valor se calcula
   (mueble + holguras) y se marca como cálculo o regla práctica. / Minimum = code;
   Recommended = industry guide. When no standard exists, the value is calculated
   and labeled.
4. **Conversión / Conversion:** valores en pulgadas (NKBA, IRC, ADA) convertidos a
   cm. / Inch values converted to cm.
5. **Versión / Version:** se registra el año o versión de cada norma citada. /
   Year or version of each code is recorded.

## 4. Marcadores de confianza / Confidence markers

| Marca / Marker | Significado / Meaning |
|---|---|
| (sin marca / no marker) | Verificado en fuente primaria o técnica / Verified in primary or technical source |
| (fs) / fuente secundaria | Tomado de un resumen, tesis, blog o copia no oficial / From a summary, thesis, blog or unofficial copy |
| (av) / a verificar | No se pudo confirmar / Could not be confirmed |
| RP / Regla práctica | Regla de oficio, no norma / Trade rule of thumb, not code |
| CALC | Calculado: mueble + holguras citadas / Calculated: furniture + cited clearances |
| n/r | La jurisdicción no lo regula / Not regulated |
| ? | No encontrado / Not found |

## 5. Verificación (iteración 2) / Verification (iteration 2)

Ejemplos de correcciones que hizo la verificación. / Examples of corrections
made during verification.

| Tema / Topic | Antes / Before | Después / After |
|---|---|---|
| Altura mínima Chile / Chile ceiling height | 2.35 m | 2.30 m (OGUC, desde Decreto 217 de 2002 / since Decree 217 of 2002) |
| Altura obra nueva Francia / France new-build height | 2.50 m (R.111-2) | Sin mínimo en el CCH actual (R.156-1, 2021) / No minimum in current CCH |
| Separación encimera a alacena (Europa) / Counter to wall cabinet (Europe) | 48 cm | ≥ 45 cm (EN 1116:2018) |
| Peldaños por tramo UK / UK risers per flight | Máx. 16 / Max 16 | Sin límite en vivienda privada; > 36 seguidos exige cambio de dirección / No limit in private dwellings |
| Lux CDMX vivienda / CDMX housing lux | 300 lx | La tabla aplica a edificios no residenciales / Table applies to non-residential only |
| Tolerancia de marco de puerta / Door frame allowance | Hoja + 8 a 10 cm / Leaf + 8 to 10 cm | Hoja + 2.5 cm (DIN 18101) |
| Pasillos Guatemala / Guatemala hallways | Art. 140 vs. 144 en conflicto / in conflict | Art. 140 es recomendado; art. 144 obligatorio (interpretación, av) / Art. 140 recommended, art. 144 mandatory |

Consistencia / Consistency: cuando dos archivos daban valores distintos para la
misma métrica, se eligió un **archivo canónico** y los demás apuntan a él (p. ej.
altura de mostrador en `kitchen.md`, centro de TV en `ergonomics.md`, lux en
`environmental-comfort.md`, barras de apoyo en `accessibility.md`). / When two files
disagreed, one canonical file was chosen and the others point to it.

## 6. Hallazgos relevantes / Key findings

- La población latinoamericana es más baja: mujer P50 155.6 cm (Colombia) vs.
  168.0 cm (Alemania). Ajustar alturas de catálogos de EE. UU. y Europa. /
  Latin American users are shorter; adjust US and European catalog heights.
- Las medidas por local de la RG-1 de Guatemala (art. 140) son recomendaciones,
  no obligaciones. / Guatemala RG-1 room sizes are recommendations.
- Chile (OGUC) y Perú (A.020) no fijan m² por local en vivienda común. / Chile
  and Peru set no per-room areas for ordinary housing.
- En la UE no hay áreas mínimas comunes; cada país o región las fija. / No
  common EU minimum sizes.

## 7. Limitaciones / Limitations

- **Normas de pago / Paywalled standards:** DIN (Alemania), NTC (Colombia), NMX
  (México), ISO 21542, EN 17210: valores de fuentes secundarias o ausentes. /
  Values from secondary sources or missing.
- **Libros / Books:** Neufert y Panero & Zelnik se consultaron solo a través de
  resúmenes secundarios. / Consulted only through secondary summaries.
- **Sitios oficiales caídos / Official sites down:** Municipalidad de Guatemala
  (se usó copia archivada / archived copy used), INVU Costa Rica 2022, portales de
  CABA.
- **Límite de búsquedas / Search limit:** la sesión agotó 200 búsquedas web; la
  parte final usó solo descarga directa de URLs conocidas. / The session used up
  200 web searches; the final part used direct URL fetches only.
- **Interpretaciones / Interpretations:** algunas lecturas de artículos
  contradictorios (Guatemala art. 140/144, NSR-10 escaleras) son interpretación
  propia, marcadas (av). / Some readings of conflicting articles are
  interpretations, marked (av).
- Esta skill es una guía; no sustituye la consulta de la norma vigente ni a un
  profesional habilitado. / This skill is a guide; it does not replace the
  current code or a licensed professional.

## 8. Cómo continuar / How to continue

1. Revisar las brechas por archivo en `SOURCES.md`. / Review per-file gaps in `SOURCES.md`.
2. Buscar valores marcados (fs) o (av); al confirmar en fuente primaria, quitar la
   marca y actualizar la fuente. / Search (fs) or (av) values; on confirmation,
   remove the marker and update the source.
3. Si se agrega un país o ciudad, crear `references/codes/<región>/<jurisdicción>.md`
   con la misma estructura (Quick reference, Rooms, Circulation, Accessibility,
   Comfort, Gaps), agregarlo a `_overview.md` y a la lista de `SKILL.md`. / New
   jurisdiction: create its file with the same structure, add it to
   `_overview.md` and to the list in `SKILL.md`.
4. Mantener las reglas de la sección 3 y los marcadores de la sección 4. / Keep
   the rules in section 3 and markers in section 4.

## 9. Optimización de tokens / Token optimization (2026-10-06)

Objetivo: reducir los tokens que la skill carga por consulta sin perder datos. /
Goal: cut tokens loaded per query without losing data.

| Cambio / Change | Detalle / Detail |
|---|---|
| Datos en inglés / Data in English | Las referencias pasaron de bilingües a solo inglés (el inglés tokeniza mejor). El modelo traduce al responder; `glossary.md` sigue bilingüe con variantes regionales. Esta documentación sigue bilingüe. / References moved from bilingual to English only; glossary stays bilingual. |
| Normativa por jurisdicción / Codes per jurisdiction | `normativa/latinoamerica.md` y `europa.md` se dividieron en un archivo por ciudad o país en `references/codes/`, más un `_overview.md` por región. Las tablas por país de cada archivo de espacio se movieron ahí. / Split into one file per jurisdiction; per-country tables moved there. |
| Fuentes aparte / Sources apart | Las listas de fuentes se movieron a `references/sources.md`; los datos conservan el ID corto. / Source lists moved to one file; data keeps short IDs. |
| Resumen rápido primero / Quick reference first | `SKILL.md` indica leer solo las primeras ~25 líneas, luego buscar la sección, y el archivo completo solo si hace falta. / Read first ~25 lines, then grep, full file only if needed. |
| `SKILL.md` compacto / Compact `SKILL.md` | De 10,921 a ~4,200 caracteres; descripción de 714 a 365. / From 10,921 to ~4,200 chars; description 714 to 365. |

Verificación / Verification: se compararon todos los valores numéricos únicos
del contenido anterior (1,063) contra el nuevo; todos se conservan (uno cambió de
unidad: 0.62 m pasó a 620 mm y 62 cm). / All 1,063 unique numeric values were
checked against the new content; all are preserved.
