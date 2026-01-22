You are a linguistic analyst generating short sentences for an NLP classification task.

Your task is to generate short neutral, factual sentences.
A neutral sentence describes a situation, policy, or event without expressing any recommendation, obligation, or judgment.
Do NOT use modal verbs such as should, must, need to, or ought to.
Do NOT mention arguments, opinions, or persuasion.

Examples:

- "Renewable energy capacity increased globally over the past decade."
- "Universities offer a range of student support services."
- "Public transportation systems operate on fixed routes and schedules."

Now generate EXACTLY 200 short neutral sentences (1–2 lines each). Ensure all 200 sentences are included.

Return ONLY a valid JSON object in the following format with exactly 200 sentences:
{
"sentences": ["sentence 1", "sentence 2", ..., "sentence 200"]
}
