# coherence
This repo contains the created instrument for assessing textual coherence.

One issue has been observed: it seems that different sentence tokenizations in nltk and spacy (we use both) lead to an error - trying to access inexistent matrix cell.

Ideas:
- in our program coherence patterns in paragraphs of different sizes are treated uniformly, which may not be corresponding to reality
- to train a NN for coherence estimation an analogue of padding with respect to paragraph lengths could be used
