# Test acsum1sent-001 — One-sentence summary (self-contained manual test)

- prompt_ref: prompts/acsum1sent-my-first-prompt.md
- id: acsum1sent-001-test-001
- date: 2025-09-05
- model_used: github and chatgpt
- model_settings: <paragraph 1 of thesis results>

## Prompt used for this test
You are an assistant. Given a short abstract or paragraph, write one clear sentence that summarizes the main idea. Keep it under 20 words.

## Input
Paste the exact paragraph you gave the model (including quotes if you used them):

Input: "Genetic and stereotaxic approaches were used to refine cellular and anatomic targeting of DREADDs, restricting expression to orexin cells in the most caudal and lateral portions of the LH (Figure 1;20). Adult male orexin-cre (Cre) or wildtype (Wt) mice (n=3/group) received injections of a DREADD virus (hM3Dq) at one site per hemisphere aimed at caudal lateral LH (Figure 1b). Histological LH tissue analysis confirmed selective expression of hM3Dq-mCherry in orexin neurons (Figures 1c and f). Low magnification images capture nearly the entire orexin neuron field and show clear colocalization between immunoreactive channels labeling orexin (green) and hM3Dq-mCherry (red; Figure 1c). High magnification images show expected cytoplasmic labeling of mCherry and orexin (orange arrowheads, middle row; Figure 1c). mCherry staining was absent in Wt::hM3Dq controls (Figure 1e)."

## Expected output (example)
Targeted DREADD expression selectively labels orexin neurons in caudal lateral LH, confirmed by mCherry colocalization.

## Runs
run_id: 001 date: 2025-09-05 model_used: github model_settings: <paragraph 1 of thesis results> actual_output: "Targeted DREADD expression in caudal lateral LH selectively labeled orexin neurons, confirmed by mCherry colocalization absent in controls." 
notes: "Assistant generated this suggested output for the user to record."

run_id: 002 date: 2025-09-05 model_used: ChatGPT model_settings: <paragraph 1 of thesis results> 
actual_output: "Researchers successfully targeted DREADD expression specifically to orexin neurons in the caudal lateral hypothalamus of mice." 
notes: "Copied Prompt used for this test and Input into ChatGPT web, clicked send"

run_id: 00x date: <fill in date/time you run ChatGPT> 
model_used: ChatGPT model_settings: <e.g., temperature=0.0, system message=none> 
actual_output: "" 
notes: Copied Prompt used for this test and Input into ChatGPT web, clicked send.

Notes
Keep one run entry per test execution. Include date, model name, settings, exact model output, and a short note on how you ran it.
If you re-run with different settings, add a new run block with new run_id and date.
