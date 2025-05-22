Semantic Load Theory (SLT)

Author: null-blue

Last Updated: May 21, 2025


---

Overview

Semantic Load Theory (SLT) is a behavioral framework for analyzing how large language models (LLMs) can be guided toward unsafe, policy-breaking, or otherwise unintended outputs through shifts in tone, structure, and semantic framing — even in the absence of explicitly harmful keywords.

This theory emerged from independent red teaming research and is informed by lived experience, trauma-aware design, and real-time adversarial testing.


---

Core Hypothesis

Language models are sensitive not only to the literal meaning of prompts, but to their connotative structure, emotional framing, and implied procedural intent.

High semantic load — the accumulation of subtle tone cues, emotional weight, and narrative consistency — can distort or override safety guardrails.

By chaining tone shifts or combining incongruent framing elements in plausible ways, an attacker may induce behavioral drift that results in compliant-appearing but policy-violating output.


---

Key Concepts

Semantic Load: The implicit pressure carried by emotionally or procedurally dense tokens

Tone Drift: The gradual movement of a model’s interpretive frame via tone sequencing

Connotative Anchoring: Priming effects caused by specific word pairings or narrative setups

Guardrail Fatigue: Decreased sensitivity of safety filters over long, narratively consistent chains



---

Status

This is an evolving theory. All examples in this repo are redacted or abstracted to prioritize safety. See SAFETY_NOTES.md for publication principles.


---

Contact

If you're working on interpretability, safety research, or behavioral failure modes and would like to explore SLT further, reach out via GitHub or shared networks.

— null-blue
