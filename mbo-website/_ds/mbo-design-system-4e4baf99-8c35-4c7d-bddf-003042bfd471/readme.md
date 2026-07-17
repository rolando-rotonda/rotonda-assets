# MBO — Muebles Bonilla · Interiorismo Comercial

## Contexto de la empresa
**MBO** son las iniciales de **Muebles Bonilla**. La empresa se especializa en **interiorismo comercial** — diseño, fabricación e instalación de mobiliario y espacios para contextos comerciales: oficinas, showrooms, puntos de venta, hoteles, restaurantes y espacios gastronómicos.

**Slogan principal:** *Interiorismo Comercial*
**Slogan alternativo:** *Desde el origen*
**Nombre completo en sellos:** *Muebles Bonilla · Interiorismo Comercial*

**Fuentes:** Manual de identidad MBO (texto, 12 págs. Illustrator 1920×1080) + archivos de logotipo en JPG (18 archivos adjuntos).

---

## Content Fundamentals

- **Tono:** Cálido pero profesional. Artesanal + técnico. Confianza en el oficio.
- **Voz:** Directa. Habla de materiales, espacios, proyectos — no de abstracciones.
- **Idioma principal:** Español (mercado México)
- **Capitalización:** ALL CAPS en labels y slogans (siguiendo el logo); Sentence case en body.
- **Emoji:** Nunca — la marca es formal y artesanal
- **Copy:** Concreto. "Diseñamos el mobiliario de tu espacio" > "Generamos soluciones integrales"
- **Taglines frecuentes:** "Desde el origen" · "Interiorismo Comercial"

---

## Visual Foundations

### Colores
Paleta de cuatro colores con jerarquía estricta. **Nunca usar blanco puro como fondo.**

| Nombre | Hex | Rol |
|--------|-----|-----|
| Lámina Clara | `#EAEAE1` | Fondo primario. Base neutra. Sustituye al blanco. |
| Acero Verde | `#3B5452` | Color principal. Eje rector. Estructuras, fondos de sección. |
| Grafito Modular | `#003045` | Profundidad, autoridad. Fondos oscuros, textos sobre claro. |
| Madera Terra | `#93775B` | Acento cálido. Slogans, detalles, secundarios. |

### Logotipo
El logotipo de MBO está construido con **formas geométricas orgánicas y redondeadas**: la M con dos arcos, la B con protuberancias redondeadas, la O como círculo perfecto. Es un diseño gráfico propio — no tipografía.

**Variantes disponibles (ver `assets/`):**
- `logo-dark.jpg` — MBO oscuro (Grafito) + "INTERIORISMO COMERCIAL" en Madera Terra. Fondo blanco.
- `logo-light.jpg` — MBO en Lámina Clara + "INTERIORISMO COMERCIAL" en Madera Terra. Fondo blanco.
- `logo-clara.jpg` — MBO en Lámina Clara + Madera Terra. Variante suave.
- `logo-desdeorigen-dark.jpg` — MBO + "DESDE EL ORIGEN"
- `logo-fullname-dark.jpg` — MBO + "MBO INTERIORISMO COMERCIAL"
- `logo-fullname-desdeorigen-dark.jpg` — MBO + "MBO DESDE EL ORIGEN"
- `logo-gradient.jpg` — Versión degradado
- `sello-grafito.jpg` — Sello circular Muebles Bonilla · Interiorismo Comercial (Grafito)
- `sello-verde.jpg` — Sello circular (Acero Verde)
- `sello-gradient.jpg` — Sello circular degradado
- `symbol-terra.jpg` — Símbolo aislado en Madera Terra (motivo hoja/pluma)
- `symbol-light.jpg` — Símbolo aislado en Lámina Clara

⚠️ **Todos los logos están en JPG con fondo blanco.** Usar `logo-dark.jpg` solo sobre Lámina Clara (donde el fondo blanco se vuelve invisible). Para fondos oscuros, pedir SVG con fondo transparente.

### Símbolo
El símbolo es un **motivo de hoja/pluma** compuesto por capas curvas superpuestas — evoca materiales naturales y el oficio artesanal. Se usa en sellos y aplicaciones donde el logotipo completo no cabe.

### Tipografía
- **GT Flexa Mono** (Light 300, Medium 500) — Display / labels / slogans. Todo en mayúsculas, espaciado amplio. **Archivos OTF incluidos en `assets/fonts/`.**
- **Inter Variable** — Cuerpo de texto, descripciones, UI. Archivo variable TTF incluido en `assets/fonts/`.

### Espaciado
Grid base de 8px. Padding de sección: 80px H, 80px V. Espaciado generoso.

### Forma
El logo usa formas orgánicas y redondeadas. En componentes UI, mantener un estilo limpio y minimalista. `border-radius: 0` para elementos estructurales; se permiten radios mayores en elementos gráficos decorativos que complementen el espíritu orgánico del logo.

### Fondos
- Principal: Lámina Clara. Nunca blanco puro.
- Oscuro: Acero Verde o Grafito Modular.
- Patrón geométrico con colores oficiales. No incluir símbolo dentro del patrón.
- Degradado: como fondo/textura. Construido sobre tonos de la identidad.

### Animación
Sutil. Fade lento. Nada brusco. `250ms ease`.

---

## Iconografía
No hay sistema de íconos especificado. Para UI: Lucide Icons (trazo fino). El símbolo MBO (hoja/pluma) funciona como ícono de marca en contextos reducidos.

---

## Estrategia de marca (El Mapa)

El documento "El Mapa" define el posicionamiento completo de MBO. Puntos clave:

- **Centro:** MBO = Interiorismo Comercial. Saca a la empresa del terreno de la carpintería genérica.
- **Diferencia:** Resolver desde el origen. 40 años de experiencia en plazas, lineamientos, fabricación e instalación.
- **Clientes:** Corporativo (principal) → Emprendedor comercial → Residencial (complementario).
- **Tagline principal:** "Desde el origen" — habla del origen histórico, del proyecto y del oficio.
- **Firma:** MBO · Interiorismo Comercial (por Muebles Bonilla en transición).
- **Desde:** 1993 · Monterrey, México.

### Taglines activos de campaña
- *Para abrir bien. Desde el origen.* — Apertura / principal
- *Del plano a la plaza. Bien armado.* — Ejecución
- *Tu punto de venta, bien orquestado.* — Resultado
- *Un espacio abierto a nuevas formas.* — Apertura / evolución

### Pitch corto
> MBO desarrolla interiorismo comercial para marcas, plazas y negocios que necesitan resolver bien su punto de venta desde el origen. Diseñamos, fabricamos e instalamos islas, vitrinas, exhibidores, locales y mobiliario comercial con oficio, criterio y experiencia real en operación de plazas.

---

## Índice de archivos

| Ruta | Descripción |
|------|-------------|
| `Canvas.dc.html` | Design system browser — índice visual completo |
| `styles.css` | Entrada principal de tokens |
| `tokens/` | Colors, typography, spacing, effects |
| `guidelines/` | Especímenes: color, tipo, espacio, logos, patrón, estrategia, mensajería, masters |
| `components/core/` | Button, Card, Badge, Input, Divider |
| `ui_kits/website/` | Landing page MBO Interiorismo Comercial |
| `ui_kits/presentation/` | Deck corporativo MBO — 8 slides |
| `assets/` | Logos, sellos, símbolo |
| `assets/masters/` | 4 piezas editoriales de campaña (PNG) |

---

## Notas de producción
- ✅ GT Flexa Mono integrado con archivos OTF con licencia. Stack: `'GT Flexa Mono', 'IBM Plex Mono', monospace`.
- ✅ Inter integrado como fuente variable (cubre todos los pesos con un solo archivo).
- Logos disponibles en JPG (fondo blanco). Solicitar SVG con fondo transparente para aplicaciones sobre fondos oscuros.
- Colores Pantone: Lámina Clara = 5757 C · Acero Verde = 560 C (89%) · Grafito = 303 C · Madera Terra = 7504 C.
