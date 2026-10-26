# C Steganography

## About the Project

C Steganography is a project developed using the C programming language to hide secret messages inside BMP images and retrieve them through decoding.

The project demonstrates file handling, bitwise operations, pointers, structures, and modular programming in C.

## Features

- Encode secret messages into BMP images.
- Decode and retrieve hidden messages from stego images.
- Use Least Significant Bit (LSB) manipulation.
- Work with binary image files.
- Organize code into multiple C source and header files.

## Technologies Used

- **Language:** C
- **Operating System:** Linux / Ubuntu
- **Compiler:** GCC
- **Version Control:** Git and GitHub
- **Image Format:** BMP

## Concepts Used

- File handling: `fopen()`, `fread()`, `fwrite()`, `fseek()`
- Bitwise operators
- Pointers and structures
- Command-line arguments
- Modular programming
- Header files and function declarations

## Project Structure

- `main.c` — Main program and operation selection
- `encode.c` — Encoding implementation
- `encode.h` — Encoding declarations and structures
- `decode.c` — Decoding implementation
- `decode.h` — Decoding declarations and structures
- `common.h` — Common definitions
- `types.h` — Type definitions
- `README.md` — Project documentation

## Compilation

Compile the source files using GCC:

```bash
gcc -Wall -Wextra -std=c11 main.c encode.c decode.c -o stego
```

## How to Run

The program supports encoding and decoding through command-line arguments.

### Encoding

Provide a BMP cover image, a text file containing the secret message, and an output image filename according to the argument format implemented in the program.

### Decoding

Provide the generated stego image and the required output filename according to the argument format implemented in the program.

## Learning Outcomes

- Practiced C programming and modular code organization.
- Applied bitwise operations to hide and retrieve message data.
- Learned binary file handling and command-line argument processing.
- Developed and tested a multi-file C project on Linux.

## Author

Electronics and Communication Engineering Graduate
