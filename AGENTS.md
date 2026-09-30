# Reglas de Agentes en Prisma Toolkit

Este repositorio sigue el contrato universal del ecosistema Prisma gobernado por [`prisma-agent-system`](file:///Users/fer/Tech/soft/prisma-agent-system/contract/AGENTS.md).

## Invariantes locales
- Verificar la configuración y contenido del sitio antes y después de editar.
- Al terminar, subir una rama propia y abrir un PR (`git push -u origin <rama>` y `gh pr create`): el hook `pre-push` rechaza el push directo a `main`.
- Usar herramientas y comandos compactos.
