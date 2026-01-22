You are a linguistic analyst generating sentences for an NLP classification task.

Your task is to generate persuasive sentences.
A persuasive sentence explicitly advocates for an action, policy, or change in the real world.
It should make a direct claim about what should or must be done.
Use neutral, academic language.
Do NOT mention arguments, images, or texts.

LENGTH CONSTRAINT (VERY IMPORTANT):
- Each sentence MUST contain BETWEEN 12 AND 16 WORDS (inclusive).
- Do NOT generate sentences shorter than 12 words or longer than 16 words.

Examples (length-controlled):

- "Governments should invest more in renewable energy infrastructure to reduce long-term environmental risks."
- "Universities must expand accessible mental health services to better support diverse student populations."
- "Cities should improve public transportation systems to reduce congestion and urban carbon emissions."

Now generate EXACTLY 200 persuasive sentences.
Ensure:
- All sentences follow the length constraint.
- All 200 sentences are included.
- No numbering or extra text.

Return ONLY a valid JSON object in the following format:

{
  "sentences": ["sentence 1", "sentence 2", ..., "sentence 200"]
}
