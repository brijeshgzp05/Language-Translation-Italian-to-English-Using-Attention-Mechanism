# Language-Translation-Italian-to-English-Using-Attention-Mechanism

Data: 
 The dataset is downloaded from metatext nlp database.

Steps involved:
 1. Preprocess the data.
 2. Tokenizing and padding the sequences to use them easily.
 3. Implementing custom layers, custom models, custom loss function and custom data generator.
 4. First a simple encoder decoder model is built.
 5. Reference is taken from https://arxiv.org/abs/1409.0473 (Neural Machine Translation By Jointly Learning To Align And Translate) and attention mechanism is applied to improve
    the simple encoder decoder model to work properly for longer sentences.
 6. Two types of attention mechanism are applied:
    a) Attention using dot.
    b) Attention using general mechanism.
    
 7. Got a BLEU score of 0.72 on simple model and 0.85 on attention models.
