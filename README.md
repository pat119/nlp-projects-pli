# nlp-projects-pli
This is my personal repository for NLP and LLM projects.

## Code:
- Available upon request (pli373775@gmail.com)

# Context-Free Grammars
## Summary: 
This is my implementation of various weighted context-free grammars (CFG) and a script that generates sentences from an CFG. The CFGs include rules for tenses, singular vs. plural agreement, etc.
The script takes in multiple arguments:
- grammar: The CFG used to generate sentences
- N: the number of sentences to generate
- M: the number of sentences and M is the maximum number of expansions allowed while generating the sentence

## Functions:
- The script randomly generates N sentences from the CFG.
- To prevent an excessively long sentence, the script only allows M expansions, after which further expansions are replaced with (...)
- After generation, the script prints the generated sentence and the derivation tree.

  
# Trigram Language Model
## Team
Patrick Li and Ishmael Lee
## Summary: 
A log-linear model for text classification, implemented in PyTorch. Various smoothing techniques, including add-lambda with backoff, are also implemented. This is a basic model that uses embeddings as features. The model was trained for the task of classifying emails as spam or non-spam, and classifying documents as English or Spanish. It achieved a test accuracy of 90% on the spam task and 87% on the language task. 
Additional features could be added, such as bigram and trigram counts. 

