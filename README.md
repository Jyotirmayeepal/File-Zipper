# File-Zipper
This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. It can compress and decompress any text files. 
This project supports two functions: 
1) Encode: Compresses input file passed. 
2) Decode: Decompresses Huffman coded file passed back to its original file.

Command Line arguments to run encode:

g++ encode.cpp huffman.cpp -o main

main inputFile.txt compressedFile.huf

Command Line arguments to run decode:

g++ decode.cpp huffman.cpp -o main

main compressedFile.huf outputFile.txt

