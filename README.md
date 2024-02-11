![Banner](https://raw.githubusercontent.com/francfer-art/Badges/main/covers/cover-get_next_line-bonus.png?token=GHSAT0AAAAAACI7BVOKJHW2QQMWXXXPROHMZOI2OMQ)

<p align="center">
  <img src="https://raw.githubusercontent.com/francfer-art/Badges/main/badges/get_next_linem.png?token=GHSAT0AAAAAACI7BVOLMUWFY2HARN6ZY456ZOI2PHQ" alt="GNL Logo">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Score-125%2F100-brightgreen" alt="GNL Score">
</p>

## Table of Contents

- [Introduction](#introduction)
- [Features](#overview)
- [Requirements](#requirements)
- [Additional Instructions](#additional-instructions)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to get_next_line! This project aims to provide a function that reads a line from a file descriptor, one line at a time, handling various scenarios and edge cases.

## Overview

The get_next_line function allows you to read text files or input from the standard input (stdin) and returns the line that was read. It handles repeated calls (e.g., using a loop) to read the text file, ensuring that each call retrieves the next line.

## Requirements

Here are the key requirements for the get_next_line function:

```
Repeated calls to get_next_line() should let you read the text file pointed to by the file descriptor, one line at a time.
The function should return the line that was read. If there is nothing else to read or if an error occurred, it should return NULL.
Ensure that the function works as expected both when reading a file and when reading from the standard input (stdin).
The returned line should include the terminating \n character, except if the end of the file was reached and does not end with a \n character.
Your header file get_next_line.h must contain at least the prototype of the get_next_line() function.
Add all the necessary helper functions in the get_next_line_utils.c file.
```
## Additional Instructions

Here are some additional instructions for compiling and handling the project:

```
To define the buffer size for read(), add the option -D BUFFER_SIZE=n to your compiler call, where n is the buffer size value.
The buffer size value will be modified by your peer-evaluators and the Moulinette for testing purposes.
You must be able to compile this project with and without the -D BUFFER_SIZE flag in addition to the usual flags.
The function has undefined behavior if the file pointed to by the file descriptor changed since the last call, whereas read() didn’t reach the end of the file.
The function also has undefined behavior when reading a binary file. However, you can implement a logical way to handle this behavior if you want to.
```

## Getting Started

To use Libft in your project, follow these steps:

1. Clone the repository:

```bash
https://github.com/francfer-art/42Printf.git
```

3. Include the library in your project:

```c
    #include "ft_printf.h"
```

4. Compile the library:

```bash
    make
```

5. Link the library during compilation of your project:

```bash
    gcc main.c -L. -lftprintf -o my_program
```

## Usage

Once the library is successfully integrated into your project, you can start using the functions in your code. Refer to the Libft Wiki for detailed documentation on each function.

```c
#include "ft_printf.h"

int main()
{
    int num;
    num = 7;

    ft_printf("Hello, %s\n", "world!");
    ft_printf("The value of the number is: %d\n", num);
    return 0;
}

```

## Contributing

Contributions are welcome! If you have improvements or additional features to suggest, please open an issue or submit a pull request. Follow the Contribution Guidelines for more details.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

