# Huffman encoding and LBC decoding
 
 This a programme to compress a text file using Huffman encoding.
 After the encoding is done a file is usually passed on a channel and at the recieving end it is supposed to be decoded.
 This programme uses LBC(Linear Block code) to decode the encoded text.
 
 Important points:
* The code length in huffman coding depends upon the frequency of the character most frequent characters have the smallest code.
* Time complexity for assigning code to character is O(n log n)
* Lbc is a channel coding used so that signal to noise ratio does not increase
* Parity bits are added in the lbc coding so that error correction is easier>
* For applying (6,3) LBC we,ve grouped the encoded message into packets of three.
* We multiply the encoded code words with the generator matrix to get codewords with parity bits. 
 
