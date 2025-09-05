# Test 002 — One-sentence summary (self-contained manual test)

- prompt_ref: prompts/002-my-first-prompt.md
- id: 002-test-001
- date: 2025-09-05
- model_used: github v4
- model_settings: <paragraph 1 of results>

## Prompt used for this test
You are an assistant. Given a short abstract or paragraph, write one clear sentence that summarizes the main idea. Keep it under 20 words.

(If you used any extra system messages or hidden instructions in the model UI, paste them here too.)

## Input
Paste the exact paragraph you gave the model (including quotes if you used them):

Input:
"Genetic and stereotaxic approaches were used to refine cellular and anatomic targeting of DREADDs, restricting expression to orexin cells in the most caudal and lateral portions of the LH (Figure 1;20). Adult male orexin-cre (Cre) or wildtype (Wt) mice (n=3/group) received injections of a DREADD virus (hM3Dq) at one site per hemisphere aimed at caudal lateral LH (Figure 1b). Histological LH tissue analysis confirmed selective expression of hM3Dq-mCherry in orexin neurons (Figures 1c and f). Low magnification images capture nearly the entire orexin neuron field and show clear colocalization between immunoreactive channels labeling orexin (green) and hM3Dq-mCherry (red; Figure 1c). High magnification images show expected cytoplasmic labeling of mCherry and orexin (orange arrowheads, middle row; Figure 1c). mCherry staining was absent in Wt::hM3Dq controls (Figure 1e)."

## Expected output (example)
Targeted DREADD expression selectively labels orexin neurons in caudal lateral LH, confirmed by mCherry colocalization.

## Actual output (paste the model response here)
Targeted DREADD expression in caudal lateral LH selectively labeled orexin neurons, confirmed by mCherry colocalization absent in controls.

## Notes
- How you ran the prompt: assistant generated this suggested output for you to record.
- Any manual edits to output: none (assistant-crafted).
- Anything unusual observed: github was more technically specific than chatgpt
