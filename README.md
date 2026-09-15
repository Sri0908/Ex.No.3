# Ex. No. 3 — Scenario-Based Report Development Utilizing Diverse Prompting Techniques

# Date : 31-07-2026
# REG NO : 212223060270

## Aim
To write prompts for the following prompt engineering types and evaluate them:
1. Straightforward Prompts
2. Tabular Format Prompting
3. Preceding Question Prompting
4. Missing Word Prompting

## Problem Statement / Explanation
Prompt engineering is the practice of designing inputs to a generative AI/LLM system so that it produces the most accurate, relevant, and useful output. Different prompting styles suit different goals — a direct instruction works well for simple factual recall, a tabular prompt is ideal when structured comparison is needed, a preceding-question prompt frames context before asking for an explanation, and a missing-word (cloze-style) prompt tests or elicits precise, targeted recall. This report takes one use case — **explaining core science and technology concepts to a learner** — and demonstrates it across all four prompt types, evaluating the output quality of each.

## Algorithm / Procedure

**Step 1: Straightforward Prompts**
Give the model a direct, unambiguous instruction with no additional framing, and evaluate the directness and conciseness of the response.

**Step 2: Tabular Format Prompting**
Instruct the model to structure its output as a table with defined columns, and evaluate clarity and ease of comparison.

**Step 3: Preceding Question Prompting**
Pose a question first, followed by a request for explanation, to give the model explicit context before the detailed answer, and evaluate depth and relevance.

**Step 4: Missing Word Prompting**
Give the model a sentence with a blank ("____") and ask it to complete it, and evaluate factual accuracy and precision.

**Step 5: Evaluation**
Compare outputs from all four types against the criteria: *clarity, structure, accuracy, and usefulness*, and record observations.

---

## 1. Straightforward Prompts

**Prompt A:** "Define photosynthesis in one sentence."
**Generated Output:** Photosynthesis is the process by which green plants, algae, and some bacteria convert sunlight, water, and carbon dioxide into glucose and oxygen using chlorophyll.

**Prompt B:** "List three advantages of electric vehicles."
**Generated Output:**
1. Zero tailpipe emissions, reducing local air pollution.
2. Lower running costs due to cheaper electricity compared to fuel and fewer moving parts to maintain.
3. Quieter operation and smoother acceleration compared to internal combustion engine vehicles.

**Evaluation:** Straightforward prompts produce quick, concise, directly usable answers. Best suited for simple fact retrieval or short lists, but they offer little structure for comparing multiple attributes at once.

---

## 2. Tabular Format Prompting

**Prompt A:** "Compare and contrast AC and DC current in a table."

**Generated Output:**

| Feature | AC (Alternating Current) | DC (Direct Current) |
|---|---|---|
| Direction of flow | Periodically reverses direction | Flows in one constant direction |
| Common source | Power grid, generators | Batteries, solar cells |
| Typical use | Household and industrial power supply | Electronics, batteries, low-voltage devices |
| Transmission | Efficient over long distances (via transformers) | Less efficient over long distances |
| Voltage conversion | Easy, using transformers | More complex, requires converters |

**Prompt B:** "Provide a table listing five programming languages, their paradigms, and one use case each."

**Generated Output:**

| Language | Primary Paradigm | Common Use Case |
|---|---|---|
| Python | Multi-paradigm (OOP, procedural, functional) | Data science and automation |
| Java | Object-Oriented | Enterprise backend systems |
| JavaScript | Multi-paradigm (event-driven, OOP, functional) | Web front-end development |
| C | Procedural | Systems and embedded programming |
| SQL | Declarative | Database querying and management |

**Evaluation:** Tabular prompting excels when the goal is side-by-side comparison of multiple items across shared attributes. It significantly improves readability over prose for multi-point comparisons but is unnecessary for single-fact answers.

---

## 3. Preceding Question Prompting

**Prompt A:** "Why is climate change a global concern? Explain how greenhouse gases contribute to global warming."

**Generated Output:** Climate change is a global concern because rising global temperatures disrupt weather patterns, raise sea levels, and threaten ecosystems, agriculture, and human health across every region — no country is unaffected. Greenhouse gases such as carbon dioxide, methane, and nitrous oxide trap heat from the sun in the Earth's atmosphere rather than letting it radiate back into space, creating a "greenhouse effect." As human activities like fossil fuel combustion and deforestation increase the concentration of these gases, more heat is trapped, driving up average global temperatures over time.

**Prompt B:** "How do vaccines work? Describe the process of immunization in simple terms."

**Generated Output:** Vaccines work by training the body's immune system to recognize and fight a specific pathogen without causing the actual disease. A vaccine typically introduces a weakened, inactivated, or partial form of a pathogen (or instructions to build a harmless piece of it). The immune system responds by producing antibodies and memory cells. If the real pathogen is encountered later, the immune system recognizes it quickly and mounts a fast, effective defense, preventing or reducing illness.

**Evaluation:** Framing a question before requesting an explanation guides the model toward a more contextual, motivated response — it explains *why* something matters before *how* it works, producing richer, more pedagogically structured answers than a bare instruction.

---

## 4. Missing Word Prompting

**Prompt A:** "The capital of France is ____."
**Generated Output:** The capital of France is **Paris**.

**Prompt B:** "In photosynthesis, plants absorb sunlight to produce ____."
**Generated Output:** In photosynthesis, plants absorb sunlight to produce **glucose (and oxygen)**.

**Evaluation:** Missing-word (cloze) prompting is highly effective for testing or eliciting precise factual recall with minimal output — ideal for quizzes, flashcards, or verifying a model's grasp of a specific fact. It is not suited to open-ended or explanatory tasks.

---

## Comparative Summary

| Prompt Type | Best For | Output Style | Limitation |
|---|---|---|---|
| Straightforward Prompts | Quick facts, short lists | Concise, direct | Limited structure for comparisons |
| Tabular Format Prompting | Multi-attribute comparisons | Structured, scannable | Overkill for single facts |
| Preceding Question Prompting | Contextual explanations | Detailed, motivated | Longer, less concise |
| Missing Word Prompting | Precise factual recall | Minimal, targeted | Not suited for explanations |

## Conclusion
Each prompting technique serves a distinct purpose depending on the desired outcome. Straightforward prompts are ideal for quick, direct answers; tabular prompting is best for structured comparisons; preceding-question prompting produces richer, context-aware explanations; and missing-word prompting is most effective for precise, targeted recall. Selecting the right prompting style for a given task materially improves the clarity, accuracy, and usefulness of generated AI output.

## Result
Thus, the prompts for Straightforward Prompts, Tabular Format Prompting, Preceding Question Prompting, and Missing Word Prompting were written and executed successfully, and the generated outputs were evaluated.
