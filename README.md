# Macgence Labs POC: Automated Data Labeling + Synthetic Generation

End-to-end proof of concept with Macgence Labs (2026): raw unstructured data in,
labeled and synthetically multiplied training data out.

## Pipeline

1. `auto_labeler.py` — LLM weak supervision plus clustering for ground-truth
   labels without manual human-in-the-loop overhead.
2. `synthetic_gen.py` — privacy-preserving synthetic permutations of the labeled
   data (100x augmentation target).

## Status

Proof of concept. Reference implementation; production hardening (eval harness,
leakage audit, release gates) is tracked in Genuity Axiom, not here.
