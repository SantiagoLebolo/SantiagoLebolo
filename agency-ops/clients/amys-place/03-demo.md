# 03 — Demo (Fase 3)

## Dirección de diseño

Concepto: diner de desayuno de barrio con 26 años de historia, conocido por el pan "bolo" portugués (herencia real de la comunidad portuguesa de Rhode Island) y por el sándwich "Hash it Out". La dirección se aleja del salón oscuro de Gardel — acá es luz de mañana, formica, letrero de neón de esquina, menú escrito a mano.

- **UX**: página única, con foco en resolver el problema real detectado en la auditoría (esperas largas los fines de semana) — el CTA de "Pedir para llevar" va arriba de todo, no escondido al final.
- **UI**: fondo claro tipo luz de mañana, bloques de color sólido estilo letrero de diner, sin sombras genéricas.
- **Colores** (anclados en la estética real de diner americano + herencia portuguesa, distinta a la paleta de Gardel):
  - `--cream` #FBF3E7 — fondo principal
  - `--butter` #F4E3B2 — fondo secundario (alterna secciones)
  - `--cherry` #C6432B — acento primario (rojo cereza de letrero de diner)
  - `--teal` #2E6E62 — acento secundario (verde azulado de formica clásica)
  - `--ink` #2B231C — texto principal
- **Tipografía**:
  - Display: "Bungee" (letrero, bloque, remite a neón de esquina — uso solo en wordmark/titulares)
  - Editorial/citas: "Libre Baskerville" itálica (subtítulos, reseñas)
  - Cuerpo/UI: "Work Sans"
- **Estructura**: Hero (con CTA de pedido anticipado arriba) → Por qué la fila vale la pena (historia + producto insignia) → Menú destacado → Reseñas → Fotografía (marcador) → Ubicación/horario → Footer.
- **Fotografías**: no hay banco de fotos verificado en esta sesión (Instagram tiene 941 posts pero no se inspeccionaron). Se usan íconos de línea (sándwich, pan bolo, taza de café, smoothie) marcados como provisionales, igual criterio que con Gardel.
- **CTA**: "Pedir para llevar" enlaza al sistema real de pedidos (Toast, order.toasttab.com/online/amysprovidence) — no se simula un sistema nuevo. CTA secundario a Instagram.
- **Animaciones**: mínimas, con `prefers-reduced-motion` respetado.
- **Responsive**: una columna en mobile, mismo criterio que el demo de Gardel.

## Estado de construcción

- [x] Sitio construido (demo, no producción)
- [x] URL del demo: ver `04-deployment.md`
- [ ] Autorización del usuario para publicar como sitio real: pendiente — demo privado de presentación.
