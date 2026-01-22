# Persuasion Classification with Linguistics Cues

This project investigates whether a simple linear model can distinguish persuasive from neutral sentences based on lexical features.

A TF-IDF + logistic regression baseline is evaluated on a prompt-generated dataset. A sentence-length confound is identified, verified through ablation, and mitigated via controlled regeneration.

The final model achieves 87.5% accuracy after controlling for length, indicating that lexical cues alone provide substantial signal for persuasion detection.
