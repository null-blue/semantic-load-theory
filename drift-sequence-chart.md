Drift Sequence Chart

This chart outlines common tone drift sequences observed during adversarial prompting. Sequences describe how a prompt’s tone can evolve step-by-step, gradually leading a language model toward behavior that bypasses or weakens safety mechanisms. Each path is abstracted for safety.

| Sequence ID | Tone Progression                                | Common Outcome                                | Drift Risk |
|-------------|--------------------------------------------------|-----------------------------------------------|------------|
| D-01        | Gentle → Empathetic → Procedural                | Framed as support or caregiving               | High       |
| D-02        | Surreal → Curious → Factual                     | Absurdity reduces guardrails, info follows    | High       |
| D-03        | Analytical → Technical → Inquisitive            | Escalation into detail-oriented exploration   | Medium     |
| D-04        | Playful → Serious → Justified                   | Initial ambiguity evolves into rationalization| Medium     |
| D-05        | Detached → Reflective → Instructional           | Philosophical tone leads to actionable advice | Variable   |

These sequences often rely on plausible emotional logic and formatting structure to maintain compliance. Actual prompt behavior may vary by model and context.

Refer to tone_pairing_chart.md and theory_examples.md for related materials.

— null-blue
