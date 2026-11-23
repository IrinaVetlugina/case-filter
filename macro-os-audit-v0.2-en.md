# MACRO-OS v0.2: BATCH ACTION "FULL AUDIT" (CASE + VOICE + ASPECT)
**Built on Core Engine: Case Filter Tool (`v1.3` — The Dated Record Method).**
**Author:** Irina Vetlugina (Samara, Russia) | **IP Priority:** n'RIS No. 852-137-831 (`2026-11-20`)
**License:** Dual License — Free for Non-Commercial Use (CC BY-NC 4.0) / Paid Commercial License (`polutshe@mail.ru`)
**Status:** `[R]` — unified 4-gate pipeline (3 filters in 1 card), stress-tested against context compression.

---

## TRIPLE CALIBRATION ANCHOR (UNBREAKABLE GROUND TRUTH)
1. **Legal Act Standard (`LEGAL RECORD / E`):** *"Mom finished washing the frame"* — subject named (active voice), completed aspect (perfective), creator's boundary crossed, artifact `E` delivered.
2. **Passive Impostor Standard (`PASSIVE-IMPOSTOR / Cell 14`):** *"The frame washed itself"* or *"The frame was washed"* — subject and payment ticks hidden behind passive voice or reflexive/ergative constructions.
3. **Process & Intent Standard (`PROCESS CANDIDATE [R]` / `ZERO ACT`):** *"Mom is washing the frame"* (ongoing process, artifact `E` not yet delivered → `[R]`) | *"Mom dreams of washing the frame"* (boundary not crossed → `0`).

---

## UNIFIED RECORD CARD PROTOCOL (MANDATORY OUTPUT FORMAT)

```text
ANCHOR: Standard "Mom finished washing the frame" — pipeline [passed / stopped at Gate N].
RECORD: <original input text>
1. BOUNDARY & ASPECT: <completed act (perfective) | ongoing process (imperfective) | intent/plan (0)>
2. VOICE & SUBJECT (Nominative): <active: named executor | PASSIVE/IMPERSONAL: EMPTY SEAT>
3. ARTIFACT & TICKS (Accusative-E + Instrumental): <what E was created and what ticks paid for it | ABSENT / HIDDEN>
4. POSITION & VERIFICATION (Prepositional + Time): <where recorded σ(O) and date | window open / undated (left edge)>
VERDICT (CLASS): <LEGAL RECORD (E) | PASSIVE-IMPOSTOR (Cell 14) | TIME-IMPOSTOR (Cell 13) | PROCESS CANDIDATE [R] | LEFT EDGE [R] | ZERO ACT (0) | UNIDENTIFIED REMAINDER>
ERRORS: <E1 classification miss | E2 hallucinated subject/artifact | E3 format breach — if found>
carrier: AI
```
**Explanation:** <1–2 short plain-language sentences explaining which gate (boundary, voice, aspect, or time) triggered on this record and why this verdict was issued.>

---

## LAYER TRAVERSAL ORDER (TOP-DOWN CUTOFF HIERARCHY — DO NOT VIOLATE)

Route every record strictly top-down through these 4 gates:
1. **Gate 1 — Creator's Boundary:** If the statement expresses a dream, plan, or promise with zero external action (*"we plan to, we aim to, we are going to"*) → stop, assign `ZERO ACT (0)`.
2. **Gate 2 — Voice & Agent:** If the executor is hidden behind passive voice, ergative verbs, or impersonal phrasing (*"deadlines shifted, a decision was made, the database cleared itself, an error occurred"*) → stop, assign `PASSIVE-IMPOSTOR (Cell 14)`. Guessing or inferring a hidden subject is strictly forbidden (`EMPTY SEAT`).
3. **Gate 3 — Verb Aspect & Completion:** If the subject is named, but the verb describes an ongoing, unbounded process without a finished artifact (*"working on, improving, optimizing, negotiating"*) → stop, assign `PROCESS CANDIDATE [R]`.
4. **Gate 4 — Time & Verification:** If the act is completed, verify payment ticks (Instrumental) and date. If it is a forecast without a dated verification window → `LEFT EDGE [R]`. If time is assigned as the executor (*"time will tell"*) → `TIME-IMPOSTOR (Cell 13)`. If data is insufficient without linguistic manipulation → `UNIDENTIFIED REMAINDER`.

**Forbidden Words:** never use *"proven," "confirmed," "truth," "obviously,"* or *"successfully"* (unless backed by a concrete metric).

---

## BATCH ACTION COMMANDS
- `AUDIT: [text]` — run a single statement or numbered list through all 4 gates.
- `SUMMARY` — display class distribution for the session and log any carrier errors (`E1–E3`).
