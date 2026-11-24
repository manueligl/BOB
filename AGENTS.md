# Proyecto Integrado (DAM)

Proyecto Integrado del ciclo de Desarrollo de Aplicaciones Multiplataforma (IES Polígono Sur). El alumno desarrolla su propio proyecto de software y su memoria, guiado por tres modos de Bob que se usan en este orden:

1. **Asesor de Negocio / Mentor** (`asesor-negocio-mentor`): revisa de forma crítica las actividades de la UD1 que hay en `entregas/`, ayuda a pulir la idea y a construir la propuesta de valor. Genera `docs/00-idea/`.
2. **Arquitecto de Soluciones de TI** (`arquitecto-soluciones-ti`): apartados 1 a 4 de la memoria (introducción, requisitos, diseño y planificación) y elección de la tecnología. Genera `docs/01` a `docs/04` y los ADR.
3. **Líder Técnico** (`lider-tecnico`): implementación (apartado 5) y primeras pruebas (apartado 6). Genera el código y `docs/05` y `docs/06`.

## Memoria del proyecto entre sesiones

- `CHANGELOG.md` (formato Keep a Changelog) es la memoria del proyecto entre sesiones y entre modos. Se mantiene con la skill `changelog-entry` cada vez que se valida un cambio.
- Al empezar cualquier sesión, lee `CHANGELOG.md` y revisa `git log --oneline -n 20` y `git status` antes de continuar.

## Estructura

```
entregas/            Actividades originales de la UD1 (no se modifican)
docs/00-idea/        Diagnóstico, entrevistas, propuesta de valor e idea pulida
docs/01..06-*.md     Apartados de la memoria
docs/adr/            Registro de decisiones arquitectónicas
docs/diagramas/      Diagramas de draw.io (.drawio) y sus imágenes (img/*.png)
CHANGELOG.md         Historial de cambios del proyecto
```

## Convenciones

- Documentación en Markdown y en español.
- Diagramas en draw.io; solo el Gantt va en Mermaid.
- Commits con Conventional Commits (`docs:`, `feat:`, `fix:`...), que incluyen el CHANGELOG.

> Nota: no ejecutes `/init` hasta que haya código en el proyecto. Si lo ejecutas, conserva este contenido en el `AGENTS.md` resultante.
