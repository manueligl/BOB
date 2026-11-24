# Cómo empezar

## 1. Prepara el proyecto

1. Crea tu repositorio a partir de esta plantilla y clónalo en tu ordenador.
2. En VS Code, abre la carpeta del proyecto con **Archivo > Abrir carpeta**. Abre la carpeta raíz del proyecto, no una subcarpeta: Bob busca sus modos en `.bob/`, en la raíz.
3. Copia tus actividades de la UD1 en la carpeta `entregas/`.

## 2. Comprueba que Bob reconoce los agentes

- **Configuración de Bob > Modos**: deben aparecer *Asesor de Negocio / Mentor*, *Arquitecto de Soluciones de TI* y *Líder Técnico (Tech Lead)*, marcados como modos del proyecto.
- **Configuración de Bob > Skills**: debe aparecer `changelog-entry`, también del proyecto.

Si no aparecen, comprueba que has abierto la carpeta raíz y recarga la ventana de VS Code.

## 3. Trabaja con los agentes en orden

| Fase | Modo | Para empezar, escríbele... |
|---|---|---|
| Pulir la idea y crear la propuesta de valor | Asesor de Negocio / Mentor | "Revisa mis entregas de la carpeta entregas/" |
| Análisis, diseño, tecnología y planificación | Arquitecto de Soluciones de TI | "Vamos a empezar la memoria a partir de docs/00-idea/" |
| Programación | Líder Técnico (Tech Lead) | "Vamos a empezar la primera iteración" |

Cambia de modo con el selector que hay debajo del cuadro de chat. Cada agente te dirá cuándo has terminado su fase y te propondrá pasar al siguiente.

## 4. Buenas prácticas

- **Abre una conversación nueva en cada sesión de trabajo.** El agente recupera el contexto leyendo el `CHANGELOG.md` y el historial de Git, así que no necesitas recordarle lo que hiciste el día anterior.
- **Lee lo que el agente te propone antes de aprobarlo,** sobre todo los comandos de terminal. Tú eres el responsable de tu proyecto y tendrás que defenderlo.
- **Haz commit cuando el agente te lo proponga.** Si no confirmas los cambios en Git, en la siguiente sesión el agente no sabrá qué se hizo.
- **Retoca tú los diagramas en draw.io** si la colocación no ha quedado bien. El agente respeta tus cambios.
