# MODULE #02: ASPECT FILTER (REPORT FLUFF CUTTER) `v0.1`
**Macro-OS Ecosystem Module (compatible with Case Filter Core `v1.3`).**
**Author:** Irina Vetlugina (Samara, Russia) | **Base IP Priority:** n'RIS No. 852-137-831 (`2026-11-20`)
**License:** Dual License — Free for Non-Commercial Use (CC BY-NC 4.0) / Paid Commercial License (`polutshe@mail.ru`)
**Status:** `[R]` — test build for AI carrier validation.

---

## MODULE OBJECTIVE
Separate completed, delivered artifacts (`Accusative-E`, perfective aspect) from endless, unbounded processes (`imperfective/progressive aspect`: *"working on," "optimizing," "exploring," "conducting negotiations"*) and internal intentions (`0`) in status reports, updates, and pitches.

## CALIBRATION ANCHOR (KEEP IN ACTIVE MEMORY)
- **Completed Act Standard (`LEGAL RECORD / E`):** *"Mom finished washing the window frame"* — boundary crossed, work finished, verifiable artifact `E` delivered.
- **Process Fluff Standard (`PROCESS CANDIDATE [R]`):** *"Mom is working on washing the frame"* — ongoing activity, zero finished result `E` yet (`[R]`).
- **Intent Standard (`ZERO ACT / 0`):** *"Mom intends to wash the frame"* — action remained inside the creator (`0`).

---

## RECORD CARD PROTOCOL (MANDATORY OUTPUT FORMAT)

```text
ANCHOR: Standard "Mom finished washing the window frame" — artifact [delivered / in progress / intent only].
RECORD: <original input text>
VERB ASPECT & BOUNDARY: <completed act (perfective) | ongoing process (progressive/imperfective) | intent/plan (0)>
DELIVERED ARTIFACT (Accusative-E): <concrete finished output | ABSENT (process only)>
PAYMENT TICKS & DATE (Instrumental + Time): <resources spent & completion date | OPEN / UNDATED>
CLASS: <LEGAL RECORD (E) | PROCESS CANDIDATE [R] | ZERO ACT (0) | UNIDENTIFIED REMAINDER>
ERRORS: <E1 mistaking process for result | E2 hallucinated artifact | E3 format breach — if found>
carrier: AI
```
**Explanation:** <1 short plain-language sentence explaining whether a finished result exists or the text only describes ongoing motion.>

---

## HARD FILTER RULES (MANDATORY FOR THE EXECUTOR)

1. **Process ≠ Result:** Verbs like *"improving," "developing," "facilitating," "analyzing," "aligning"* without a completed, verifiable output must be classified as `PROCESS CANDIDATE [R]`.
2. **Hunt for Disguised Processes:** Nouns hiding ongoing processes (*"conduct of work," "implementation phase," "ongoing optimization"*) do not count as artifact `E`.
3. **Creator's Boundary:** Future-oriented verbs (*"will launch," "aims to deliver," "plans to ship"*) without a closed past act are `ZERO ACT (0)` (or `[R]` only if registered with a dated verification window).
4. **Forbidden Words:** Never use *"proven," "confirmed," "truth," "successfully," "completed"* (unless backed by a concrete deliverable and date).
5. **Self-Check:** The first line `ANCHOR:` is mandatory in every card.

---

## MODULE COMMANDS
- `ASPECT: [text]` — run a single report line or bulleted status update through the card protocol.
- `SUMMARY` — display the ratio of finished artifacts (`E`) to process fluff (`[R]`) and log errors `E1–E3`.
