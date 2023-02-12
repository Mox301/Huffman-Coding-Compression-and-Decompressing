# Huffman Coding: Compression and Decompression
HuffmanCode is a Java program that can be used to compress and decompress files using Huffman coding.

## Requirements
Java Development Kit (JDK) version 8 or higher and basic knowledge of Java programming.

## Usage
The program can be executed from the command line or an integrated development environment (IDE) such as IntelliJ, Eclipse, or NetBeans. Follow these steps to run the program:

1- Open the command prompt or terminal.  
2- Navigate to the directory where the program files are stored.  
3- Compile the program by entering "javac HuffmanCode.java" in the command prompt or terminal.  
4- Run the program by entering "java HuffmanCode" in the command prompt or terminal.  

The program will display a menu with the following options:  
1- Compress File: Allows the user to select a file to compress and specify the location of the compressed file.  
2- Decompress File: Allows the user to select a file to decompress and specify the location of the decompressed file.  
3- Exit: Exits the program.  

To compress a file, select option 1 from the menu and follow the prompts to select the file to compress and the location of the compressed file.

To decompress a file, select option 2 from the menu and follow the prompts to select the file to decompress and the location of the decompressed file.

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
HuffmanCode Running

![HuffmanCode Result](https://user-images.githubusercontent.com/88712877/218340851-c319c801-0177-40cd-a325-911afab2b347.png)
HuffmanCode Result

## Contributing
If you find a bug or have a suggestion for a new feature, please open an issue on the project's GitHub page. Pull requests are also welcome.

## License
This project is licensed under the MIT License.
