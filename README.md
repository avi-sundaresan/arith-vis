# arith-vis
A Python-based graphical visualization tool for DNA sequences.

We propose a novel two-dimensional graphical visualization method to intuitively analyze and compare multiple DNA sequences. To do so, we employ arithmetic coding, a lossless entropy-based compression method, to transform a sequence into a representative series of bits, taking advantage of differing DNA k-mer frequencies to encode DNA sequences more efficiently than standard two-bit encoding methods. To better visualize and compare related sequences, the k-mer frequencies used to generate the encoding can be derived from multiple sequences. The compressed binary sequence is then represented by a series of vectors constituting a two-dimensional graphical visualization that avoids degeneracy and loss of information. This DNA visualization method can be used to explore variation across sequences in an efficient and intuitive manner. 

This research was presented at the ISCB/RECOMB RegSysGen 2020 conference: https://f1000research.com/posters/10-240. 
