# About
SUTD 50.040 Natural Language Processing Course Homework and Projects taught by Professor Lu Wei.
For more information, refer to https://istd.sutd.edu.sg/undergraduate/courses/50040-natural-language-processing.

## Material
### Homework
#### 1. HW1 [Code] - Word Embeddings (Co-occurence matrices/Word2Vec)
Word embeddings are dense vectors that represent words, and capable of capturing semantic and syntactic similarity, relations with other words, etc.
This homework uses two methods to learn word embeddings: Count-based (Co-occurrence matrices) and Prediction-based (Word2Vec - CBOW and Skip-gram model).
The dataset used is "text8" that consists of one single line of text.

#### 2. HW2 [Code] - CKY parsing algorithm for probabilistic context-free grammars (PCFG)
Constituency parsing aims to extract a constituency-based parse tree from a sentence that represents its syntactic structure according to a phrase structure grammar.
This homework implements a constituency parser based on probabilistic context-free grammars (PCFGs) and evaluate its performance.
The dataset used is a version of the “Penn Treebank” released in the NLTK corpora.

#### 3. HW3 [Written] - Language Model, Dependency Parsing, Context Free Grammar, Transition-based Parsing
Language Model - Calculate bigram language model probability, dealing with out-of-vocab bigram/unigram using interpolated model and "add-one" smoothing.
Dependency Parsing - Draw projective and non-projective dependency trees.
Context Free Grammar - Calculate the probability of a parse tree, use CKY algorithm to find the most probable parse tree.
Transition-based Prasing - "arc-standard" and "arc-eager" transition systems.

### Recommended Textbooks
1. Chris Manning and Hinrich Schütze, Foundations of Statistical Natural Language Processing, MIT Press. Cambridge, MA: May 1999
2. Dan Jurafsky and James H. Martin, Speech and Language Processing (3rd ed. draft), 2018
3. Yoav Goldberg, Neural Network Methods for Natural Language Processing, 2017

### Supplementary Textbooks for Linear Algebra, Probability
1. D. Poole, Linear Algebra: A Modern Introduction. 3rd edition, 2010.
2. J. L. Devore, Probability and Statistics for Engineering and the Science. 8th edition, 2011
