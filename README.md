# Fuzzy-String-Matching

It is a simple algorithm which splits text into ‘chunks’ (or ngrams), counts the occurrence of each chunk for a given sample and then applies a weighting to this based on how rare the chunk is across all the samples of a data set. This means that useful words are filtered from the ‘noise’ of more common words which occur within text.

We can then compare these chunks across a matrix of items which represents our data set to look for close matches. This method of finding close matches should be both very efficient and also produce good quality matches through its ability to place greater importance on groups of characters which are less common across the data.
