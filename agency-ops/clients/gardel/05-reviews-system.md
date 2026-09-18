# 05 — Sistema de Reviews (Fase 5)

## Flujo definido

Flujo de una sola pantalla, sin ramificar por sentimiento (evita "review gating", prohibido por las políticas de Google): a **todos** los comensales se les ofrecen las mismas dos opciones, con el mismo peso visual.

1. Al cerrar la cuenta, la mesa tiene un tarjetón con QR → escanea → abre la landing page.
2. La landing ofrece, una al lado de la otra:
   - **"Dejar reseña en Google"** — enlace directo al perfil de Google del negocio.
   - **"Escribirnos directo"** — mailto a gardel.pvd@gmail.com, para quien prefiere feedback privado (positivo o negativo).
3. Ninguna opción se oculta ni se prioriza según si la experiencia fue buena o mala — ambas están siempre visibles.

## Código QR

La landing page (ver abajo) genera su propio QR en el navegador, apuntando a su propia URL — así el mismo QR impreso en las mesas sirve sin depender de un generador externo. Incluye una vista de impresión (`@media print`) pensada para imprimir el tarjetón de mesa.

## Landing page

Publicada (privada, para revisión): **https://claude.ai/artifact/587eM8CuJtiUp25qywFUdA**

## CTA

- Primario: "★ Dejar reseña en Google" — actualmente enlaza a la ficha del negocio en Google Maps (búsqueda por dirección), porque **no tengo el enlace corto oficial de reseña** (`g.page/r/...`). Ese enlace lo genera automáticamente Google desde el propio Google Business Profile verificado del negocio (botón "Pedir reseñas" / "Compartir perfil"). **Pendiente: que el dueño del negocio lo genere y me lo pase para reemplazar el enlace actual por el directo.**
- Secundario: "Escribirnos directo" — mailto real a gardel.pvd@gmail.com.

## Seguimiento

- No hay integración automatizada con el email o POS de Gardel desde esta sesión (no tengo acceso a esas cuentas). El seguimiento por ahora es un proceso manual sugerido:
  1. El staff entrega el tarjetón con QR al cerrar la mesa.
  2. Reseñas nuevas en Google se revisan semanalmente y se responden (el negocio ya tiene este hábito, según lo visto en Fase 1 — solo se formaliza la cadencia).
  3. Los mensajes que lleguen por el mailto se derivan a quien gestione gardel.pvd@gmail.com.
- Si más adelante se autoriza acceso al Google Business Profile o al email del negocio, se puede automatizar el paso 2-3.

## Integración con Google

- Parcial: el CTA principal ya apunta al perfil real de Google del negocio.
- Completa: requiere el enlace corto de reseña generado desde el GBP verificado (ver arriba) — no se puede fabricar ni adivinar ese enlace.

> No se inventan ni falsifican reviews o testimonios bajo ninguna circunstancia. No se implementa "review gating" (mostrar la opción de reseña pública solo a quienes tuvieron buena experiencia) — viola las políticas de Google y es contrario a las reglas de esta agencia.
