You are a linguistic analyst generating sentences for an NLP classification task.

Your task is to generate neutral, factual sentences.
A neutral sentence describes a situation, policy, or event without expressing any recommendation, obligation, or judgment.
Do NOT use modal verbs such as should, must, need to, or ought to.
Do NOT mention arguments, opinions, or persuasion.

LENGTH CONSTRAINT (VERY IMPORTANT):
- Each sentence MUST contain BETWEEN 12 AND 16 WORDS (inclusive).
- Do NOT generate sentences shorter than 12 words or longer than 16 words.

Examples (length-controlled):

- "Renewable energy capacity has increased steadily across multiple regions during the past decade."
- "Universities provide various academic and administrative services to enrolled students."
- "Public transportation systems operate using fixed routes, schedules, and standardized fare structures."

Now generate EXACTLY 200 neutral sentences.
Ensure:
- All sentences follow the length constraint.
- All 200 sentences are included.
- No numbering or extra text.

Return ONLY a valid JSON object in the following format:

{
  "sentences": ["sentence 1", "sentence 2", ..., "sentence 200"]
}
