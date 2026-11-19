# "Case Filter" Tool (Падежный фильтр) v1.2

**The Dated Record Method. A portable carrier-tool for verifying statements in dialogue with AI.**

* **Author of the method:** Irina Vetlugina (Samara, Russia)
* **Key Holder:** User (the human conducting verification in dialogue with AI)
* **Status:** `[Р]` — working version (tested in Runs #1–#5)

---

## What is this tool?

Without a formula, grammatical cases are just grammar. With a formula, they become a strict verification filter for records, hypotheses, and statements:
* **"Mom washed the frame"** — passes (there is an executor, an action, an object, and payment in ticks).
* **"The frame washed mom"**, **"the frame washed the frame"**, **"mom dreamed of washing"** — fail: the executor's seat is paid with the wrong currency, or the creator's boundary was never crossed.

The tool **does not solve problems** for the user and does not seek "absolute truth." It acts as a strict accountant: it parses records about events and problems, separates actual acts from forecasts, and catches substitutions (the "Zoo" of errors).

## Quick Start

1. Open the file [`case-filter-v1.2-en.md`](./case-filter-v1.2-en.md) and copy its entire content.
2. Paste the text at the very beginning of a new dialogue with any LLM (ChatGPT, Claude, Gemini, DeepSeek, etc.).
3. Submit any record or list of statements using the command:
   ```text
   RUN: [text of your record]
   ```
4. Receive a structured **record card** according to the protocol along with a brief plain-language explanation.

> **Important:** AI acts strictly as a carrier-executor. The verification key for dated windows always remains with the human.

## Core Commands

* `RUN: [text]` — parses a record into a protocol card with a mandatory brief explanation.
* `FORECAST: [Ê] window [date]` — registers a candidate before the act takes place.
* `VERIFY: [Ê against fact E]` — closes a bet upon reaching the dated window.
* `SUMMARY` — outputs accumulated operator/model errors (`O1–O3`) for the session.
* `ABLATION: [cell]` — tests filter discipline by excluding a specified cell.

## Examples & Test Logs

The [`/runs`](./runs) folder contains test protocols of the tool applied to complex scientific problems (Fermat's Last Theorem, P vs NP, Riemann Hypothesis, Higgs Boson, etc.). See [`run-science-problems-en.md`](./runs/run-science-problems-en.md).

## How to Contribute

The tool requires **independent blind runs** across different language models. 
If you conduct a run and spot a failure in classification (`O1`), reading (`O2`), or recording (`O3`), please open an **Issue** in this repository and attach the dialogue log.
