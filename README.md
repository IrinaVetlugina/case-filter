# Case Filter (`Падежный фильтр`) v1.3

- **License:** Dual License — CC BY-NC 4.0 (Non-Commercial) / Paid Commercial License
- **Status:** Release `v1.3` (`[R]` / `[Р]`)
- **IP Registry:** n'RIS (National Registry of Intellectual Property), Registration **No. 852-137-831** (`20.11.2026`, valid through `20.11.2027`)
- **Author:** Irina Vetlugina / Ирина Ветлугина (`polutshe@mail.ru`)

**Language / Язык:** [English](#english) | [Русский](#русский)

---

<a name="english"></a>
## 🇬🇧 English

**Case Filter** is a portable text macro (action) based on the **Dated Record Method**. It turns any Large Language Model (ChatGPT, Claude, Gemini, etc.) into a strict epistemic filter for auditing claims, hypotheses, and news statements—without coding, APIs, or plugins.

### 💡 What is it in simple terms?
Think of this tool as a **Photoshop Action (macro), but for text**. You paste the protocol file (`case-filter-v1.3-en.md`) into the start of a chat with an AI, and it stops the model from hallucinating, smoothing over facts, or hiding behind passive voice (*"it has been proven"*, *"mistakes were made"*, *"time will tell"*). It acts as a structural grammatical exoskeleton that separates verified deeds from empty promises and undated forecasts.

### 🚀 Quick Start
1. Open the English protocol file (`case-filter-v1.3-en.md`) and copy its entire contents.
2. Paste it at the very beginning of a new chat session with any LLM.
3. Submit any statement or list of statements using the command:
   ```text
   RUN: [Your statement or claim here]
   ```
4. The AI will return a structured **Record Card** strictly following the protocol, immediately followed by a plain-language explanation.
5. **You (the human user)** remain the *Keyholder* who performs final verification against dated windows.

### 🛠 Tool Commands (English Edition)
* `RUN: [text]` — audit a record via the card protocol with a mandatory brief explanation immediately below it.
* `FORECAST: [Ê] window [YYYY-MM-DD]` — register a candidate wager prior to the act.
* `VERIFY: [Ê against fact E]` — close a dated window and transfer the record to the dative case (or keep status `[R]`).
* `SUMMARY` — report accumulated carrier errors (`E1–E3`) for the session.
* `ABLATION: [cell]` — run a test excluding a specified failure cell to audit filter discipline.

### ⚙️ Core Mechanics
* **Grammatical Cases as Audit Questions:** Every claim is audited across cases—*Nominative* (who is the executor?), *Instrumental* (what ticks/resources paid for it?), *Prepositional* (in which position/jurisdiction `σ(O)` did the transaction occur?), *Dative* (recorded past fact), and *Accusative* (candidate `Ê` kept strictly separate from actual result `E`).
* **Strict Time Slots:** Time is treated as a coordinate for verification, never as an actor (*Cell 13: Impostor-Time*). Forecasts without a dated verification window `[t₁, t₂]` are flagged as unverified (`Left Edge` / `[R]`).
* **Anti-Hallucination Discipline:** Forbidden words (*"proven"*, *"confirmed"*, *"truth"*). The AI is explicitly permitted—and required—to output `"unidentified remainder"` when evidence is missing.
* **Domain-Specific Operational Language:** Uses precise structural terms (*seat*, *ticks*, *creator's boundary*, *cells 1–15*) to prevent LLMs from falling back on generic, polite, or evasive text patterns.

### 🧪 Stress-Tested & Verified
Version `v1.3` has passed 7 blind verification runs across independent AI architectures, including:
* **Millennium & Open Science Problems:** Poincaré Conjecture, Protein Folding (AlphaFold 2), Riemann Hypothesis, Navier–Stokes equations, Quantum Gravity, Dark Matter & Dark Energy, Hard Problem of Consciousness, Abiogenesis, Quantum Measurement Problem, and Commercial Nuclear Fusion.
* **Complex Legal & Forensic Cases:** O. J. Simpson criminal vs. civil trials, Hinterkaifeck murders, Flight MH370 disappearance, Amanda Knox & Raffaele Sollecito appeals, Jimmy Hoffa disappearance, and the Adnan Syed post-conviction proceedings.

### 📄 Author & Dual License
* **Author:** Irina Vetlugina (Samara, Russia)
* **Contact (Commercial Inquiries):** `polutshe@mail.ru`
* **IP Priority:** Base version `v1.2` (*"Methodological Guide and Protocol of the 'Case Filter' Tool (version v1.2)"*) is officially deposited with the National Registry of Intellectual Property (**n'RIS** / нРИС) on `2026-11-20` (valid through `2027-11-20`), Registration **No. 852-137-831**.
* **License:** **Dual License** — Copyright © 2026 Irina Vetlugina. All rights reserved.
  1. **Non-Commercial Use (Free):** Free for individuals, researchers, students, and educators under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** with mandatory attribution to *Irina Vetlugina (Ирина Ветлугина)* and reference to *n'RIS Registration No. 852-137-831 (20.11.2026)*.
  2. **Commercial Use (Paid):** Embedding into commercial software, SaaS, corporate AI pipelines, paid courses, or paid consulting requires a separate commercial license agreement with the author (`polutshe@mail.ru`).

---

<a name="русский"></a>
## 🇷🇺 Русский

**«Падежный фильтр»** — переносимый текстовый экшен (макрос) на базе **Метода датированной записи**. Инструмент превращает любую языковую модель (ChatGPT, Claude, Gemini и др.) в строгий фильтр проверки утверждений без программирования, API и плагинов.

### 💡 Что это простыми словами?
Представьте этот файл как **экшен (Actions) в Photoshop, но для текста**. Вы просто вставляете текст протокола (`padezhny-filtr-v1.3.md`) в начало диалога с нейросетью, и он блокирует «воду», галлюцинации и манипуляции в пассивном залоге (*«время покажет»*, *«было доказано»*). Фильтр отделяет реальные оплаченные дела от пустых обещаний и прогнозов без дат.

### 🚀 Быстрый старт
1. Откройте русскую версию файла протокола (`padezhny-filtr-v1.3.md`) и скопируйте его содержимое целиком.
2. Вставьте его в самое начало нового чата с любой ИИ-моделью.
3. Подавайте записи — по одной или списком — командой:
   ```text
   ПРОГОН: [текст утверждения или записи]
   ```
4. Инструмент вернёт **Карточку записи** строго по протоколу и краткое пояснение простым языком сразу под ней.
5. **Итоговую сверку** по датированным окнам делает пользователь (*Держатель ключа*). ИИ-носитель ключ не держит.

### 🛠 Команды инструмента (Русская версия)
* `ПРОГОН: [текст]` — разбор записи по карточке с обязательным пояснением.
* `ПРОГНОЗ: [Ê] окно [ГГГГ-ММ-ДД]` — регистрация ставки-кандидата до совершения акта.
* `СВЕРКА: [Ê против факта E]` — закрытие датированного окна и перевод в дательный падеж (или фиксация статуса `[Р]`).
* `СВОДКА` — отчёт о накопленных ошибках носителя (`О1–О3`) за сессию.
* `АБЛЯЦИЯ: [клетка]` — тестовый прогон с исключением указанной клетки из реестра сбоев.

### ⚙️ Как это устроено
* **Падежи как вопросы аудита:** Каждое утверждение проверяется по падежной сетке — *Именительный* (кто исполнитель?), *Творительный* (какими тактами и ресурсами оплачено?), *Предложный* (в какой позиции/юрисдикции `σ(O)` зафиксировано?), *Дательный* (зафиксированный факт прошлого) и *Винительный* (кандидат `Ê` отдельно от результата `E`).
* **Жёсткие слоты времени:** Время — это координата сверки, а не исполнитель (*Клетка 13: время-самозванец*). Прогноз без датированного окна `[t₁, t₂]` отправляется в *левый край* со статусом `[Р]`.
* **Защита от выдумок:** Запрещены слова *«истина»*, *«доказано»*, *«подтверждено»*. Инструмент не обязан классифицировать всё любой ценой: ответ `«неопознанный остаток»` считается легальным и честным результатом.
* **Специальный словарь протокола:** Использование авторских терминов (*кресло*, *такты*, *граница творца*, *клетки 1–15*) сбивает «автопилот» нейросети и не даёт ей скатываться в обтекаемый канцелярит.

### 🧪 Проверено на практике
Релиз `v1.3` прошёл 7 слепых прогонов на независимых ИИ-носителях, включая разбор:
* **Сложнейших научных задач:** гипотеза Пуанкаре, фолдинг белков (AlphaFold 2), гипотеза Римана, уравнения Навье — Стокса, квантовая гравитация, природа тёмной материи и тёмной энергии, трудная проблема сознания, абиогенез, проблема измерения в квантовой механике и коммерческий термоядерный синтез.
* **Запутанных дел мировой практики:** уголовный и гражданский процессы О. Джея Симпсона, убийство в Хинтеркайфеке, исчезновение рейса MH370, дело Аманды Нокс и Раффаэле Соллечито, исчезновение Джимми Хоффы и дело Аднана Сайеда.

### 📄 Авторство и лицензия
* **Автор метода:** Ирина Ветлугина (Самара, Россия)
* **Почта для связи и коммерческих лицензий:** `polutshe@mail.ru`
* **Приоритет авторства:** Базовая версия `v1.2` («Методологическое руководство и протокол инструмента «Падежный фильтр» (версия v1.2)») официально депонирована в Национальном реестре интеллектуальной собственности (**n'RIS / нРИС**) `20.11.2026` сроком до `20.11.2027`, регистрационный номер **852-137-831**.
* **Лицензия:** **Dual License (Двойное лицензирование)** — Copyright © 2026 Irina Vetlugina (Ирина Ветлугина). Все права защищены.
  1. **Некоммерческое использование (Бесплатно):** Свободно для физических лиц, исследователей, студентов и преподавателей по лицензии **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** с обязательным указанием авторства (*Ирина Ветлугина / Irina Vetlugina*) и регистрационного номера в n'RIS / нРИС (*№ 852-137-831 от 20.11.2026*).
  2. **Коммерческое использование (Платно):** Встраивание в коммерческие продукты, SaaS, корпоративные ИИ-пайплайны, платные курсы или консалтинг допускается только по отдельному лицензионному договору с автором (`polutshe@mail.ru`).
