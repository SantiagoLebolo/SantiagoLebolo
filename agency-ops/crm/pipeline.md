# CRM — Pipeline de Prospectos y Clientes

Antes de agregar un nuevo negocio, busca por nombre o website en esta tabla para evitar duplicados. Si ya existe, actualiza su fila en lugar de crear una nueva.

| Negocio | Ciudad | Website | Contacto | Etapa | Última actualización | Notas |
|---|---|---|---|---|---|---|
| _(sin registros todavía)_ | | | | | | |

## Etapas válidas

`NEW LEAD → AUDIT → DEMO → CONTACTED → MEETING → PROPOSAL → WON → ONBOARDING → ACTIVE CLIENT → COMPLETED`

## Notas de uso

- Una fila por negocio. No duplicar.
- El campo "Última actualización" se actualiza cada vez que cambia la etapa.
- El detalle de cada fase vive en `../clients/<nombre-del-negocio>/`, no en esta tabla.
