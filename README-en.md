# "Case Filter" Tool v1.2 (Падежный фильтр)

**The Dated Record Method. A portable carrier-tool for verifying claims and reducing hallucinations in dialogue with AI.**

Author: **Irina Vetlugina** (Samara, Russia).  
Deposited with **n'RIS**: Registration No. `852-137-831` dated `20.11.2026`.

---

## License & Terms of Use (Dual License)

* **For Individuals — FREE (Non-Commercial):** Free to use, copy, and share for personal, educational, and non-commercial research purposes, provided the author's name and n'RIS deposit notice remain intact.
* **For Organizations & Businesses — PAID LICENSE REQUIRED:** Any use by legal entities, entrepreneurs, or for commercial purposes (internal corporate workflows, R&D, analytics, SaaS/AI integration, paid training, or consulting) is strictly prohibited without a separate paid commercial license agreement from the copyright holder.
* **Full terms:** see [`LICENSE`](./LICENSE).
* **Commercial licensing & inquiries:** `polutshe@mail.ru`

---

## Why Use Case Filter?

Large Language Models tend to present hypotheses and speculation with the same confidence as verified facts. Case Filter shifts AI from "plausible text generation" into a strict record-accounting protocol:

* **Separates facts from hypotheses:** audits every record for its framework Ω(T), paid act, institutional position σ(O), and dated verification window.
* **Bans ungrounded certainty:** AI is prohibited from using words like *"confirmed"*, *"proven"*, or *"truth"* — only strict protocol statuses (`legal record`, `[R] candidate`, `left edge`, `cell 1`, `false removed`).
* **Legitimizes refusal to guess:** when external verification criteria are missing, AI must assign `unidentified remainder` instead of hallucinating.
* **Separates roles:** AI acts strictly as the carrier-executor, while the human user remains the "key holder" responsible for time-based verification.

---

## Quick Start (30 Seconds)

1. Open [`case-filter-v1.2-en.md`](./case-filter-v1.2-en.md) and copy the entire file.
2. Paste it at the beginning of a new chat with any modern LLM (ChatGPT, Claude, Gemini, DeepSeek, etc.).
3. Submit any claim or hypothesis using the command:
   ```text
   RUN: [your claim, news item, or hypothesis]
   ```

### Core Commands
* `RUN: [text]` — analyze a record using the strict protocol card and explanation.
* `VERIFY: [Ê against fact E]` — verify a prediction against a dated window.
* `SUMMARY` — output session summary and check for O1–O3 protocol errors.
* `FORECAST: [Ê] window [date]` — register a candidate prior to verification.
* `ABLATION: [cell]` — test filter discipline by excluding a specific cell.

---

## Repository Contents

* [`case-filter-v1.2-en.md`](./case-filter-v1.2-en.md) — main portable protocol file (English).
* [`case-filter-v1.2.md`](./case-filter-v1.2.md) — Russian version of the protocol.
* [`run-science-problems-en.md`](./run-science-problems-en.md) — benchmark run of 10 major solved and unsolved science problems.
* [`LICENSE`](./LICENSE) — full Dual License terms (RU / EN).

