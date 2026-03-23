# Agent Research

This repository explores agentic AI systems through iterative development and rigorous evaluation.

## Directory Structure

### `prototypes/`

**Purpose:** Rapid local testing and iteration

- Loads quantized/lightweight HuggingFace models for quick debugging
- Tests agent reasoning, routing logic, and prompt design
- Fast feedback loop for development and refinement
- Minimal computational overhead

### `evaluations/`

**Purpose:** Full evaluation on finalized methodologies

- Uses API calls to production-grade LLM models (e.g., Claude, GPT-4, Gemini)
- Runs comprehensive benchmarks and metrics collection
- Executed only after prototypes are verified and methodology is locked
- Generates final research results and comparative analysis

## Workflow

1. **Develop & Debug** → `prototypes/` (local, fast iteration)
2. **Finalize & Lock** → Methodology and prompts approved
3. **Evaluate & Report** → `evaluations/` (API-based, final results)
