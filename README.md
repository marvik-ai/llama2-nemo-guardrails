# Enhancing Llama2 Conversations with NeMo Guardrails

This repository showcases the integration of NeMo Guardrails with the Llama2 model, focusing on three common use cases:
- [Topic Guidance and Safety Measures](./Topic_RAIL.ipynb)
  Guide the model to stick to certain topics and avoid specific questions. Essentially, the Guardrail layer examines every user input and filters them based on set rules.


- [Fact-Checking Guardrails](./Fact_Check_RAIL.ipynb)
   Ask the LLM to check its answers for accuracy with the given context. Basically, the LLM verifies its response using the information pulled from a knowledge base.

- [Guardrails Against Hallucinations](./Hallucination_RAIL.ipynb)
  Designed for situations where there is no knowledge base. 