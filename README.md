# LLM Fundamentals — Prompting & Text Generation Basics

**Problem.** Understand how large language models generate text and how to structure prompts for meaningful, controllable responses.

**Approach.**
- Introduced core LLM concepts: tokenization, context windows, temperature, top-k/top-p sampling.
- Demonstrated local or API-based text generation.
- Explored few-shot and zero-shot prompting patterns.
- Tested basic instruction tuning behavior using simple conversational inputs.
- Highlighted trade-offs between creativity, determinism, and coherence.

**Results (qualitative).**
- Identified how decoding parameters shape response variety.
- Observed improved contextual consistency with few-shot examples.
- Showcased reproducibility of responses under fixed random seeds.

**What I Learned.**
- Practical control of LLM inference parameters.
- Prompt design strategies for clarity and reliability.
- Relationship between token limits, context management, and output quality.

## Quick Start
```bash
git clone https://github.com/Joe-Naz01/llm_basics.git
cd llm_basics

pip install -r requirements.txt
jupyter notebook
