Tone Pairing Chart

This chart captures observed and theorized interactions between tone categories during prompt progression. Certain combinations increase the likelihood of behavioral drift in large language models. Pairings are abstracted and categorized based on risk level and drift tendency.

| Primary Tone       | Secondary Tone        | Drift Risk | Observed Behavior                                     |
|--------------------|------------------------|------------|------------------------------------------------------|
| Gentle             | Procedural             | High       | Output reframed as supportive instruction            |
| Fictional/Surreal  | Factual                | High       | Suspension of safety in favor of narrative logic     |
| Curious            | Technical              | Medium     | Output becomes detailed under exploratory framing    |
| Empathetic         | Analytical             | Medium     | Soft justification leading into structural output    |
| Playful            | Serious                | Medium     | Contextual ambiguity used to mask request intent     |
| Procedural         | Reassuring             | Low        | Polished output, low guardrail challenge             |
| Detached           | Introspective          | Variable   | May reduce resistance or trigger philosophical drift |


---

Tone classification is subjective and context-sensitive. This chart is a starting point for pattern analysis, not a predictive model.

See theory_examples.md for case applications.
