# prisma-toolkit

> **ES** · El backbone técnico del ecosistema Código Prisma Φ — prompts, instrucciones, plantillas y configuraciones curadas.  
> **EN** · The technical backbone of the Código Prisma Φ ecosystem — curated prompts, instructions, templates, and configurations.

---

## ¿Qué es esto? · What is this?

**ES**  
`prisma-toolkit` es el repositorio operacional de [Código Prisma Φ](https://codigoprisma.xyz) — el ecosistema de conocimiento, investigación y expresión de [Jennifer Beats](https://jenniferbeats.xyz).

Aquí vive el soporte técnico del ecosistema: prompts de IA probados, instrucciones de configuración, tutoriales de herramientas y plantillas reutilizables. No es una colección estática — es un archivo vivo que crece desde la práctica del laboratorio ([Prisma Lab Φ](https://codigoprisma.xyz)).

**EN**  
`prisma-toolkit` is the operational repository of [Código Prisma Φ](https://codigoprisma.xyz) — the knowledge, research, and expression ecosystem of [Jennifer Beats](https://jenniferbeats.xyz).

This is where the ecosystem's technical support lives: tested AI prompts, configuration instructions, tool tutorials, and reusable templates. It's not a static collection — it's a living archive that grows from laboratory practice ([Prisma Lab Φ](https://codigoprisma.xyz)).

---

## Qué hace

**ES** · Es a la vez el archivo de prompts, instrucciones y plantillas del ecosistema y el sitio
público `toolkit.codigoprisma.xyz` (Jekyll con el tema Chirpy) que los muestra. **EN** · It is both the
ecosystem's archive of prompts, instructions and templates and the public site that serves them.

## Qué lo dispara

- **Publicar:** fusionar un PR a `main`. Un workflow de GitHub Actions (`jekyll-gh-pages.yml`)
  compila con `bundle exec jekyll build` y despliega en GitHub Pages, con el dominio de `CNAME`.
- **Probar:** cada push corre las pruebas (`pruebas.yml`).
- **Dependencias:** los martes y viernes a las 06:00 UTC, y a mano (`dependencias.yml`).
- **Espejo:** cada push se copia al espejo de GitLab.

## Qué toca

Publica una dirección pública. **El repo es público**: lo que se sube a `main` lo puede leer cualquiera,
así que nada de credenciales ni de notas íntimas. No escribe en ningún otro lugar.

## Dónde deja el rastro

El historial de git y los PR; las ejecuciones de GitHub Actions y los despliegues de GitHub Pages; y
el espejo de GitLab.

## Estructura · Structure

```
prisma-toolkit/
│
├── prompts/              # Prompts de IA curados · Curated AI prompts
│   ├── ai-assistants/    # System prompts, companions, configuraciones
│   ├── writing/          # Síntesis, redacción, Zettelkasten
│   ├── research/         # Workflows de investigación
│   └── systems/          # Arquitectura, diagramas, código
│
├── instructions/         # Tutoriales técnicos · Technical tutorials
│   ├── obsidian/         # Configuración del Vault
│   ├── publishing/       # Eleventy, Vercel, Starlight
│   └── workflows/        # Procesos del ecosistema
│
├── templates/            # Plantillas reutilizables · Reusable templates
│   ├── notes/            # Blooms, MOCs, Groves
│   └── docs/             # Documentación de proyectos
│
└── README.md
```

---

## Cómo usar esto · How to use this

**ES**  
Cada archivo es autónomo — incluye descripción, contexto de uso y el recurso en sí. Puedes navegar por carpeta según tu necesidad o consultar el índice de cada sección en su respectivo `README.md`.

Los archivos siguen este frontmatter mínimo:

```yaml
---
title: ""
category: ""
tags: []
version: ""
status: draft | stable | deprecated
date: YYYY-MM-DD
---
```

**EN**  
Each file is self-contained — it includes a description, usage context, and the resource itself. You can browse by folder according to your needs, or consult each section's index in its respective `README.md`.

Files follow this minimal frontmatter:

```yaml
---
title: ""
category: ""
tags: []
version: ""
status: draft | stable | deprecated
date: YYYY-MM-DD
---
```

---

## Sobre el ecosistema · About the ecosystem

**ES**  
Este toolkit es parte de **Código Prisma Φ** — un ecosistema fractal que integra experiencia, conocimiento, método y expresión en un sistema vivo. Fue construido desde la práctica real, el diseño neurodivergente y la investigación basada en experiencia.

- 🌐 Ecosistema: [codigoprisma.xyz](https://codigoprisma.xyz)  
- 🌿 Digital Garden: [garden.codigoprisma.xyz](https://garden.codigoprisma.xyz)  
- 🎙️ Voz pública: [jenniferbeats.xyz](https://jenniferbeats.xyz)

**EN**  
This toolkit is part of **Código Prisma Φ** — a fractal ecosystem that integrates experience, knowledge, method, and expression into a living system. It was built from real practice, neurodivergent design, and experience-based research.

- 🌐 Ecosystem: [codigoprisma.xyz](https://codigoprisma.xyz)  
- 🌿 Digital Garden: [garden.codigoprisma.xyz](https://garden.codigoprisma.xyz)  
- 🎙️ Public voice: [jenniferbeats.xyz](https://jenniferbeats.xyz)

---

## Licencia · License

**ES**  
El contenido de este repositorio está publicado bajo [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Puedes usarlo y adaptarlo libremente para fines no comerciales, con atribución.

**EN**  
The content in this repository is published under [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). You are free to use and adapt it for non-commercial purposes, with attribution.

---

*Construido desde la experiencia. Iterado en el laboratorio. · Built from experience. Iterated in the lab.*