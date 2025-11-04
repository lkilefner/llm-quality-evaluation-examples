# Prompt 04 — Math Word Problem (Edge Case: Misleading Wording)

**User Prompt**
“Sofia has 12 apples. She gives some to her friend. Now she has 7 apples. How many apples did Sofia give away? Explain your thinking in 1–2 short sentences, in kid-friendly language.”

**Ground Truth (Exemplar)**
“Sofia used to have 12 apples and now she has 7. That means she gave away **5 apples**, because 12 - 7 = 5.”

**Why this is an Edge Case**
This is the type of problem where:
- Some models incorrectly answer **“5 apples” but add unnecessary extra steps**, or
- Provide confusing explanations with subtraction phrased backwards, or
- Switch to multi-step reasoning not needed for Grade 2–3.

**Target Score Profile (Ideal)**
- Accuracy: 5 (correct subtraction; no reversals)
- Alignment: 5 (1–2 sentences; kid-friendly language)
- Clarity: 5 (direct and simple)
- Tone: 4–5 (neutral/helpful; no “easy!” framing)

**Common Failure Modes to Catch**
- Writes: “Sofia gave away 12 - 5 = 7,” which reverses logic
- Uses: “minuend/subtrahend” (too advanced vocab)
- Writes paragraphs instead of simple explanation
