**Para qué:**
<!-- Resumen conciso (1-3 líneas). Por qué existe este cambio y qué problema resuelve. -->

**Qué ya existía:**
<!-- Qué se buscó antes de escribir código y qué se reutilizó: este repo, los demás repos propios
(graph-query, ctx_search), el taller, las skills, la biblioteca estándar o una dependencia ya
instalada. Si nada servía, dónde se buscó. Escribirlo obliga a buscar (AB#526). -->

Closes #
AB#
<!-- Opciones de trazabilidad según contract/protocols/git.md:
- Closes #N (o Fixes #N, Resolves #N, Relates to #N, Parte de #N)
- **Sin issue:** <razón explícita de por qué no requiere issue>
- AB#N: la Task de Azure; con ella la integración enlaza el PR en la Task
- **Sin Task:** <razón explícita de por qué no hay Task en Azure>; no vale para un pedido
  directo de Jennifer, que lleva su Task (contract/partes/git.md)
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
