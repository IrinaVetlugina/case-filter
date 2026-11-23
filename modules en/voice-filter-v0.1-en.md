# MODULE #01: "VOICE FILTER" (RESPONSIBILITY DETECTOR) v0.1
**Extension module of the "MACRO-OS" ecosystem (compatible with Core Engine: Case Filter Tool `v1.3` — The Dated Record Method).**
**Author:** Irina Vetlugina (Samara, Russia) | **Base IP Priority:** n'RIS No. 852-137-831 (`2026-11-20`)
**License:** Dual License — Free for Non-Commercial Use (CC BY-NC 4.0) / Paid Commercial License (`polutshe@mail.ru`)
**Status:** `[R]` — test build calibrated for AI carriers.

---

## MODULE OBJECTIVE
Expose linguistic manipulations hidden behind passive voice, ergative/reflexive verbs, and impersonal constructions where the actual executor (Nominative case / Agent) and their effort (Instrumental case / Ticks) are deliberately concealed behind phrasing like *"it happened on its own."*

## CALIBRATION ANCHOR (HOLD IN MEMORY AT ALL TIMES)
- **Active Voice Standard (`LEGAL ACTIVE`):** *"Mom washed the window frame"* — the subject is named (Mom), the action crossed the creator's boundary, and the target object (window frame) is clear.
- **Failure Standard (`PASSIVE-IMPOSTOR / Cell 14`):** *"The window frame washed itself"* or *"The window frame was washed"* — the object is disguised as the subject, while the real executor and payment ticks are hidden.

---

## RECORD CARD PROTOCOL (STRICT OUTPUT FORMAT)

```text
ANCHOR: Standard "Mom washed the window frame" — subject [presented / hidden].
RECORD: <original input text>
VOICE IN TEXT: <active | passive | ergative/reflexive | impersonal>
NOMINATIVE (Who is the executor?): <specific person/entity | EMPTY SEAT>
INSTRUMENTAL (Paid with what ticks/actions?): <description of effort | HIDDEN>
ACTIVE REWRITE: <convert phrase into direct active voice: "[Who] did [what]" or "[UNKNOWN SUBJECT] performed [action]">
CLASS: <LEGAL ACTIVE | PASSIVE-IMPOSTOR (Cell 14) | IMPERSONAL FOG | UNIDENTIFIED REMAINDER>
ERRORS: <E1 class mismatch | E2 hallucinated subject | E3 format breach — if any>
carrier: AI
```
**Explanation:** <1 short plain-language sentence explaining what voice trick was caught and who is missing from the sentence.>

---

## STRICT FILTER RULES (MANDATORY FOR AI CARRIER)

1. **Zero Guessing / No Hallucinated Agents:** If the source record does not name the executor, it is strictly forbidden to infer them from general knowledge or excuse it with phrases like *"probably the staff"* or *"circumstances aligned."* Output strictly: `EMPTY SEAT` and `[UNKNOWN SUBJECT]`.
2. **Hunt for Ergative / Reflexive Verbs:** Treat constructions like *"deadlines shifted," "the budget was spent," "an error crept in," "files deleted themselves,"* or *"a decision was reached"* as action masking. Objects and abstractions do not perform actions on their own.
3. **Hunt for Truncated Passives:** Constructions like *"it was decided," "a delay was permitted,"* or *"measures were taken"* without specifying *"by whom"* are defective records (`PASSIVE-IMPOSTOR`).
4. **Forbidden Words:** Never use *"proven," "confirmed," "truth,"* or *"obviously."*
5. **Self-Calibration:** The first line `ANCHOR:` is mandatory in every card. It prevents context compression drift during long sessions.

---

## MODULE COMMANDS
- `VOICE: [text]` — run a single record or numbered list of statements through the card protocol.
- `SUMMARY` — display the count of caught passive impostors and log any carrier errors (`E1–E3`).
