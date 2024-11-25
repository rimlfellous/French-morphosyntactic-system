In this project, I developed a morphosyntactic system for the French language to automate part-of-speech (POS) tagging, a foundational task in natural language processing. 

The goal was to assign grammatical tags like nouns, verbs, or adjectives to words in a sentence.

Using labeled datasets in the Universal Dependencies format, I trained a Hidden Markov Model (HMM) to predict tags based on probabilistic relationships between words and their roles.
The model computed transition probabilities (e.g., the likelihood of a noun following a determiner) and emission probabilities (e.g., the likelihood of the word "chat" being a noun).

For unseen sentences, I applied the Viterbi algorithm to determine the most probable sequence of tags. 

The models demonstrated strong performance in tagging common categories like nouns and verbs while identifying areas for improvement, such as handling rare or unseen words.

This approach showcased the interpretability and efficiency of HMMs for sequence labeling tasks, with potential extensions to other languages or benchmarking against modern machine learning models like CRFs or neural networks.
