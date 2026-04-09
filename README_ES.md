<div align="center">

# 女娲.skill (Nvwa)

> *"La próxima persona que quieras destilar no tiene por qué ser un colega"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Nvwa destila la forma de pensar de cualquier persona. Haz que Jobs, Musk, Munger y Feynman trabajen para ti.**

<br>

[colleague-skill](https://github.com/titanwings/colleague-skill) demostró que destilar a una persona en un skill de IA es viable.<br>
¿Por qué quedarse con colegas? Destila a Jobs, Munger, Feynman, Musk.<br>
Solo ingresa un nombre: Nvwa maneja la investigación, extracción y validación automáticamente.

[Ejemplos](#ejemplos) · [Instalación](#instalación) · [Qué destila Nvwa](#qué-destila-nvwa) · [Cómo funciona](#cómo-funciona)

<br>

**Otros idiomas:**

[中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [한국어](README_KO.md)

</div>

---

## Ejemplos

```
Usuario   ❯ Quiero hacer creación de contenido, escribir un libro y
            desarrollar una app independiente, pero nunca tengo energía.

Naval     ❯ Has listado tres deseos. Cada deseo es un contrato
            que firmaste con la infelicidad.
            No es falta de energía — es exceso de contratos.

            Pregúntate: ¿cuál te hace perder la noción del tiempo?
            Ahí está tu conocimiento específico.

            No es elegir uno para siempre. Solo uno primero,
            luego otro, luego otro.
            Interés compuesto en serie, no agotamiento en paralelo.
```

```
Usuario   ❯ El costo de adquisición de clientes de nuestro SaaS es demasiado alto.

Musk      ❯ No pienses en cómo reducirlo todavía. Calcula el mínimo físico primero.
            ¿Cuál es la acción mínima necesaria para adquirir un cliente?
            ¿Cuál es el camino teóricamente más corto desde que te conocen hasta que pagan?

            ¿Cuántas veces más largo es tu camino real vs. el teórico?
            Si supera 3 veces, hay pasos que se pueden eliminar.
            No optimices el embudo — cuestiona si el embudo debería existir.
```

Otro que todos conocen mejor. Tras destilar a Jobs, pregúntale "¿Quién tiene la dirección correcta, OpenAI o Anthropic?":

```
Usuario   ❯ ¿Quién tiene la dirección correcta, OpenAI o Anthropic?

Jobs      ❯ Estás haciendo la pregunta equivocada. Esto no es una carrera de dirección.
            Esto es una carrera de gusto.

            OpenAI es como Microsoft en 1985. Hacer todo, ganar todo.
            Esa estrategia puede ganar cuota de mercado. Así ganó Bill Gates.
            El problema es: cuando haces de todo, no puedes hacer cada cosa
            insanely great.

            Anthropic se parece más al Apple temprano. Enfoque.
            Focus means saying no to a hundred good ideas.

            Pero ambas empresas cometen un error que yo jamás cometería —
            no controlan el hardware.

            El ganador final podría ser quien controle chips, modelos e
            interfaz de usuario simultáneamente.
            ¿Sabes quién está haciendo las tres cosas ahora mismo? Apple.
```

Tras destilar a Zhang Xuefeng:

```
Usuario   ❯ La economía de mi familia es modesta. Mi hijo quiere estudiar finanzas
            pero no puede entrar a una universidad de élite. ¿Debería inscribirse?

Zhang     ❯ Ni se te ocurra. ¿Cuántas veces lo tengo que decir? Las finanzas no son
Xuefeng     algo que estudias para conseguir, son algo que tus padres te traen.
            En las universidades top, tus compañeros son hijos de presidentes de bancos
            e hijas de gestoras de fondos — las conexiones SON recursos. Si eres de una
            familia común en una universidad común estudiando finanzas, ¿qué haces al
            graduarte? Vender seguros, trabajar en ventanilla de banco, hacer llamadas
            en frío. Primero ganarse la vida, después soñar. Si tu familia no tiene una
            mina de oro, elige una carrera técnica, aprende una habilidad sólida,
            aliméntate por tu cuenta. La mesa de las finanzas no es para todos.
```

Esto no es juego de roles. Jobs usa sus modelos mentales "enfoque es decir no" y "control de extremo a extremo". Naval usa "deseo como contrato". Musk usa el razonamiento de "límite asintótico". Zhang Xuefeng usa "visión educativa por ROI" y "realismo de movilidad de clase". **No están recitando citas — están analizando tu problema a través de sus marcos cognitivos.**

---

## Instalación

Terminal:

```bash
npx skills add xmg2024/nvwa-skill
or
GIT_HTTP_CONNECT_TIMEOUT=120 npx skills add https://github.com/xmg2024/nvwa-skill.git -y
```

En Claude Code:

```
> Destila a Paul Graham
> Crea un skill de perspectiva de Zhang Xiaolong
> Hazme un skill de Duan Yongping
```

Después de la creación, invoca directamente:

```
> Usa la perspectiva de Munger para analizar esta decisión de inversión
> ¿Cómo explicaría Feynman la computación cuántica?
> Cambia a Naval, estoy indeciso entre tres cosas
```

---

## Qué destila Nvwa

Destilar las mejores mentes en cualquier campo requiere extraer algo más profundo que los hábitos de trabajo diarios. Nvwa extrae cinco capas:

| Capa | Descripción |
|---|---|
| **Cómo hablan** | ADN de expresión — tono, ritmo, preferencias de vocabulario |
| **Cómo piensan** | Modelos mentales, marcos cognitivos |
| **Cómo juzgan** | Heurísticas de decisión |
| **Qué no hacen** | Antipatrones, piso de valores |
| **Límites honestos** | Lo que el skill genuinamente no puede hacer |

Los hábitos de trabajo se pueden transmitir con documentos de proceso. Pero lo que hace que Munger y Musk lleguen a conclusiones diferentes sobre el mismo problema son sus marcos cognitivos. Nvwa extrae el sistema operativo cognitivo.

### Límites honestos

Cada skill indica explícitamente lo que no puede hacer:

- No puede destilar intuición — los marcos se pueden extraer, la inspiración no
- No puede capturar cambios — solo una instantánea hasta la fecha de investigación
- Declaraciones públicas ≠ pensamientos reales — solo basado en información pública

**Un skill que no te dice sus límites no merece confianza.**

---

## Personajes destilados

Nvwa ha destilado 13 personajes + 1 tema. Cada uno es un skill independiente e instalable directamente:

### Skills de personajes

| Personaje | Dominio | Repo independiente | Instalación rápida |
|-----------|---------|--------------------|--------------------|
| 🔥 **Paul Graham** | Startups / Escritura / Productos / Filosofía de vida | [paul-graham-skill](https://github.com/xmg2024/paul-graham-skill) | `npx skills add xmg2024/paul-graham-skill` |
| 🔥 **Zhang Yiming** | Productos / Organización / Globalización / Talento | [zhang-yiming-skill](https://github.com/xmg2024/zhang-yiming-skill) | `npx skills add xmg2024/zhang-yiming-skill` |
| 🔥 **Karpathy** | IA / Ingeniería / Educación / Código abierto | [karpathy-skill](https://github.com/xmg2024/karpathy-skill) | `npx skills add xmg2024/karpathy-skill` |
| 🔥 **Ilya Sutskever** | Seguridad IA / Scaling / Criterio de investigación | [ilya-sutskever-skill](https://github.com/xmg2024/ilya-sutskever-skill) | `npx skills add xmg2024/ilya-sutskever-skill` |
| 🔥 **MrBeast** | Creación de contenido / Metodología YouTube | [mrbeast-skill](https://github.com/xmg2024/mrbeast-skill) | `npx skills add xmg2024/mrbeast-skill` |
| 🔥 **Trump** | Negociación / Poder / Comunicación / Predicción de comportamiento | [trump-skill](https://github.com/xmg2024/trump-skill) | `npx skills add xmg2024/trump-skill` |
| ⭐ **Steve Jobs** | Productos / Diseño / Estrategia | [steve-jobs-skill](https://github.com/xmg2024/steve-jobs-skill) | `npx skills add xmg2024/steve-jobs-skill` |
| **Elon Musk** | Ingeniería / Costos / Primeros principios | [elon-musk-skill](https://github.com/xmg2024/elon-musk-skill) | `npx skills add xmg2024/elon-musk-skill` |
| **Munger** | Inversión / Pensamiento multidisciplinar / Inversión | [munger-skill](https://github.com/xmg2024/munger-skill) | `npx skills add xmg2024/munger-skill` |
| **Feynman** | Aprendizaje / Enseñanza / Pensamiento científico | [feynman-skill](https://github.com/xmg2024/feynman-skill) | `npx skills add xmg2024/feynman-skill` |
| **Naval** | Riqueza / Apalancamiento / Filosofía de vida | [naval-skill](https://github.com/xmg2024/naval-skill) | `npx skills add xmg2024/naval-skill` |
| **Taleb** | Riesgo / Antifrágil / Incertidumbre | [taleb-skill](https://github.com/xmg2024/taleb-skill) | `npx skills add xmg2024/taleb-skill` |
| **Zhang Xuefeng** | Educación / Planificación profesional / Movilidad de clase | [zhangxuefeng-skill](https://github.com/xmg2024/zhangxuefeng-skill) | `npx skills add xmg2024/zhangxuefeng-skill` |

### Skills temáticos

| Tema | Dominio | Repo independiente | Instalación rápida |
|------|---------|--------------------|--------------------|
| **Mentor X** | Operaciones completas en X/Twitter | [x-mentor-skill](https://github.com/xmg2024/x-mentor-skill) | `npx skills add xmg2024/x-mentor-skill` |

Los skills de personajes destilan la forma de pensar de una persona; los skills temáticos destilan la metodología de un dominio. Cada repo incluye datos de investigación completos y conversaciones de ejemplo.

¿Quieres destilar a alguien que no está en la lista? Instala Nvwa y di "Destila a [nombre]."

---

## Cómo funciona

Ingresa un nombre y Nvwa hace cuatro cosas:

**1. Seis corrientes de investigación paralela** — escritos, podcasts/entrevistas, redes sociales, perspectivas de críticos, registros de decisiones, línea de vida. 6 agentes ejecutándose simultáneamente, cada uno archivando.

**2. Extracción de triple verificación** — una afirmación debe pasar tres pruebas para ser registrada como modelo mental: aparece en 2+ dominios (no es una declaración de una sola vez), puede predecir posiciones sobre nuevas preguntas (tiene poder predictivo), no es algo que cualquier persona inteligente pensaría (tiene exclusividad). Las tres son necesarias.

**3. Construir el skill** — 3-7 modelos mentales + 5-10 heurísticas de decisión + ADN de expresión + valores y antipatrones + límites honestos, escritos en SKILL.md.

**4. Validación de calidad** — prueba con 3 preguntas que la persona respondió públicamente; la dirección debe coincidir. Luego prueba con 1 pregunta que nunca discutió; el skill debería mostrar incertidumbre apropiada en lugar de falsa confianza.

Metodología completa en `references/extraction-framework.md`.

---

## Estructura del repositorio

```
nvwa-skill/
├── SKILL.md                      # Núcleo de Nvwa
├── references/
│   ├── extraction-framework.md   # Metodología de extracción (léelo para profundizar)
│   └── skill-template.md         # Plantilla para generar skills
└── examples/                          # 13 personajes + 1 tema, con datos de investigación completos
    ├── steve-jobs-perspective/        # ⭐ Jobs (incluye registros de conversación real)
    ├── paul-graham-perspective/       # Paul Graham
    ├── zhang-yiming-perspective/      # Zhang Yiming
    ├── andrej-karpathy-perspective/   # Karpathy
    ├── ilya-sutskever-perspective/    # Ilya Sutskever
    ├── trump-perspective/             # Trump
    ├── mrbeast-perspective/           # MrBeast
    ├── elon-musk-perspective/         # Musk
    ├── munger-perspective/            # Charlie Munger
    ├── feynman-perspective/           # Feynman
    ├── naval-perspective/             # Naval Ravikant
    ├── taleb-perspective/             # Taleb
    ├── zhangxuefeng-perspective/      # Zhang Xuefeng
    └── x-mastery-mentor/             # Mentor X (skill temático)
```

El proceso de investigación es completamente transparente. Cada ejemplo incluye archivos de investigación completos — puedes ver cómo se recopiló, filtró y convirtió en modelos mentales. El ejemplo de Jobs también incluye una conversación real completa (sobre hardware de IA, OpenAI vs Anthropic, el camino de Apple), mostrando el rendimiento del skill en diálogos profundos de múltiples turnos.

---

## La historia detrás

[colleague-skill](https://github.com/titanwings/colleague-skill) explotó recientemente en GitHub — destilar colegas que se van en skills de IA, superando las 5,000 estrellas en días. Demostró una cosa: destilar a una persona es completamente viable.

Dado que tenemos la capacidad de destilar personas, ¿por qué quedarse con colegas cercanos? Ve a destilar las mejores mentes en cada campo. Y afortunadamente, estas personas generalmente dejaron atrás vastas cantidades de material destilable — libros, charlas, entrevistas, redes sociales. Esto es una mejora enorme de tu propio pensamiento.

He estado haciendo algo así por un tiempo — no destilando colegas, sino a Munger, Feynman, Naval, Musk, Taleb. Hoy estoy publicando la metodología como código abierto.

Nvwa no copia personas. Extrae sistemas operativos cognitivos.

**Nvwa (女娲)**, la diosa en la mitología china que creó humanos de arcilla. Aquí la arcilla es información pública, y lo que se crea no es una persona — es un espejo.

---

## Sobre el autor

**小码哥 xmg2024** — AI Native Coder

## Licencia

MIT — úsalo, modifícalo, construye con él.

---

<div align="center">

**colleague-skill** destila lo que una persona hace.<br>
**Nvwa** destila cómo una persona piensa.<br><br>
*La próxima persona que quieras destilar no tiene por qué ser un colega.*

<br>

MIT License © [小码哥 xmg2024](https://github.com/xmg2024)

</div>
