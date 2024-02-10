# Plagiarism Detector using 3 different algorithms and analysis of them

String Matching is a problem used in many applications such as plagiarism detection. In this project, you
are required to implement a plagiarism detector. Your algorithm will receive a corpus of existing documents and a
potentially plagiarized document as input. The output should be the set of documents from which the document was
plagiarised from. You should implement the KMP, LCSS, and Rabin-Karp fingerprints algorithms.
a) KMP : Treat each sentence in the test file as a potential pattern. Search for the pattern in the existing documents
and find the matches.
b) LCSS : Run the LCSS algorithm for each paragraph from the test file and existing corpora.
c) Rabin-Karp fingerprints: Implement Rabin-Karp algorithm for multipattern matching. You can use the language
libraries for converting string to hash.
