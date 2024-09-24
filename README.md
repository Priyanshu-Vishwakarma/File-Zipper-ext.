# File-Zipper-ext.
# File Compressor Application

This project is a **File Compressor** built using the **Huffman Algorithm** to efficiently reduce file sizes. The application encodes data with a binary tree, ensuring **lossless compression**, which allows for saving storage and faster data transmission.

## Features

- **Lossless compression** using the Huffman coding algorithm.
- Efficient **file size reduction** by encoding data using a binary tree.
- Decompression to restore the original file without any loss of data.
- Implements **Greedy Algorithm** for optimal encoding.
- Data Structures such as **Binary Tree**, **Min-Heap**, and **Priority Queue** used for efficient processing.
- Handles file encoding and decoding with **hash maps** (Frequency Table) and **recursion**.

## Technologies Used

- **C++**: The primary language used for implementation.
- **Huffman Coding Algorithm**: For encoding and decoding files.
- **Binary Tree** and **Min-Heap**: Used to generate the Huffman Tree.
- **Priority Queue**: For efficient tree construction.
- **Hash Map**: To store frequency of characters.

## Algorithm Details

The Huffman Coding algorithm is a **greedy algorithm** that assigns variable-length codes to input characters, with shorter codes assigned to more frequent characters. This method results in a compressed file that occupies less space without losing any information.

### Steps Involved:
1. **Frequency Table Generation**: Calculate the frequency of each character in the input file.
2. **Building Huffman Tree**: Using a **min-heap**, construct a binary tree based on character frequencies.
3. **Generate Huffman Codes**: Traverse the tree to assign binary codes to characters.
4. **Encoding**: Replace characters in the file with their corresponding Huffman codes.
5. **Decoding**: Reverse the encoding process to retrieve the original data.

## How to Use

### Requirements:
- C++ compiler (e.g., g++ or clang++)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/file-compressor.git

2. Compile the code :
    ```bash
   g++ -o file_compressor file_compressor.cpp

3. Run the Program
   ```bash
   ./file_compressor inputfile.txt
   
