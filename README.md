# Huffman Coding: Compression and Decompression
HuffmanCode is a Java program that can be used to compress and decompress files using Huffman coding.

## Requirements
Java 8 or later

## Usage
The program can be run from the command line. 

To compress a file, use the following command:

java HuffmanCode compress [input_file_path] [output_file_path]

To decompress a file, use the following command:

java HuffmanCode decompress [input_file_path] [output_file_path]

## How it works
Huffman coding is a data compression algorithm that assigns variable-length codes to each symbol based on the frequency of occurrence of each symbol. Symbols that occur more frequently are assigned shorter codes, while symbols that occur less frequently are assigned longer codes. This results in a compression of the original data, as fewer bits are needed to represent the most common symbols.

The HuffmanCode program uses the following steps to compress a file:

1- Read the input file and count the frequency of occurrence of each symbol in the file.

2- Construct a binary tree using the frequency counts, where each leaf node represents a symbol and the path from the root to a leaf node represents the code for that symbol.

3- Traverse the binary tree and assign a code to each symbol based on the path from the root to the corresponding leaf node.

4- Write the codes and the binary tree to the output file.

To decompress a file, the program reads the binary tree and codes from the compressed file, and uses them to reconstruct the original data.

## Screenshots
![HuffmanCode Running](https://user-images.githubusercontent.com/88712877/218340850-213748ed-21e6-4370-8d2d-c67626a1790e.png)
![HuffmanCode Result](https://user-images.githubusercontent.com/88712877/218340851-c319c801-0177-40cd-a325-911afab2b347.png)
