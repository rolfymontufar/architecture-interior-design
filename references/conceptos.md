# Conceptos Fundamentales / Core Concepts

> Mapa de lo mínimo que hay que saber para dimensionar y evaluar espacios. / Map of the minimum knowledge needed to size and evaluate spaces.
> Estado / Status: v1 (A3 a A8, A16, A17, A19 completos / complete). Fuentes al final / Sources at bottom.

## Resumen rápido / Quick reference

- **Área útil vs. construida / Net vs. gross:** útil ≈ 75-85 % de la construida; restar 15-25 % a la cifra de anuncio.
- **Circulación / Circulation:** 10-15 % del área útil (regla práctica; ver `circulacion.md`).
- **Chequeo de programa / Program check:** construida ≈ Σ netas x (1 + % circulación) x (1 + % muros).
- **Proporción / Proportion:** 1:1.25 a 1:1.5 ideal; 1:2 límite práctico; > 1:2 efecto pasillo. Ubicación canónica / Canonical location: A8.
- **Lado mínimo / Min. side:** mueble principal + holguras a ambos lados; manda sobre el área.
- **Medida libre / Clear dimension:** a ejes − ½ muro por lado − acabados (ejes 3.00, muros 15 → 2.82 libre).
- **Muros / Walls:** yeso laminado 7.3-10; bloque 12-18; exterior 15-35.
- **Módulos / Modules:** M = 10 cm; cocina 60; placa de yeso 122 x 244 (Américas), 120 x 250-300 (Europa).
- **Escalas / Scales:** 1:100 plantas; 1:50 amueblado; 1:20-1:25 cocinas y baños.

## A. Arquitectura / Architecture

| # | Concepto / Concept | Qué es / What it is | Archivo / File |
|---|---|---|---|
| A1 | Antropometría / Anthropometrics | Medidas del cuerpo humano (percentiles 5 y 95) / Human body measurements (5th and 95th percentiles) | ergonomia.md |
| A2 | Ergonomía / Ergonomics | Relación cuerpo-mueble-espacio / Body-furniture-space fit | ergonomia.md |
| A3 | Programa arquitectónico / Architectural program | Lista de espacios, usuarios y áreas / List of spaces, users, areas | conceptos.md |
| A4 | Zonificación / Zoning | Zona social, privada, servicio / Social, private, service zones | conceptos.md |
| A5 | Diagrama de relaciones / Adjacency diagram | Qué espacio conecta con cuál / Which space connects to which | conceptos.md |
| A6 | Área útil vs. construida / Net vs. gross area | Interior libre vs. con muros / Clear interior vs. including walls | conceptos.md |
| A7 | Medida libre vs. a ejes / Clear vs. centerline dimension | Paramento a paramento vs. eje de muro / Face to face vs. wall axis | conceptos.md |
| A8 | Proporción del espacio / Room proportion | Relación ancho:largo funcional / Usable width:length ratio | conceptos.md |
| A9 | Circulación / Circulation | Pasillos, flujos, % de área / Hallways, flows, % of area | circulacion.md |
| A10 | Holguras / Clearances | Espacio de uso alrededor de muebles / Use space around furniture | mobiliario.md |
| A11 | Puertas y ventanas / Doors and windows | Anchos, alturas, abatimiento, antepecho / Widths, heights, swing, sill | circulacion.md |
| A12 | Escaleras / Stairs | Huella, contrahuella, Blondel, descansos / Tread, riser, landings | circulacion.md |
| A13 | Altura de techo / Ceiling height | Mínimos y recomendados / Minimum and recommended | confort-ambiental.md |
| A14 | Iluminación y ventilación natural / Daylight and ventilation | Relación ventana/piso, orientación / Window-to-floor ratio, orientation | confort-ambiental.md |
| A15 | Accesibilidad universal / Universal design | Silla de ruedas, giro 150 cm / Wheelchair, 150 cm turning circle | accesibilidad.md |
| A16 | Modulación / Modular coordination | Módulos de materiales y muebles / Material and cabinet modules | conceptos.md |
| A17 | Lectura de planos / Reading plans | Escala, cotas, simbología / Scale, dimensions, symbols | conceptos.md |
| A18 | Normativa / Building codes | Mínimos legales por país o ciudad / Legal minimums by country or city | normativa/ |
| A19 | Núcleo húmedo / Wet core | Agrupar baños, cocina y lavandería / Grouping bathrooms, kitchen, laundry | conceptos.md |

## B. Interiorismo / Interior Design

| # | Concepto / Concept | Qué es / What it is | Archivo / File |
|---|---|---|---|
| B1 | Principios de diseño / Design principles | Equilibrio, ritmo, énfasis, escala, proporción, unidad / Balance, rhythm, emphasis, scale, proportion, unity | interiorismo.md |
| B2 | Color | Regla 60-30-10, círculo cromático, temperatura / 60-30-10 rule, color wheel, temperature | interiorismo.md |
| B3 | Iluminación por capas / Layered lighting | Ambiental, de tarea, de acento; lux; Kelvin; CRI / Ambient, task, accent | interiorismo.md |
| B4 | Distribución de mobiliario / Furniture layout | Punto focal, zonas de conversación / Focal point, conversation areas | interiorismo.md |
| B5 | Alturas de instalación / Mounting heights | Cuadros, lámparas, espejos, cortinas, TV / Art, pendants, mirrors, curtains, TV | interiorismo.md |
| B6 | Tamaños de alfombras / Rug sizing | Según sala, comedor, dormitorio / By room type | interiorismo.md |
| B7 | Materiales y acabados / Materials and finishes | Pisos, muros, uso según zona húmeda o seca / Floors, walls, wet vs. dry areas | interiorismo.md |
| B8 | Textura, patrón y estilo / Texture, pattern, style | Combinación y estilos principales / Mixing and main styles | interiorismo.md |
| B9 | Acústica básica / Basic acoustics | Absorción, aislamiento / Absorption, insulation | interiorismo.md |

## A3. Programa arquitectónico / Architectural program

- Definición / Definition: lista de espacios necesarios con usuarios, actividades, mobiliario, área y relaciones; base de todo diseño. / List of required spaces with users, activities, furniture, area and relationships; the basis of any design.
- Pasos / Steps:
  1. Usuarios: número, edades, movilidad, rutinas. / Users: count, ages, mobility, routines.
  2. Actividades por espacio. / Activities per space.
  3. Mobiliario y equipo (ver `mobiliario.md`). / Furniture and equipment.
  4. Área neta por espacio = mueble + holguras (nivel mín./rec./holgado). / Net area per space = furniture + clearances.
  5. Sumar áreas netas, añadir circulación y muros (ver A6). / Sum net areas, add circulation and walls.
  6. Comparar con terreno y norma (COS/CUS, retiros). / Check against lot and code (coverage, FAR, setbacks).

| Columna / Column | Contenido / Content | Ejemplo / Example |
|---|---|---|
| Espacio / Space | Nombre / Name | Dormitorio principal / Master bedroom |
| Zona / Zone | Social, privada, servicio / Social, private, service | Privada / Private |
| Usuarios / Users | Cantidad, perfil / Count, profile | 2 adultos / 2 adults |
| Actividades / Activities | Qué se hace / What happens | Dormir, vestirse / Sleep, dress |
| Mobiliario / Furniture | Lista con medidas / List with sizes | Cama 160x200, 2 burós / Bed 160x200, 2 nightstands |
| Área neta / Net area (m²) | Por nivel / Per level | Ver / See `dormitorios.md` |
| Lado mín. / Min. side (m) | Lado libre mínimo / Minimum clear side | Ver / See `dormitorios.md` |
| Relaciones / Adjacencies | Directa, deseable, evitar / Direct, desirable, avoid | Directa: baño principal / Direct: en-suite |
| Requisitos / Requirements | Luz, vista, privacidad, instalaciones / Light, view, privacy, services | Luz este / East light |

- Fórmula de chequeo / Check formula: Área construida ≈ Σ áreas netas × (1 + % circulación) × (1 + % muros). Regla práctica / Rule of thumb; % en A6.

## A4. Zonificación / Zoning

| Zona / Zone | Espacios / Spaces | Carácter / Character | Ubicación típica / Typical location |
|---|---|---|---|
| Social / Social | Recibidor, sala, comedor, estudio de visitas, terraza, medio baño / Foyer, living, dining, guest study, terrace, powder room | Pública, ruido tolerable / Public, noise tolerated | Cerca del acceso, planta baja, mejor vista y sol / Near entrance, ground floor, best view and sun |
| Privada / Private | Dormitorios, baños completos, vestidor, estudio privado / Bedrooms, full baths, walk-in closet, private study | Silenciosa, aislada / Quiet, isolated | Lejos de calle y acceso; planta alta o ala propia / Away from street and entrance; upper floor or own wing |
| Servicio / Service | Cocina, despensa, lavandería, patio de servicio, cuarto de servicio, garaje, bodega / Kitchen, pantry, laundry, service yard, staff room, garage, storage | Funcional, ruido y olores / Functional, noise and odors | Junto a acceso secundario y garaje; fachada menos valiosa / Next to secondary entrance and garage; least valuable facade |

- Reglas / Rules:
  - La cocina es bisagra entre social y servicio. / The kitchen hinges the social and service zones.
  - Circulación privada no debe cruzar la zona social si se puede evitar. / Private circulation should not cross the social zone where avoidable.
  - Visitas no deben ver dormitorios ni lavandería desde el acceso. / Guests should not see bedrooms or laundry from the entrance.
  - Agrupar zonas húmedas (ver A19). / Group wet areas (see A19).

### Orientación / Orientation (Regla práctica / Rule of thumb, OLG)

| Hemisferio / Hemisphere | Fachada de sol invernal / Winter-sun facade | Uso sugerido / Suggested use |
|---|---|---|
| Norte (MX, GT, CO, ES) / Northern | Sur / South | Sala, comedor, estar / Living, dining, family room |
| Sur (AR, CL, sur de BR) / Southern | Norte / North | Sala, comedor, estar / Living, dining, family room |
| Ambos / Both | Este / East | Dormitorios, desayunador (sol de mañana) / Bedrooms, breakfast nook (morning sun) |
| Ambos / Both | Oeste / West | Evitar dormitorios; usar garaje, bodega, baños como colchón térmico; proteger con aleros o celosías / Avoid bedrooms; use garage, storage, baths as thermal buffer; shade with overhangs or screens |
| Ambos / Both | Polo (N en hemisferio sur, S en norte) / Pole-facing | Servicio, escaleras, estudio con luz difusa / Service, stairs, study with diffuse light |

- Trópico (GT, CO, sur de MX): sol casi cenital; prioridad = sombra, ventilación cruzada y proteger poniente. / Tropics: near-overhead sun; priority = shade, cross ventilation, protect west.
- Detalle de asoleamiento y ventilación en `confort-ambiental.md`. / Sun and ventilation details in `confort-ambiental.md`.

## A5. Diagrama de relaciones / Adjacency diagram

- Niveles / Levels: **Directa** (puerta o espacio continuo) / **Direct** (door or open plan); **Deseable** (cercana, 1 paso por circulación) / **Desirable** (near, via circulation); **Indiferente** / **Neutral**; **Evitar** (separar visual o acústicamente) / **Avoid** (separate visually or acoustically).
- Herramientas / Tools: matriz de relaciones (triangular) y diagrama de burbujas. / Relationship matrix (triangular) and bubble diagram.

| Espacio A / Space A | Espacio B / Space B | Relación / Relationship | Motivo / Reason |
|---|---|---|---|
| Acceso / Entrance | Recibidor / Foyer | Directa / Direct | Transición, guardarropa / Transition, coat storage |
| Recibidor / Foyer | Sala / Living | Directa / Direct | Recibir visitas / Receive guests |
| Sala / Living | Comedor / Dining | Directa o deseable / Direct or desirable | Uso social continuo / Continuous social use |
| Comedor / Dining | Cocina / Kitchen | Directa / Direct | Servir y recoger / Serve and clear |
| Cocina / Kitchen | Despensa / Pantry | Directa / Direct | Almacenamiento / Storage |
| Cocina / Kitchen | Garaje o acceso de servicio / Garage or service entrance | Deseable / Desirable | Descarga de compras / Unloading groceries |
| Cocina / Kitchen | Lavandería / Laundry | Deseable / Desirable | Núcleo húmedo, servicio / Wet core, service |
| Cocina / Kitchen | Dormitorios / Bedrooms | Evitar / Avoid | Ruido, olores / Noise, odors |
| Medio baño / Powder room | Zona social / Social zone | Deseable / Desirable | Visitas sin entrar a zona privada / Guests stay out of private zone |
| Medio baño / Powder room | Comedor, cocina / Dining, kitchen | Evitar puerta enfrentada / Avoid facing door | Higiene, vista / Hygiene, sightline |
| Dormitorio principal / Master bedroom | Baño principal, vestidor / En-suite, walk-in closet | Directa / Direct | Privacidad / Privacy |
| Dormitorios / Bedrooms | Baño compartido / Shared bath | Deseable (por pasillo) / Desirable (via hallway) | Sin cruzar zona social / Without crossing social zone |
| Dormitorios / Bedrooms | Sala, TV, garaje / Living, TV, garage | Evitar muro común / Avoid shared wall | Ruido / Noise |
| Sala, comedor / Living, dining | Terraza, jardín / Terrace, garden | Directa / Direct | Extensión exterior / Outdoor extension |
| Lavandería / Laundry | Patio de tendido / Drying yard | Directa / Direct | Secado / Drying |
| Estudio / Study | Acceso / Entrance | Deseable si recibe clientes / Desirable if clients visit | Separar de zona privada / Separate from private zone |

## A6. Área útil vs. construida / Net vs. gross area

| Término / Term | Definición / Definition | Fuente / Source |
|---|---|---|
| Área útil / Net (usable) area | Superficie pisable dentro de muros; excluye muros, pilares, ductos / Walkable floor inside walls; excludes walls, columns, shafts | OCU, ARQ |
| Área construida / Gross area | Dentro del perímetro exterior de muros de fachada; incluye muros interiores y la mitad de medianeros (criterio ES) / Within outer face of facade walls; includes interior walls and half of party walls (ES criterion) | OCU |
| Área construida con comunes / Gross incl. common areas | Construida + parte proporcional de zonas comunes (ES) / Gross + share of common areas | ARQ |
| Altura < 1,50 m / Height < 1.50 m | No computa como útil en vivienda protegida (ES) (a verificar en norma local / to verify locally) | ARQ |

| Parámetro / Parameter | Valor típico / Typical value | Nota / Note | Fuente / Source |
|---|---|---|---|
| Diferencia útil vs. construida / Net-to-gross gap | 15 a 25 % | Vivienda; depende del espesor de muros / Housing; depends on wall thickness | ARQ |
| Eficiencia útil/construida / Net-to-gross ratio | 0,75 a 0,85 | Regla práctica / Rule of thumb (inversa de la fila anterior / inverse of row above) | ARQ |
| Circulación en vivienda / Circulation in housing | 10 a 15 % del área neta / of net area | Regla práctica; > 20 % = planta ineficiente. Ubicación canónica: `circulacion.md` / Rule of thumb; canonical: `circulacion.md` | NEUF (a verificar / to verify) |
| Muro divisorio yeso laminado / Drywall partition | 7,3 a 10 cm | Montante 48 o 70 mm + 1 placa 12,5 mm por lado / 48 or 70 mm stud + one 12.5 mm board per side | PLC |
| Muro divisorio bloque / Block partition | 12 a 18 cm | Bloque 10 a 15 cm + repello 1,5 cm por lado / Block 10 to 15 cm + 1.5 cm plaster per side | GCC; Regla práctica / Rule of thumb |
| Muro exterior bloque o ladrillo / Exterior masonry wall | 15 a 35 cm | LatAm cálida ~15-20 cm; ES con aislante ~25-35 cm / Warm LatAm ~15-20 cm; Spain with insulation ~25-35 cm | (a verificar / to verify) |

- Usar siempre área útil y lado libre para evaluar habitabilidad; la norma suele exigir medidas libres. / Always use net area and clear side to judge habitability; codes usually require clear dimensions.
- En anuncios inmobiliarios se da área construida: restar 15-25 % para estimar útil. / Listings give gross area: subtract 15-25 % to estimate net.

## A7. Medida libre vs. a ejes / Clear vs. centerline dimension

| Tipo / Type | Se mide / Measured | Uso / Use |
|---|---|---|
| Libre (luz libre, paramento a paramento) / Clear (face to face) | Entre caras terminadas de muros / Between finished wall faces | Habitabilidad, muebles, norma / Habitability, furniture, codes |
| A ejes / Centerline (axis to axis) | Entre ejes de muros o columnas / Between wall or column axes | Estructura, replanteo, modulación / Structure, setting out, grid |
| Nominal / Nominal | Pieza + junta / Unit + joint | Coordinación modular / Modular coordination |

- Fórmula / Formula: libre = a ejes − (e₁/2 + e₂/2) − acabados. / clear = centerline − (t₁/2 + t₂/2) − finishes.
- Ejemplo / Example: ejes 3,00 m, muros 15 cm, repello 1,5 cm por cara: 3,00 − 0,15 − 0,03 = **2,82 m libre / clear**.
- Error común / Common mistake: dibujar habitación de "3 x 3 m" a ejes y obtener 2,82 x 2,82 m libres; un clóset o cama puede dejar de caber. / Drawing a "3 x 3 m" room to centerlines yields 2.82 x 2.82 m clear; a wardrobe or bed may no longer fit.
- Columnas y ductos reducen el lado libre localmente: verificar en el punto más estrecho. / Columns and shafts reduce clear width locally: check at the narrowest point.

## A8. Proporción del espacio / Room proportion

| Relación ancho:largo / Width:length | Efecto / Effect | Uso / Use | Fuente / Source |
|---|---|---|---|
| 1:1 | Estática; esquinas difíciles de amueblar si es grande / Static; corners hard to furnish if large | Comedor redondo, vestíbulo / Round-table dining, foyer | Regla práctica / Rule of thumb |
| 1:1,25 a 1:1,5 | Más versátil para amueblar / Most versatile to furnish | Dormitorio, sala, comedor / Bedroom, living, dining | Regla práctica / Rule of thumb |
| 1:1,618 (áurea / golden) | Proporción clásica armónica / Classic harmonic ratio | Referencia compositiva / Compositional reference | NEU |
| 1:2 | Límite práctico; dividir en 2 zonas / Practical limit; split into 2 zones | Sala-comedor, estudio + estar / Living-dining, study + lounge | Regla práctica / Rule of thumb |
| > 1:2 | Efecto pasillo, luz natural no llega al fondo / Corridor effect, daylight does not reach back | Solo galerías, cocinas en paralelo / Only galleries, galley kitchens | Regla práctica / Rule of thumb |

- Lado mínimo manda sobre el área: un espacio de 9 m² en 2,0 x 4,5 m no sirve como dormitorio doble. / Minimum side governs over area: a 9 m² room at 2.0 x 4.5 m does not work as a double bedroom.
- Lado mín. = mueble principal + holguras de uso a ambos lados (ver `mobiliario.md`). / Min. side = main furniture + use clearances on both sides.
- Profundidad de iluminación natural: hasta ~2 a 2,5 veces la altura del dintel desde la ventana (regla práctica; ubicación canónica `confort-ambiental.md`). / Daylight depth: up to ~2 to 2.5 times window-head height (rule of thumb; canonical in `confort-ambiental.md`).
- Altura vs. planta: espacios grandes con techo bajo se perciben opresivos; ver `confort-ambiental.md`. / Large rooms with low ceilings feel oppressive.

## A16. Modulación / Modular coordination

- Módulo base ISO: M = 10 cm; dimensiones preferidas múltiplos de M, 3M (30 cm), 6M (60 cm). / ISO basic module M = 100 mm; preferred multiples M, 3M, 6M. (ISO)
- Diseñar a módulo reduce cortes y desperdicio. / Designing to module reduces cuts and waste.

| Elemento / Element | Medida / Size (cm) | Módulo / Module | Fuente / Source |
|---|---|---|---|
| Gabinete base cocina, ancho / Kitchen base cabinet width | 15, 20, 30, 40, 45, 60, 80, 90 | 60 cm estándar para electrodomésticos / 60 cm standard for appliances | IKE, NKB |
| Gabinete base, fondo / Base cabinet depth | 60 (cubierta 60 a 65 / countertop 60 to 65) | | IKE |
| Gabinete base, altura / Base cabinet height | 80 + patas 8 = 88 (sin cubierta / without top) | Cubierta terminada ~90 / Finished counter ~90 | IKE |
| Gabinete alto, fondo / Wall cabinet depth | ~37 a 39 | | IKE |
| Placa de yeso / Gypsum board (Américas) | 122 x 244 (4 x 8 ft); también / also 122 x 305 | Montantes a 40,6 o 61 cm / Studs at 16 or 24 in | ASTM C1396 (a verificar / to verify) |
| Placa de yeso / Gypsum board (Europa) | 120 x 200 a 300; espesor 12,5 mm | Montantes a 40 o 60 cm / Studs at 40 or 60 cm | PLC |
| Tablero contrachapado, MDF / Plywood, MDF | 122 x 244 | | Regla práctica / Rule of thumb (estándar comercial / trade standard) |
| Bloque de concreto MX / Concrete block MX | 10, 12, 15, 20 x 20 x 40 (nominal) | Hiladas de 20 cm, largos múltiplos de 20 / 20 cm courses, lengths in 20 cm multiples | GCC |
| Bloque de concreto EE. UU. / CMU US | 8 x 8 x 16 in nominal (19,4 x 19,4 x 39,7 cm real / actual) | Junta 3/8 in | ANG |
| Bloque de concreto GT / Concrete block GT | 14 x 19 x 39 (real) | Nominal 15 x 20 x 40 | (a verificar / to verify) |
| Ladrillo macizo/perforado ES / Brick ES | 24 x 11,5 x 5 (métrico) | Con junta 25 x 12,5 / With joint 25 x 12.5 | COAM (histórico 25 x 12 x 5) |
| Tabique rojo recocido MX / Fired clay brick MX | ~7 x 14 x 28 | Artesanal, variable / Handmade, variable | (a verificar / to verify) |
| Placa de cielo falso / Ceiling tile (Europa, LatAm) | 59,5 x 59,5 en retícula 60 x 60; también 60 x 120 | | JUD |
| Placa de cielo falso / Ceiling tile (EE. UU.) | 2 x 2 ft (61 x 61), 2 x 4 ft (61 x 122) | | JUD |
| Porcelanato / Porcelain tile | 30 x 60, 60 x 60, 60 x 120, 120 x 120 | Medida real ~0,5 a 1 cm menor según fabricante / Actual may be smaller | Regla práctica / Rule of thumb |

- Ajustar largo de cocina a múltiplos de 60 (más rellenos de 5 a 10 cm en esquinas). / Fit kitchen runs to 60 cm multiples (plus 5 to 10 cm fillers at corners).
- Alinear juntas de piso con eje de puerta o muro principal; cortes ≥ 1/2 pieza en bordes visibles. Regla práctica / Rule of thumb. / Align floor joints with door axis or main wall; cuts ≥ half a tile at visible edges.

## A17. Lectura de planos / Reading plans

### Escalas / Scales (ISO 5455)

| Escala / Scale | 1 cm en papel = / 1 cm on paper = | Uso típico / Typical use |
|---|---|---|
| 1:500, 1:200 | 5 m, 2 m | Conjunto, terreno / Site plan |
| 1:100 | 1 m | Plantas generales, cortes, fachadas / General plans, sections, elevations |
| 1:50 | 50 cm | Plantas amuebladas, anteproyecto interior / Furnished plans, interior design |
| 1:25, 1:20 | 25 cm, 20 cm | Cocinas, baños, clósets, alzados interiores / Kitchens, baths, closets, interior elevations |
| 1:10, 1:5, 1:1 | 10 cm, 5 cm, 1 cm | Detalles constructivos y de mobiliario / Construction and joinery details |

- Escala gráfica obligatoria si el plano se imprime o escala digitalmente. / Graphic scale needed if printed or scaled digitally.
- No medir con regla un plano sin verificar la escala impresa contra una cota conocida. / Never scale a drawing without checking against a known dimension.

### Cotas / Dimensions

| Tipo / Type | Descripción / Description |
|---|---|
| Cota parcial / Partial dimension | Entre elementos consecutivos (muro, vano, muro) / Between consecutive elements |
| Cota total / Overall dimension | Exterior a exterior / Outside to outside |
| Cota a ejes / Grid dimension | Entre ejes estructurales (letras y números en círculos) / Between structural grid lines |
| Cota de nivel / Level mark | N.P.T. (nivel de piso terminado / finished floor level) +0,00; N.T.N. (terreno natural / natural grade) |
| Unidades / Units | LatAm y ES: m con 2 decimales o cm; Europa técnica: mm. Ver nota del plano / Check the drawing note |
| Vano de ventana / Window opening | Ancho x alto y altura de antepecho (sill) / Width x height and sill height |

- Las cotas escritas mandan sobre lo medido en el dibujo. / Written dimensions govern over scaled ones.

### Simbología común / Common symbols

| Símbolo / Symbol | Significado / Meaning |
|---|---|
| Línea gruesa / Thick line | Elemento cortado (muro) / Cut element (wall) |
| Línea fina / Thin line | Elemento en vista bajo el plano de corte (muebles, piso) / Element seen below the cut plane |
| Línea discontinua / Dashed line | Elemento sobre el plano de corte u oculto (vigas, gabinetes altos, dobles alturas) / Element above cut plane or hidden (beams, wall cabinets, voids) |
| Plano de corte en planta / Plan cut plane | ~1,00 a 1,50 m sobre el piso (Regla práctica / Rule of thumb, convención usual) |
| Puerta abatible / Hinged door | Hoja como línea + arco de 90° que muestra el barrido / Leaf line + 90° arc showing swing |
| Puerta doble, vaivén / Double, swing door | Dos hojas con arcos; vaivén con arcos a ambos lados / Two leaves; double-acting shows arcs both sides |
| Puerta corrediza / Sliding door | Hoja paralela al muro con flecha / Leaf parallel to wall with arrow |
| Ventana / Window | 2 a 3 líneas finas dentro del muro; corrediza con hojas desfasadas / 2 to 3 thin lines in the wall; sliding with offset sashes |
| Escalera / Stairs | Flecha con "sube/baja" (UP/DN) y línea de corte diagonal / Arrow with "up/down" and diagonal break line |
| Flecha norte / North arrow | Indica norte; necesaria para orientación y asoleamiento / Shows north; needed for orientation and sun |
| Corte / Section mark | Línea con flechas y letra (A-A') que indica dirección de vista / Line with arrows and letter showing view direction |
| Eje / Grid line | Línea de trazo y punto con círculo y letra o número / Dash-dot line with bubble |

- Mano de puerta / Door handing: convenciones distintas (EE. UU. se ve desde el exterior, DIN desde el lado de apertura). Siempre confirmar con el dibujo del arco. / Conventions differ (US viewed from outside, DIN from opening side). Always confirm with the drawn arc. (a verificar por país / to verify per country)
- Verificar en planta: barrido de puertas libre de muebles, choque entre hojas, apertura hacia pasillo. / Check on plan: door swings clear of furniture, leaves not colliding, swing into hallway.

## A19. Núcleo húmedo / Wet core

- Agrupar baños, cocina y lavandería alrededor de pocas bajantes: reduce tubería, costo y fugas. / Group bathrooms, kitchen and laundry around few stacks: less piping, cost and leaks.
- En 2 plantas, apilar baños verticalmente. / In two-storey houses, stack bathrooms vertically.
- Distancia inodoro a bajante: mantener corta por pendiente del drenaje (≥ 1-2 %, ver norma local; a verificar / to verify). / Keep toilet-to-stack runs short due to drain slope.
- Ducto de instalaciones / Service shaft: prever 30 a 60 cm de ancho para bajantes y ventilación (Regla práctica / Rule of thumb, a verificar / to verify).

## Fuentes / Sources

- **ANG**: Angelus Block Co., "CMU Basics: Dimensions and Sizes" (ASTM C90). https://angelusblock.com/resources/cmu-basics/dimensions-and-sizes/
- **ARQ**: Arquitasa, "Diferencia entre superficie útil y construida". https://arquitasa.com/diferencia-superficie-util-construida
- **NEUF**: Neufert y práctica profesional común (reglas prácticas de circulación). / Neufert and common practice.
- **COAM**: Revista Nacional de Arquitectura n.º 80 (1948), normalización del ladrillo (Orden 13-05-1942). https://www.coam.org
- **GCC**: GCC, Ficha técnica Bloque de Concreto Estándar (MX). https://www.gcc.com/wp-content/uploads/2020/08/FTBCES0817-Bloque-Concreto-Estandar-1.pdf
- **IKE**: IKEA, sistema de cocina METOD (fichas de producto). https://www.ikea.com
- **ISO**: ISO 21723 / ISO 1006, coordinación modular (módulo M = 100 mm); ISO 5455, escalas de dibujo técnico; ISO 128, convenciones de líneas.
- **JUD**: Judge Ceilings, "Ceiling tiles by size". https://judge-ceilings.co.uk/ceiling-tiles-by-size
- **NEU**: Neufert, E., *Arte de proyectar en arquitectura* / *Architects' Data* (proporciones, sección áurea).
- **NKB**: NKBA, *Kitchen & Bath Planning Guidelines with Access Standards*.
- **OCU**: OCU, "Superficies construidas y útiles". https://www.ocu.org/fincas-y-casas/gestion/urbanismo-y-construccion/analisis/2020/09/superficie-util
- **OLG**: Olgyay, V., *Design with Climate* / *Arquitectura y clima* (orientación bioclimática).
- **PLC**: Placo (Saint-Gobain) España, fichas técnicas de placa 12,5 mm x 1200 mm (EN 520). https://www.placo.es
