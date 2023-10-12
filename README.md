# NLP Projects
- [POS Tagging using HMMs and Viterbi algo from scratch:](https://github.com/BENHIMA-Mohamed-Amine/NLP-Projects/tree/master/POS-Tagging-HMM-Viterbi)

    #### Quick summary:

    - Loaded our vocabulary and created a vocabulary dictionary: vocab[word] = its_index.
    - Extracted words from the test corpus.
    - Processed these words, assigning the appropriate unknown token if not in the vocabulary.
    - Created emission_counts: (tag, word) = number of occurrences, transition_counts: (tag, tag) = number of occurrences, and tag_counts dictionary: (tag) = total number of occurrences all this dict built using the training corpus.
    - Constructed a list of states containing all the tags, sorted.
    - Built a transition matrix of size (num_tags, num_tags).
    - Created an emission matrix of size (num_tags, size_vocab).
    - Applied the Viterbi algorithm to decode predictions:
        - Initialized the best_prob (size: (num_tags, len(sentence)) and best_path matrices (size: (num_tags, len(sentence))).
        - Utilized viterbi_forward to populate best_prob and best_path.
        - Employed viterbi_backward to retrieve the best path and obtain the predictions.
    - Computed the accuracy.

- [Frequency Based Sentiment Analysis in naive bayes from scratch using Numpy for better intuition](https://github.com/BENHIMA-Mohamed-Amine/NLP-Projects/tree/master/Naive-Baye-Sentiment-Analysis)

- [Frequency Based Sentiment Analysis in Logistic Regression from scratch using Numpy for deep understanding](https://github.com/BENHIMA-Mohamed-Amine/NLP-Projects/tree/master/Frequency-Based-Sentiment-Analysis-in-Logistic-Regression)
