## [HU-ENV-INICIALES_XX] Título de la Historia de Usuario

---

### Descripción

<!-- Describe brevemente qué hace este PR y por qué es necesario. -->

---

### HU relacionada

- **ID:** HU-ENV-INICIALES_XX
- **Repositorio del backlog:** [accesorios-dm/docs/HUs/](../accesorios-dm/docs/HUs/)

---

### ADRs aplicados

- [ ] ADR-008 — Versionamiento de APIs (`/api/v1/`)
- [ ] ADR-009 — Formato estándar de errores

---

### Tipo de cambio

- [ ] `feat` — Nueva funcionalidad
- [ ] `fix` — Corrección de bug
- [ ] `refactor` — Refactorización
- [ ] `chore` — Configuración / dependencias
- [ ] `docs` — Documentación
- [ ] `test` — Tests
- [ ] `ci` — Pipeline CI/CD

---

### Criterios de aceptación completados

- [ ] ...
- [ ] ...

---

### Checklist técnico — Payment Service

- [ ] El código no contiene secretos, credenciales ni valores hardcodeados.
- [ ] Las rutas siguen el prefijo `/api/v1/` (ADR-008).
- [ ] Los errores devueltos cumplen el formato estándar definido en ADR-009.
- [ ] Solo se accede a los schemas `ventas` y `logistica`.
- [ ] Si se modificó `prisma/schema.prisma`, se ejecutó `npx prisma generate`.
- [ ] Los valores monetarios usan `Decimal`, no `number` ni `float`.
- [ ] Las transiciones de estado del carrito/pedido respetan la máquina de estados.
- [ ] El archivo `.env.example` fue actualizado si se agregaron nuevas variables.
- [ ] El servicio levanta correctamente con `docker-compose up`.

---

### Checklist de Definición de Done

- [ ] Los criterios de aceptación de la HU están cumplidos.
- [ ] El CI pasa (validate-branch-flow + build si aplica).
- [ ] El reviewer aprobó el PR.
- [ ] La rama `HU-*` será eliminada tras el merge.

---

### Notas al reviewer

<!-- Contexto adicional, decisiones tomadas, áreas de atención especial. -->
