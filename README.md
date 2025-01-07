# Get Next Line Project

The **Get Next Line** project is part of the **École 42** curriculum. This project challenges you to write a function that reads a single line from a file descriptor. The function should be able to handle reading lines of any length, and it should properly manage memory.

## Project Description

The objective of this project is to implement the `get_next_line` function, which is responsible for reading one line from a file descriptor. This line should be returned as a string, and the function should be able to handle reading from a file or even from standard input.

The function should read in chunks and append data until a newline character (`\n`) or the end-of-file (EOF) is encountered. The project aims to ensure proper memory management and efficiency when dealing with file descriptors.

### Key Requirements:
- **Memory Management**: The function should allocate and free memory correctly.
- **Buffer Handling**: The function should use a buffer to handle reading in chunks.
- **Edge Cases**: The function should handle cases like EOF, empty lines, and lines that may be split across multiple reads.
- **Multiple File Descriptors**: The implementation should support reading from multiple file descriptors.

## Objectives

- Implement the function `get_next_line` to read a line from a file descriptor.
- Ensure the function works with any file descriptor (stdin, files, etc.).
- Handle memory allocation properly (avoid leaks).
- Support reading from multiple file descriptors without interference.
- Optimize the function for performance (e.g., avoid unnecessary reads).

## Technologies Used

- **C**: The project is implemented in the C programming language.
- **Makefile**: For compiling the project and managing dependencies.
