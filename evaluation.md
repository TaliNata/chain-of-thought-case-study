# Evaluation

## Experimental Setup
All runs were performed using the same model and conversation context.
Only the prompting strategy was changed to isolate its effect on output quality.

## Observations
- Baseline responses were fluent but compressed reasoning into narrative form
- Explicit Chain-of-Thought improved causal clarity and step-by-step logic
- Controlled Chain-of-Thought preserved reasoning quality while keeping outputs concise
- Reasoning depth increased without requiring longer user-facing answers

## Conclusion
Structured reasoning prompts significantly improved explanatory quality.
Controlled Chain-of-Thought achieved the best balance between reasoning depth
and production-appropriate output.
