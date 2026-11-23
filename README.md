# Case Filter (`Падежный фильтр`) & Macro-OS (`Макрос-ОС`)

**Portable Text Actions (Zero-Code State Machines) for Large Language Models.**  
**Переносимые текстовые экшены (макросы без программирования) для работы с языковыми моделями.**

- **Author / Автор:** Irina Vetlugina / Ирина Ветлугина (Samara, Russia)
- **IP Priority / Приоритет авторства:** Base protocol `v1.2` (*"Methodological Guide and Protocol of the 'Case Filter' Tool (version v1.2)"*) is officially deposited with the National Registry of Intellectual Property (**n'RIS / нРИС**) on `20.11.2026` (valid through `20.11.2027`), Registration **No. 852-137-831**
- **License / Лицензия:** Dual License — Free for Non-Commercial Use (**Creative Commons BY-NC 4.0**) / Paid Commercial License (`polutshe@mail.ru`)
- **Core Release / Релиз ядра:** `v1.3` (`[R]` / `[Р]`) — *Initial verification windows and blind runs #1–#7 closed* | **Macro-OS Suite:** `v0.1 – v3.0`

**Language / Язык:** [English](#english) | [Русский](#русский)

---

<a name="english"></a>
## 🇬🇧 English: Photoshop & 3D Action Logic for LLM Attention

My name is **Irina Vetlugina**, creator of the **Dated Record Method** and the **Case Filter / MACRO-OS** architecture. I brought the concept of an **Action**—and the habit of building lightweight, crash-free pipelines without overloading the hardware—from my background in **Photoshop and 3D**. I managed to apply a similar method to LLMs—using basic grammar as a tool to verify real action (*"Mom washed the window frame"*).

**Case Filter** is a portable text macro. Think of it as a **Photoshop Action (`.atn`), but for text**: you do not write Python code, configure APIs, or install plugins. You simply paste a `.md` file at the start of a dialogue with any LLM (ChatGPT, Claude, Gemini, DeepSeek, etc.), and it turns the model into a strict verification instrument.

Instead of polite prompts (*"please don't hallucinate"*), the system uses **grammatical cases, verb aspect, voice, and time slots** as a deterministic UI over the model's attention heads—separating paid deeds (`E`) from empty promises, passive-voice manipulations (`EMPTY SEAT`), and undated forecasts (`Ê`).

### 📂 Repository Architecture

#### 1. Core Engine (`core/`)
* [`core/case-filter-v1.3-en.md`](core/case-filter-v1.3-en.md) — **Case Filter Tool `v1.3` (English):** The flagship core engine. Audits claims across grammatical cases, enforces dated verification windows `[t₁, t₂]`, catches logical impostors (*Cells 1, 13–15*), and mandates `"unidentified remainder"` instead of hallucinations (`RUN: [text]`).
* [`core/padezhny-filtr-v1.3.md`](core/padezhny-filtr-v1.3.md) — **«Падежный фильтр» `v1.3` (Russian):** Original Russian core protocol (`ПРОГОН: [текст]`).

#### 2. Macro-OS Extension Modules (`modules/`)
Specialized text actions built on top of the core engine (like tools in a Photoshop toolbar):
* [`modules/macro-os-v3.0.md`](modules/macro-os-v3.0.md) — **MACRO-OS `v3.0` All-in-One (Russian):** Unified 8-layer analytical conveyor (`КОМБАЙН: [текст]`) + built-in AI Hallucination Detector (`ЗЕРКАЛО`).
* [`modules/macro-os-audit-v0.2-en.md`](modules/macro-os-audit-v0.2-en.md) — **Batch Action "Full Audit" `v0.2` (English):** Unified 4-gate pipeline (`Boundary → Voice → Aspect → Time/Verification`) in a single card (`AUDIT: [text]`).
* [`modules/macro-os-audit-v0.2.md`](modules/macro-os-audit-v0.2.md) — **Пакетный экшен «Полный аудит» `v0.2` (Russian):** Объединённый 4-шлюзовый конвейер (`АУДИТ: [текст]`).
* [`modules/voice-filter-v0.1.md`](modules/voice-filter-v0.1.md) — **Module #01: Voice Filter (`Залоговый фильтр`):** Exposes hidden agents behind passive voice and reflexive verbs (`ЗАЛОГ: [текст]`).
* [`modules/aspect-filter-v0.1.md`](modules/aspect-filter-v0.1.md) — **Module #02: Aspect Filter (`Видовой фильтр`):** Cuts ongoing fluff (*"working on, improving"*) from completed results (`ВИД: [текст]`).
* [`modules/evidentiality-filter-v0.1.md`](modules/evidentiality-filter-v0.1.md) — **Module #03: Evidentiality Auditor (`Эвиденциальный аудитор`):** Grades statements across 4 evidence tiers—direct measurement, official document, hearsay, or speculation (`ИСТОЧНИК: [текст]`).
* [`modules/contract-auditor-v0.1.md`](modules/contract-auditor-v0.1.md) — **Module #04: Contract & Scope Auditor (`Аудитор обязательств и ТЗ`):** Catches undated deadlines, passive acceptance traps, and process-without-deliverable clauses (`СДЕЛКА: [текст]`).
* [`modules/ai-mirror-v1.0.md`](modules/ai-mirror-v1.0.md) — **AI Mirror (`ЗЕРКАЛО / AI-AUDIT v1.0`):** Forces the LLM to audit its own previous answer and calculate a factual Honesty Index (`ЗЕРКАЛО` / `ЭКЗАМЕН:`).

#### 3. Case Studies & Stress Tests (`examples/`)
* [`examples/case-study-genom-pro.md`](examples/case-study-genom-pro.md) — **Investment Due Diligence Audit ("Genom-Pro" Biotech Startup):** Full core audit separating 1 verified preclinical lab record from $15M rumors, lost archives, and undated promises.
* **Blind Run #7 (16 Edge Cases):** Verified across 10 hardest scientific problems (Poincaré Conjecture, AlphaFold, Riemann Hypothesis, Navier–Stokes, Quantum Gravity, Dark Matter, Consciousness, Abiogenesis, Measurement Problem, Commercial Fusion) and 6 complex global legal cases (O. J. Simpson, Hinterkaifeck, MH370, Amanda Knox, Jimmy Hoffa, Adnan Syed) with zero protocol errors (`E1–E3`).

### 🚀 Quick Start & Reproduce the Stress-Test (30 Seconds)
1. Copy the entire contents of `core/case-filter-v1.3-en.md` (or `modules/macro-os-audit-v0.2-en.md`) and paste it at the start of a fresh chat with any LLM.
2. Submit any claim, report, or contract clause using `RUN: [text]` (or `AUDIT: [text]`).
3. **Want to run the Blind Stress-Test yourself?** Paste this prompt right after loading the core `.md` file:
   ```text
   Run a strict protocol stress-test on the loaded core. Process 10 of the hardest problems across different fields of science (2 solved and 8 unsolved) and 6 of the most complex, unresolved legal cases in world history. Output a strict record card for each, followed by a final summary auditing your own carrier errors (E1–E3).
   ```
4. **You (the human user)** remain the **Keyholder** who closes verification windows. The AI (`carrier: AI`) never holds the key.

---

<a name="русский"></a>
## 🇷🇺 Русский: Экшены из Photoshop и 3D для управления вниманием ИИ

Меня зовут **Ирина Ветлугина**, я автор **метода датированной записи** и архитектуры **«Падежный фильтр» / «Макрос-ОС»**. Понятие **экшена** и привычку строить лёгкие, безотказные конвейеры без лишней нагрузки на систему я вынесла из работы в **Photoshop и 3D**. В нейросети мне удалось применить подобный метод — через школьные падежи как инструмент проверки реального действия (*«Мама мыла раму»*).

**«Падежный фильтр»** и экосистема **«Макрос-ОС»** — переносимые текстовые экшены. Представьте эти файлы как **операции (Actions) в Photoshop, но для текста**: вам не нужно писать код на Python, настраивать API или ставить плагины. Вы просто вставляете `.md`-файл в начало диалога с любой нейросетью (ChatGPT, Claude, Gemini, DeepSeek, Алиса), и он превращает модель в строгий измерительный прибор.

Вместо бесполезных просьб «не придумывай» система использует **падежи, вид глагола, залог, эвиденциальность и слоты времени** как жёсткую сетку управления вниманием ИИ — отделяя оплаченные дела (`E`) от пустых обещаний, манипуляций в пассивном залоге (`ПУСТОЕ КРЕСЛО`) и прогнозов без дат (`Ê`).

### 📂 Структура репозитория

#### 1. Флагманское ядро (`core/`)
* [`core/padezhny-filtr-v1.3.md`](core/padezhny-filtr-v1.3.md) — **«Падежный фильтр» `v1.3` (Русский):** Базовый движок системы. Проверяет записи по падежной сетке, требует датированных окон сверки `[t₁, t₂]`, отлавливает «самозванцев» (*Клетки 1, 13–15*) и легализует честный отказ `«неопознанный остаток»` вместо галлюцинаций (`ПРОГОН: [текст]`).
* [`core/case-filter-v1.3-en.md`](core/case-filter-v1.3-en.md) — **Case Filter Tool `v1.3` (English):** Полная англоязычная версия ядра (`RUN: [text]`).

#### 2. Модули и пакетные экшены «Макрос-ОС» (`modules/`)
Сменные текстовые плагины поверх базового ядра (как палитра инструментов в Photoshop):
* [`modules/macro-os-v3.0.md`](modules/macro-os-v3.0.md) — **Макрос-ОС `v3.0`: Единый центр аудита (All-in-One):** 8-слойный рентген текста + перевод «КАК НАДО» (`КОМБАЙН: [текст]`) и встроенный детектор галлюцинаций ИИ (`ЗЕРКАЛО`).
* [`modules/macro-os-audit-v0.2.md`](modules/macro-os-audit-v0.2.md) — **Пакетный экшен «Полный аудит» `v0.2` (Русский):** Объединённый 4-шлюзовый конвейер (`Граница творца → Залог → Вид глагола → Время/Сверка`) в одной карточке (`АУДИТ: [текст]`).
* [`modules/macro-os-audit-v0.2-en.md`](modules/macro-os-audit-v0.2-en.md) — **Batch Action "Full Audit" `v0.2` (English):** Англоязычный конвейер 4-в-1 (`AUDIT: [text]`).
* [`modules/voice-filter-v0.1.md`](modules/voice-filter-v0.1.md) — **Модуль №01: «Залоговый фильтр / Детектор ответственности»:** Вскрывает спрятанных исполнителей за страдательным залогом и возвратными глаголами *«сроки сдвинулись, решение принято»* (`ЗАЛОГ: [текст]`).
* [`modules/aspect-filter-v0.1.md`](modules/aspect-filter-v0.1.md) — **Модуль №02: «Видовой фильтр / Анти-вода для отчётов»:** Отсекает бесконечные процессы *«прорабатываем, улучшаем»* от закрытых результатов (`ВИД: [текст]`).
* [`modules/evidentiality-filter-v0.1.md`](modules/evidentiality-filter-v0.1.md) — **Модуль №03: «Эвиденциальный аудитор»:** Сортирует утверждения по 4 уровням источника — прямой замер прибора, официальный документ, пересказ или домысел (`ИСТОЧНИК: [текст]`).
* [`modules/contract-auditor-v0.1.md`](modules/contract-auditor-v0.1.md) — **Модуль №04: «Аудитор обязательств и ТЗ»:** Ищет ловушки в договорах, «резиновые» сроки, пассив в приёмке и имитацию работы без результата (`СДЕЛКА: [текст]`).
