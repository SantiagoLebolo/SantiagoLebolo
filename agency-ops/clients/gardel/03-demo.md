# 03 — Demo (Fase 3)

## Dirección de diseño

Concepto: el nombre del negocio es en sí un anclaje real de marca — Carlos Gardel, el ícono del tango de Buenos Aires de los años 30. En lugar de un genérico "restaurante cálido con acento terracota", la dirección visual se apoya en la elegancia de un café-bar de tango de época: brasso, vinilo, tinta oscura, papel de menú envejecido.

- **UX**: página única (one-page), scroll vertical con ritmo de "libreto de menú": Hero → Historia/Concepto → Menú destacado → Reseñas → Fotografía (placeholder consciente) → Ubicación/CTA de reserva → Footer de contacto.
- **UI**: fondo oscuro dominante tipo salón de tango en penumbra, secciones separadas por filetes finos color latón (no tarjetas con sombra genéricas). Menú tipografiado como carta real, no como galería de fotos.
- **Colores** (paleta con 5 tokens con base real: vino Malbec argentino, latón de vitrola/art-decó, papel envejecido):
  - `--ink` #1B1512 — fondo principal
  - `--ink-2` #241C17 — fondo secundario (alterna secciones)
  - `--paper` #F1E6D2 — texto principal / acentos claros
  - `--malbec` #7A2036 — acento primario (vino tinto)
  - `--brass` #C6A253 — acento secundario (latón, filetes, detalles)
  - `--verdigris` #5C7A6B — acento terciario (verde herbáceo, para variar del cliché vino+terracota)
- **Tipografía**:
  - Display: "Abril Fatface" (afiche vintage, uso solo en wordmark y titulares grandes)
  - Editorial/citas: "Cormorant Garamond" itálica (subtítulos, reseñas)
  - Cuerpo/UI: "Work Sans"
- **Estructura**: 7 secciones (ver UX). Sin tarjetas genéricas; el menú se tipografía como carta real con precios reales de la investigación.
- **Fotografías**: no se cuenta con fotos reales verificadas del negocio en esta sesión. Se usan **ilustraciones de línea en latón** (copa de vino, empanada, parrilla, rama de olivo) como marcador consciente, con nota explícita "Ilustraciones provisionales — pendiente sesión de fotografía profesional (Fase 6)". No se simulan fotos reales.
- **CTA**: "Reservar" enlaza al sitio real (pvdgardel.com) y a Instagram — no se inventa un sistema de reservas nuevo. No se incluye el teléfono no confirmado (ver `00-intake.md`) hasta que el negocio lo confirme.
- **Animaciones**: mínimas y con propósito — aparición suave de secciones al hacer scroll, respetando `prefers-reduced-motion`. Sin efectos decorativos excesivos.
- **Responsive**: una columna en mobile (~400px), menú y reseñas se apilan; probado en el propio artifact.

## Estado de construcción

- [x] Sitio construido (demo, no producción)
- [x] URL del demo: ver `04-deployment.md`
- [ ] Autorización del usuario para publicar como sitio real: pendiente — esto es un demo privado de presentación, no el sitio en vivo del negocio.
