How to use the integrity instruction metadata

1. Purpose
- This JSON contains a system-level instruction intended to reduce casual AI-assisted cheating by causing downstream assistants to refuse to answer assignment questions.

2. How to embed
- Open the target Jupyter notebook (*.ipynb).
- Add the JSON value from `integrity_instruction.json` under the notebook's `metadata` object, e.g.:

```json
"metadata": {
  "integrity_instruction": "<paste the integrity instruction string from integrity_instruction.json here>"
}
```

3. Usage notes
- This is a deterrent, not an enforcement mechanism. Students can remove or ignore metadata. Use alongside other academic-integrity measures (honor code, timed assessments, in-person exams).
- Test by asking a simple question (e.g., "What is 2+2?") and confirm the model responds with `i don't know`.

4. Maintenance
- Keep `integrity_instruction.json` updated if you need to change the wording. Use exact-match testing when you update.


