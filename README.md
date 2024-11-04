# Negative-Sampling-Sentence-Transformers
When fine-tuning an embedding model, we faced a challenge: we needed to sample a random positive and a subset of negatives at each step due to our unbalanced dataset of triplets. This process was complicated when using sentence-transformers's Trainer method .
