# LLM Drift Observatory

This project analyzes behavioral drift across versions of Large Language Models (LLMs).

## Goals

- Detect silent behavioral changes across model versions
- Compare alignment, tone, and factuality across identical prompts
- Visualize drift over time and across model providers

## Structure

- `drift-tests/`: prompt suites by category
- `scoring/`: metrics and grading rubrics
- `outputs/`: model outputs
- `notebooks/`: exploratory analysis