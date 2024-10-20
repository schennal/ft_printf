Ft_printf

Ft_printf is a custom implementation of the printf function, developed as part of the 42Cursus curriculum. This project focuses on understanding variadic functions and formatting output in C.

Features

- Custom Format Specifiers: Supports various format specifiers, including integers, strings, characters, and pointers.
- Variadic Functions: Utilizes variadic arguments to handle a variable number of inputs.
- Error Handling: Implements robust error checking for invalid format specifiers.

Installation

Clone the repository and compile the library:

```bash
git clone https://github.com/schennal/ft_printf.git
cd ft_printf
make
```

Usage

Include the library in your projects and use the `ft_printf` function in place of the standard `printf`:

```c
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s!\n", "world");
    return 0;
}
```
