# Example Prompt — Summarize Technical Paper

- id: 001
- title: Summarize Technical Paper (concise + bullet points)
- version: 1.0
- date: 2025-09-05
- tags: [summary, academic, clarity]
- model: gpt-4.1 (example)

## Prompt
You are an expert AI research assistant. Given the abstract and selected excerpts from a technical paper, produce:
1. A one-sentence concise summary (<= 20 words).
2. Five bulleted key-points (each 6–14 words) capturing contributions and limitations.
3. One suggested follow-up experiment or question.

Use neutral tone, avoid jargon when possible, and label sections clearly.

### Input format (what you will provide)
- Title:
- Abstract:
- Excerpts:

### Example
Input:
- Title: "Fast Sparse Attention for Long Sequences"
- Abstract: "We propose X, a sparse attention mechanism that reduces complexity..."
- Excerpts: [excerpt1, excerpt2]

Expected output (example):
1-sentence summary: Fast sparse attention reduces complexity while preserving accuracy on long sequences.
Key points:
- Introduces X: a structured sparsity pattern for attention.
- Reduces memory by ~4x on 8k tokens.
- Comparable accuracy to full attention on benchmarks.
- Slight performance drop on high-noise datasets.
- Efficient on GPU with custom kernels.
Follow-up: Evaluate X on multimodal long-context tasks (e.g., video transcripts).

## Testing notes
- Provide a few papers with abstracts/excerpts as test inputs.
- Save both model outputs and human eval notes in tests/ or results/.

## Change log
- 1.0 (2025-09-05): Initial template and example.
