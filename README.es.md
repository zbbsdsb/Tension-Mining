<p align="center">
  <img src="./assets/logo.svg" alt="Tension Mining" width="64" height="64" style="vertical-align: middle; margin-right: 12px;">
  <img src="./social-preview.jpg" alt="Tension Mining" width="100%">
</p>

<p align="center">
  <a href="https://github.com/zbbsdsb/Tension-Mining/stargazers"><img src="https://img.shields.io/github/stars/zbbsdsb/Tension-Mining?style=flat-square&color=e63946" alt="GitHub Stars"></a>
  <a href="https://github.com/zbbsdsb/Tension-Mining/network/members"><img src="https://img.shields.io/github/forks/zbbsdsb/Tension-Mining?style=flat-square&color=f4a261" alt="GitHub Forks"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square&color=2a9d8f" alt="MIT License"></a>
  <a href="./SKILL.md"><img src="https://img.shields.io/badge/skill-v2.0-blue?style=flat-square&color=4a6fa5" alt="Skill v2.0"></a>
  <a href="./references/tension-atlas.md"><img src="https://img.shields.io/badge/tensions-19-4a6fa5?style=flat-square" alt="19 Tensions"></a>
  <a href="./references/invariant-atlas.md"><img src="https://img.shields.io/badge/invariants-12-4a6fa5?style=flat-square" alt="12 Invariants"></a>
  <a href="./examples/"><img src="https://img.shields.io/badge/cases-11_studies-6b7280?style=flat-square" alt="11 Casos de Estudio"></a>
  <a href="https://github.com/zbbsdsb/Tension-Mining/actions"><img src="https://img.shields.io/github/actions/workflow/status/zbbsdsb/Tension-Mining/ci.yml?style=flat-square&color=2a9d8f" alt="CI Status"></a>
</p>

<p align="center">
  <strong>
    ⭐ Dale estrella a este repositorio &nbsp;·&nbsp;
    <a href="https://github.com/zbbsdsb/Tension-Mining/discussions">💬 Discusiones</a> &nbsp;·&nbsp;
    <a href="https://twitter.com/intent/tweet?text=Tension%20Mining%20%E2%80%94%20Descubre%20invariantes%20entre%20dominios%20en%20sistemas%20complejos&url=https://github.com/zbbsdsb/Tension-Mining">🐦 Compartir en Twitter</a>
  </strong>
</p>

---

<p align="center">
  <a href="./README.md">English</a> | <a href="./README.zh-CN.md">简体中文</a> | Español | <a href="./README.hi.md">हिन्दी</a>
</p>

---

> **La mayoría busca soluciones. Los grandes investigadores buscan tensiones.**

Una metodología de investigación para descubrir Invariants ocultos dentro de sistemas complejos. Funciona como un **Skill ejecutable por IA** en Claude Code, TRAE, Cursor, Windsurf y cualquier herramienta que admita archivos de Skill basados en Markdown.

[Inicio Rápido](#inicio-rápido) · [Cómo Funciona](#cómo-funciona) · [Casos de Estudio](#casos-de-estudio) · [Documentación](#documentación) · [Contribuir](./CONTRIBUTING.md)

---

## Índice

- [¿Por qué Tension Mining?](#por-qué-tension-mining)
- [Inicio Rápido](#inicio-rápido)
- [Cómo Funciona](#cómo-funciona)
- [Las Siete Fases](#las-siete-fases)
- [Casos de Estudio](#casos-de-estudio)
- [Lo Que Esto No Es](#lo-que-esto-no-es)
- [Documentación](#documentación)
- [Hoja de Ruta](#hoja-de-ruta)
- [Licencia](#licencia)

---

## ¿Por qué Tension Mining?

La mayoría de los flujos de innovación comienzan demasiado tarde.

Empiezan con algoritmos, arquitecturas, implementaciones y optimizaciones. Pero los sistemas más influyentes rara vez surgen de la optimización.

- **PageRank** comenzó con una pregunta sobre la importancia — no con una ecuación matricial.
- **Bitcoin** comenzó con una tensión entre descentralización y confianza — no con una estructura de datos blockchain.
- **Wikipedia** comenzó con una tensión entre apertura y fiabilidad — no con un sistema de control de revisiones.
- **Transformer** comenzó con una pregunta sobre si la recurrencia era realmente necesaria — no con un mecanismo de atención.

El avance aparece mucho antes que el algoritmo. Aparece cuando una tensión oculta finalmente se hace visible.

**Tension Mining es un lente.** Su propósito es simple: ayudar a los investigadores a descubrir las fuerzas que moldean un sistema antes de intentar diseñar el sistema mismo.

### La Idea Central

Todo sistema persistente está moldeado por un conjunto de tensiones no resueltas.

| Dominio | Tensión |
|---------|---------|
| Organización | Libertad ↔ Eficiencia |
| Sociedad | Orden ↔ Innovación |
| Agentes de IA | Autonomía ↔ Control |
| Mundos NPC | Supervivencia ↔ Exploración |
| Productos | Simplicidad ↔ Capacidad |
| Mercados | Competencia ↔ Cooperación |

La mayoría se enfoca en el comportamiento. Tension Mining se enfoca en las fuerzas detrás del comportamiento.

---

## Fundamentos Académicos

Tension Mining se basa y sintetiza conceptos de múltiples tradiciones de investigación establecidas.

| Campo | Referencias Clave | Relación |
|-------|------------------|----------|
| Sistemas Complejos | Mitchell (2009) [1], Holland (1995) [2] | Marco central para emergencia, autoorganización y adaptación |
| Pensamiento de Diseño | Schön (1983) [3], Cross (2006) [4] | Enfoque centrado en el fenómeno, redefinición del problema antes de la solución |
| Pensamiento Sistémico | Meadows (2008) [5], Senge (1990) [6] | Bucles de retroalimentación, puntos de apalancamiento, análisis de estructura de sistemas |
| Marco Cynefin | Snowden & Boone (2007) [7] | Distinguir entre dominios de problemas ordenados y complejos |
| Metodología de Investigación | Kuhn (1962) [8], Lakatos (1970) [9] | Cambios de paradigma, estructura de programas de investigación, falsación |
| Teoría Evolutiva | Dawkins (1976) [10], Boyd & Richerson (1985) [11] | Variación-selección-retención como motor de descubrimiento de invariantes |
| Ciencias de Redes | Barabási & Albert (1999) [12], Watts & Strogatz (1998) [13] | Propiedades emergentes de interacciones locales, fenómenos de mundo pequeño |

Estos fundamentos no son decorativos. Cada uno informa directamente una fase específica del pipeline:
- **Sistemas Complejos** → Fase 1 (los fenómenos deben cruzar dominios, no reforzar la miopía disciplinaria)
- **Pensamiento de Diseño** → Fase 2-3 (tensiones antes que soluciones, redefinición como habilidad central)
- **Pensamiento Sistémico** → Fase 4-5 (los mecanismos interactúan mediante retroalimentación, no causalidad lineal)
- **Cynefin** → Fase 7 (la destrucción revela si el problema estaba en un dominio complicado o complejo)
- **Teoría Evolutiva** → Fase 3 (los invariantes se seleccionan por supervivencia entre dominios, no por intención del diseñador)

Consulte la [Guía de Metodología](./references/methodology-primer.md) para una comparación detallada con metodologías relacionadas y una lista de lectura completa.

---

## Inicio Rápido

### 1. Instalación

Clona este repositorio en el directorio de Skills de tu herramienta de IA:

```bash
# Claude Code — a nivel de proyecto (recomendado)
git clone https://github.com/zbbsdsb/Tension-Mining.git .claude/skills/tension-mining

# Claude Code — a nivel de usuario (todos los proyectos)
git clone https://github.com/zbbsdsb/Tension-Mining.git ~/.claude/skills/tension-mining

# TRAE
git clone https://github.com/zbbsdsb/Tension-Mining.git .trae/skills/tension-mining

# Cursor / Windsurf / otros
# Coloca el repositorio en cualquier lugar accesible. Haz referencia a SKILL.md en las instrucciones de tu proyecto.
```

### 2. Uso

**Disparo automático** — describe un problema de sistema complejo en lenguaje natural:

> "Quiero diseñar un sistema de identidad descentralizado para un mercado P2P."

La IA detecta el disparo y activa Tension Mining automáticamente.

**Disparo manual** — invoca el Skill directamente:

| Herramienta | Comando |
|------------|---------|
| Claude Code | `/tension-mining` |
| TRAE | La IA se autoactiva según la descripción de SKILL.md |
| Cursor / Windsurf | Haz referencia a `SKILL.md` en tu `.cursorrules` o instrucciones del proyecto |

### 3. Sigue las 7 Fases

La IA te guiará a través de 7 fases, haciendo una pregunta a la vez:

```
1. Phenomenon Mining  →  Recopila 5-10 ejemplos reales de 3+ dominios
2. Tension Mining      →  Identifica 5+ tradeoffs ineliminables
3. Invariant Mining    →  Extrae 3+ principios transversales
4. Mechanism Mining    →  Estudia cómo la realidad resuelve estas tensiones
5. System Synthesis    →  Combina en un modelo coherente
6. Algorithm Synthesis →  Deriva algoritmos a partir de mecanismos (solo ahora)
7. Destruction Phase   →  Ataca tu propio modelo
```

**Principio central:** No empieces desde las soluciones. Empieza desde la realidad.

---

## Cómo Funciona

### Patrones de Diseño

Tension Mining utiliza un patrón híbrido **Pipeline + Inversión + Generador**:

- **Pipeline** — 7 fases se ejecutan en orden estricto. Cada fase tiene una condición de puerta (Gate Condition); no puedes avanzar hasta que se cumpla.
- **Inversión** — La IA te entrevista fase por fase, haciendo una pregunta a la vez. Tú impulsas el contenido; la IA aplica la metodología.
- **Generador** — El resultado sigue una plantilla estructurada con secciones definidas, garantizando completitud.

### Mecanismos Anti-Trampa

- **Tabla de Racionalizaciones Comunes** — contrarresta la tendencia de la IA a saltarse pasos ("Ya conozco las tensiones, saltemos al algoritmo")
- **Banderas Rojas** — comportamientos observables que indican que la metodología está siendo violada
- **Rúbrica de Calidad** — autoevaluación en 5 dimensiones (D1-D5, puntuación 0-15) adjunta a cada salida

### Divulgación Progresiva

`SKILL.md` es un esqueleto de activación conciso (~80 líneas). Las instrucciones detalladas de las fases, los Atlas y las plantillas se cargan bajo demanda, manteniendo el contexto inicial mínimo.

---

## Las Siete Fases

### 1. Phenomenon Mining

> ¿Qué sistemas ya exhiben este comportamiento?

Observa la realidad antes de construir abstracciones. Construye una biblioteca de fenómenos a partir de colonias de hormigas, empresas, ciudades, ecosistemas, comunidades en línea y proyectos de código abierto.

### 2. Tension Mining

> ¿Qué tradeoff nunca puede eliminarse por completo?

Identifica las fuerzas que empujan el sistema en diferentes direcciones. Construye un mapa de tensiones.

### 3. Invariant Mining

> ¿Qué se mantiene verdadero independientemente del dominio?

Busca patrones que aparecen en sistemas no relacionados. Extrae Invariants.

### 4. Mechanism Mining

> ¿Qué mecanismos ya existen en la naturaleza, la sociedad o la tecnología?

Estudia cómo la realidad resuelve las tensiones. Construye una biblioteca de mecanismos.

### 5. System Synthesis

> ¿Cuál es el modelo más pequeño que explica el sistema?

Combina tensiones, Invariants y mecanismos en un modelo coherente. Identifica qué tensiones son primarias, qué mecanismos son esenciales y qué modos de fallo existen.

### 6. Algorithm Synthesis

> Si el mecanismo es real, ¿cómo debería implementarse?

Solo ahora diseña algoritmos. Permite que surjan naturalmente a partir de los mecanismos.

### 7. Destruction Phase

> ¿Qué supuestos fallan? ¿Qué casos extremos rompen el sistema?

Ataca el modelo. Asume que está equivocado. Identifica supuestos débiles, tensiones faltantes y posibles rediseños.

---

## Casos de Estudio

Cada caso de estudio recorre el Pipeline completo de 7 fases:

| Caso de Estudio | Dominio | Tensiones Clave | Invariants Clave |
|----------------|---------|----------------|------------------|
| [PageRank](./examples/page-rank.md) | Recuperación de Información | Local vs Global, Freedom vs Efficiency | Local Rules Create Global Order, Gradients Drive Movement |
| [Transformer](./examples/transformer.md) | Deep Learning | Synchronicity vs Asynchronicity, Compression vs Fidelity | Compression Reveals Structure, Gradients Drive Movement |
| [Bitcoin](./examples/bitcoin.md) | Criptomoneda | Centralization vs Decentralization, Competition vs Cooperation | Identity Drives Cooperation, Tradeoffs Are Inescapable |
| [Git](./examples/git.md) | Control de Versiones | Consistency vs Availability, Local vs Global | Local Rules Create Global Order, Identity Drives Cooperation |
| [Wikipedia](./examples/wikipedia.md) | Conocimiento Colaborativo | Freedom vs Efficiency, Individual vs Collective | Identity Drives Cooperation, Compression Reveals Structure |
| [NPC Society](./examples/npc-society.md) | Sistemas Multi-Agente | Survival vs Exploration, Individual vs Collective | Local Rules Create Global Order, Variation Enables Selection |
| [Agent Organization](./examples/agent-organization.md) | Coordinación de IA | Autonomy vs Control, Centralization vs Decentralization | Identity Drives Cooperation, Feedback Loops Stabilize |
| [Dialogue Walkthrough](./examples/dialogue-example.md) | Identidad Descentralizada | *Demostración completa de interacción de 7 fases* | *Primera lectura recomendada* |
| [Consensus Protocols](./examples/consensus-protocols.md) | Sistemas Distribuidos | Safety vs Liveness, Consistency vs Availability | Local Rules Create Global Order, Tradeoffs Are Inescapable |
| [Ant Colony Foraging](./examples/ant-colony.md) | Sistemas Biológicos | Individual vs Collective, Survival vs Exploration | Local Rules Create Global Order, Variation Enables Selection |
| [Market Efficiency](./examples/market-efficiency.md) | Economía | Order vs Innovation, Competition vs Cooperation | Preferential Attachment, Tradeoffs Are Inescapable |

---

## Lo Que Esto No Es

- **No** es una colección de prompts
- **No** es una plantilla de lluvia de ideas
- **No** es un marco de productividad
- **No** es un camino garantizado hacia la innovación
- **No** es un sistema de diseño visual

Tension Mining es un lente. Su propósito es simple: ayudar a los investigadores a descubrir las fuerzas que moldean un sistema antes de intentar diseñar el sistema mismo.

---

## Documentación

| Ruta | Propósito |
|------|-----------|
| [`SKILL.md`](./SKILL.md) | Esqueleto de activación — el punto de entrada de la IA (~80 líneas) |
| [`references/execution-protocol.md`](./references/execution-protocol.md) | Instrucciones detalladas de las 7 fases (Objetivo / Entrevista / Salida / Puerta) |
| [`references/interface-contract.md`](./references/interface-contract.md) | Especificación de entrada/salida y manejo de errores |
| [`references/quality-rubric.md`](./references/quality-rubric.md) | Rúbrica de puntuación de 5 dimensiones (D1-D5, escala 0-15) |
| [`references/tension-atlas.md`](./references/tension-atlas.md) | Catálogo de 19 tensiones persistentes en 5 dominios |
| [`references/invariant-atlas.md`](./references/invariant-atlas.md) | Catálogo de 12 Invariants transversales en 4 capas |
| [`references/methodology-primer.md`](./references/methodology-primer.md) | Referencia metodológica extendida y FAQ |
| [`examples/dialogue-example.md`](./examples/dialogue-example.md) | Demostración completa de diálogo usuario-IA (**primera lectura recomendada**) |
| [`examples/`](./examples/) | 10 casos de estudio adicionales |
| [`templates/_core-template.md`](./templates/_core-template.md) | Esqueleto de flujo de trabajo compartido de 7 fases |
| [`templates/`](./templates/) | 9 plantillas específicas por dominio (Algoritmo, Agente IA, Sociedad NPC, Organización, Protocolo, Diseño de API, Protocolo de Consenso, Diseño de Juegos) |
| [`PROJECT_STRUCTURE.md`](./PROJECT_STRUCTURE.md) | Diseño de directorios, gráfico de dependencias, reglas de gobernanza |
| [`CONTRIBUTING.md`](./CONTRIBUTING.md) | Cómo contribuir tensiones, Invariants, casos y plantillas |
| [`CHANGELOG.md`](./CHANGELOG.md) | Historial de versiones |

---

## Hoja de Ruta

### v2.0 (Actual)
- [x] Pipeline de 7 fases con condiciones de puerta (Gate Conditions)
- [x] Arquitectura de Divulgación Progresiva
- [x] Atlas con etiquetado [CORE]/[EXPERIMENTAL]
- [x] 9 plantillas específicas por dominio
- [x] 8 casos de estudio
- [x] Rúbrica de calidad (D1-D5)
- [x] CI/CD con validación automatizada de Atlas
- [x] Mecanismos de defensa Anti-Racionalización

### v2.1 (Planificado)
- [ ] Demo web interactiva
- [x] Casos de estudio adicionales (Sistemas Distribuidos, Sistemas Biológicos, Economía)
- [x] Expansión de plantillas (Diseño de API, Protocolos de Consenso, Diseño de Juegos)
- [ ] Tensiones e Invariants contribuidos por la comunidad
- [x] Soporte multilingüe (Chino, Español, Hindi)

---

## Una Pregunta

Antes de diseñar cualquier cosa, pregúntate:

> ¿Qué tensión estoy viendo realmente?

La respuesta suele ser más valiosa que el algoritmo.

---

## Licencia

Licencia MIT — Copyright (c) 2026 zbbsdsb

Consulta [LICENSE](./LICENSE) para más detalles.

---

## Contribuir con Traducciones

Si deseas contribuir con una traducción de Tension Mining a otros idiomas, ¡los PRs son bienvenidos! Se recomienda seguir este patrón:
- Copia `README.md` y renómbralo como `README.{código-de-idioma}.md`
- Mantén todos los enlaces internos apuntando a los archivos originales en inglés
- Los bloques de código y las rutas de archivo deben permanecer en su idioma original