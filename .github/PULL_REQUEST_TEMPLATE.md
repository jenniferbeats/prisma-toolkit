**Para qué:**
<!-- Resumen conciso (1-3 líneas). Por qué existe este cambio y qué problema resuelve. -->

Closes #
<!-- Opciones de trazabilidad según contract/protocols/git.md:
- Closes #N (o Fixes #N, Resolves #N, Relates to #N, Parte de #N)
- **Sin issue:** <razón explícita de por qué no requiere issue>
-->

## Tipo de cambio
- [ ] `feat`: Nueva funcionalidad o capacidad
- [ ] `fix`: Corrección de bug o comportamiento inesperado
- [ ] `docs`: Documentación o notas de arquitectura
- [ ] `refactor`: Limpieza o reestructuración sin cambio funcional
- [ ] `test`: Nuevas pruebas o ajuste de suites existentes
- [ ] `chore` / `ci`: Mantenimiento, dependencias o flujos de integración

## Lista de verificación
- [ ] **Pruebas en verde:** Pasaron localmente y en el pipeline de CI.
- [ ] **Complejidad y estilo:** Pasa linter (`ruff check` / `eslint`) y cumple umbrales de complejidad.
- [ ] **Seguridad y secretos:** Cero credenciales, claves API o datos privados en el diff.
- [ ] **Convención de commits:** Título del PR sigue Conventional Commits (`tipo(scope): descripción`).

<!-- En commits de agentes, incluir los tráilers requeridos:
Assisted-by: NOMBRE_AGENTE:MODELO
Host: HOSTNAME
-->
