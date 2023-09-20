# Huffman-Encoding-Algorithm
This project consists in using the Huffman Encoding Algorithm in order to try and compress data. The algorithm basically assigns the shortest binary code to the character that is mostly repeated, this is accomplished by using a tree sctucture that defines the binary code. The theoretical aspect can be found in the research paper attached.
In the research paper a thorough description is provided for foundations of information theory and how it initially started, and then proceeding to a more in-depth analysis of the Huffman Algorithm with two implementations,
one with C++ and one with Python. 


Compressing methods are discussed for audio, image, and videos, with the explenation of how it can be represented with only binary code, and then the binary code undergoes Huffman Encoding for compression. Efficient compression is not always guaranteed because it depends on the entire data that is to be compressed. The worst case scenario would be when each piece of data is repeated with the same frequency. The idea is to use the shortest binary representation for the characters that are most frequently used. 

The performance of this algorithm is shown in another repository, with its implementation being in Python. The final proposal of the research was to use Huffman Encoding-Decoding Algorithm in special networks, depicting the advantages and the disadvantages of doing so.
