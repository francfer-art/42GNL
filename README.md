![Banner](https://raw.githubusercontent.com/francfer-art/Badges/main/covers/cover-ft_printf.png?token=GHSAT0AAAAAACI7BVOLIZV6FD4DJI326UIGZOIZYIQ)

<p align="center">
  <img src="https://raw.githubusercontent.com/francfer-art/Badges/main/badges/ft_printfe.png?token=GHSAT0AAAAAACI7BVOK54CECJBVIAYQRFY4ZOIZWGQ" alt="Libft Logo">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Score-100%2F100-brightgreen" alt="Libft Score">
</p>

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to ft_printf! This project aims to provide a custom implementation of the printf function in C. The purpose of ft_printf is to handle various conversion specifiers and format options just like the original printf function, but with some limitations and requirements.

## Features
ft_printf is designed to handle the following conversion specifiers:

```
%c: Prints a single character.
%s: Prints a string (as defined by the common C convention).
%p: Prints a pointer address in hexadecimal format.
%d: Prints a decimal (base 10) number.
%i: Prints an integer in base 10.
%u: Prints an unsigned decimal (base 10) number.
%x: Prints a number in hexadecimal (base 16) lowercase format.
%X: Prints a number in hexadecimal (base 16) uppercase format.
%%: Prints a percent sign.
```

## Requirements
Here are some key requirements for ft_printf:

The buffer management of the original printf() is not implemented.
The function will be compared against the original printf().
The command ar must be used to create the library (libftprintf.a), and the library must be created at the root of the repository.
The use of the libtool command is forbidden.

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

