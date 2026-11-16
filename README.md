# Personal Skills

Catálogo personal de las **skills** instaladas en mi entorno de desarrollo para agentes de IA (Antigravity / `.agents`), organizadas por pack de origen, repositorio oficial y función de cada una.

---

## Resumen de Packs y Fuentes

| Pack / Fuente | Tipo | Repositorio Oficial | Skills incluidas |
| :--- | :--- | :--- | :---: |
| **emilkowalski/skills** | Pack (GitHub) | [github.com/emilkowalski/skills](https://github.com/emilkowalski/skills) | 14 activas (+3 en disco) |
| **superpowers (v7.0.1)** | Plugin | [github.com/obra/superpowers](https://github.com/obra/superpowers) | 15 |
| **impeccable (v4.8.0)** | Skill / Pack de diseño | [github.com/pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 1 |
| **markitdown** | Skill individual | [github.com/microsoft/markitdown](https://github.com/microsoft/markitdown) | 1 |
| **playwright** | Skill individual | [github.com/microsoft/playwright](https://github.com/microsoft/playwright) | 1 |
| **Antigravity Built-in** | Integradas | Integradas en Antigravity CLI | 2 activas (+4 en disco) |

---

## 1. Pack `emilkowalski/skills`

* **Repositorio oficial:** [https://github.com/emilkowalski/skills](https://github.com/emilkowalski/skills)
* **Ubicación local:** `~/.agents/skills/`

| Skill | Función |
| :--- | :--- |
| `animate` | Construir animaciones web desde cero decidiendo propósito, herramienta, propiedades, curvas, duración, interrupciones y salida. |
| `animate-expo` | Construir animaciones y gestos en React Native / Expo usando Reanimated, Gesture Handler, Expo Router y `expo-haptics`. |
| `animation-performance` | Mantener animaciones web dentro del presupuesto de frames (propiedades compuestas, evitar *jank*, `will-change`, capas GPU). |
| `animation-vocabulary` | Glosario inverso para traducir descripciones vagas de efectos de movimiento a su nombre técnico exacto. |
| `apple-design` | Principios de diseño de Apple y movimiento físico fluido (resortes, gestos, materiales translúcidos, tipografía) adaptados a la web. |
| `ask-sonner` | Guía de instalación, uso, tematización y solución de problemas para la librería de notificaciones *toast* Sonner en React. |
| `break-ui` | Pruebas de estrés de UI con datos extremos (*worst-case data*: nombres largos, textos no latinos, emojis, ceros, etc.). |
| `choreograph` | Orquestación y coordinación de múltiples elementos que se animan juntos (*stagger*, secuencias, transiciones, *morphs*). |
| `emil-design-eng` | Filosofía de Emil Kowalski sobre pulido de UI, diseño de componentes, decisiones de animación y detalles invisibles. |
| `find-animation-opportunities` | Auditoría de solo lectura para detectar partes de una UI que deberían animarse y descartar las que no. |
| `improve-animations` | Auditoría priorizada y planes de mejora para código de animaciones existente en un proyecto. |
| `mobile-native` | Pequeños ajustes CSS y meta-tags para que una web móvil se sienta como una app nativa (tap highlights, `100vh`, notch, etc.). |
| `remove-animations` | Detectar y eliminar animaciones innecesarias o que hacen lenta la interfaz, limpiando el código residual. |
| `write-swift` | Buenas prácticas de Swift moderno (tipos por valor, concurrencia en Swift 6, protocolos, rendimiento, ARC y Swift Testing). |

> **Nota:** En disco (`~/.agents/skills/`) también están instaladas dentro de este pack `pick-ui-library`, `prototype` y `review-animations`.

---

## 2. Plugin `superpowers` (v7.0.1)

* **Repositorio oficial:** [https://github.com/obra/superpowers](https://github.com/obra/superpowers)
* **Ubicación local:** `~/.gemini/config/plugins/superpowers/skills/`

| Skill | Función |
| :--- | :--- |
| `brainstorming` | Explorar requisitos, diseño e ideas antes de crear funcionalidades o planificar trabajo creativo. |
| `diagnosing-superpowers` | Diagnosticar por qué una sesión con *superpowers* falló, repitió trabajo o fue costosa, y generar reportes. |
| `dispatching-parallel-agents` | Coordinar 2 o más tareas independientes en paralelo cuando no comparten estado ni dependencias secuenciales. |
| `executing-plans` | Ejecutar un plan de implementación paso a paso en la sesión actual. |
| `finishing-a-development-branch` | Guiar el cierre e integración de una rama de desarrollo tras completar la implementación y pasar las pruebas. |
| `receiving-code-review` | Procesar feedback de revisión de código con rigor técnico y verificación antes de aplicar cambios. |
| `requesting-code-review` | Preparar y solicitar revisión de código al completar tareas importantes o antes de hacer *merge*. |
| `subagent-driven-development` | Ejecutar planes de implementación delegando tareas independientes a subagentes. |
| `systematic-debugging` | Metodología de depuración sistemática ante bugs o fallos de pruebas antes de proponer correcciones. |
| `test-driven-development` | Aplicar desarrollo guiado por pruebas (TDD) antes de escribir código de implementación. |
| `using-git-worktrees` | Crear espacios de trabajo aislados mediante *git worktrees* para nuevas funcionalidades o planes. |
| `using-superpowers` | Reglas base para descubrir y activar skills al inicio de cualquier conversación. |
| `verification-before-completion` | Exigir verificación real con comandos y pruebas antes de declarar una tarea como completada. |
| `writing-plans` | Redactar especificaciones y planes de implementación detallados para tareas multipaso. |
| `writing-skills` | Crear, editar y verificar nuevas skills antes de su despliegue. |

---

## 3. Skills Individuales y Herramientas

### `impeccable` (v4.8.0)
* **Repositorio oficial:** [https://github.com/pbakaus/impeccable](https://github.com/pbakaus/impeccable)
* **Ubicación local:** `~/.agents/skills/impeccable/`
* **Función:** Sistema de diseño y crítica frontend para diseñar, rediseñar, auditar, pulir, simplificar y endurecer interfaces web y móviles (UX, jerarquía, tipografía, color, accesibilidad, *design systems* y `DESIGN.md`).

### `markitdown`
* **Repositorio oficial de la herramienta:** [https://github.com/microsoft/markitdown](https://github.com/microsoft/markitdown)
* **Ubicación local:** `~/.gemini/config/skills/markitdown/` (enlazada en `~/.agents/skills/markitdown`)
* **Función:** Convertir documentos de oficina (PDF, DOCX, PPTX, XLSX), multimedia, HTML o archivos comprimidos a Markdown limpio para ingesta en LLMs, análisis de texto y pipelines RAG.

### `playwright`
* **Repositorio oficial de la herramienta:** [https://github.com/microsoft/playwright](https://github.com/microsoft/playwright)
* **Ubicación local:** `~/.gemini/config/skills/playwright/` (enlazada en `~/.agents/skills/playwright`)
* **Función:** Automatización de navegador, inspección visual de páginas locales o en vivo, capturas de pantalla y creación/ejecución de pruebas E2E con Playwright.

---

## 4. Built-in de Antigravity

* **Ubicación local:** `~/.gemini/antigravity-cli/builtin/skills/`

| Skill | Función |
| :--- | :--- |
| `agy-customizations` | Guía del sistema de personalización de Antigravity (skills, reglas, plugins, hooks y servidores MCP). |
| `antigravity_guide` | Guía completa y referencia rápida de Google Antigravity (CLI `agy`, IDE, SDK de Python, comandos y atajos). |

> **Nota:** En el directorio built-in también se encuentran `automation`, `generative_ui`, `migrate-workflows` y `permissioned-github`.
