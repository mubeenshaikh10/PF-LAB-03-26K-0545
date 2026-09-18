# C Programming Fundamentals Documentation

## 1. Data Types

| Data Type | Description |
| :--- | :--- |
| `int` | Stores whole numbers (integers) without decimals. |
| `float` | Stores single-precision floating-point numbers (decimals). |
| `double` | Stores double-precision floating-point numbers (higher accuracy). |
| `char` | Stores a single character/letter. |
| `bool` | Stores boolean values (`true` or `false`). Requires `<stdbool.h>`. |
| `void` | Represents the absence of type or no value. |

## 2. Format Specifiers

| Specifier | Description |
| :--- | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Octal integer |
| `%x` | Unsigned hexadecimal integer (lowercase) |
| `%X` | Unsigned hexadecimal integer (uppercase) |
| `%f` | Floating-point number |
| `%e` | Exponential/Scientific notation |
| `%c` | Single character |
| `%s` | String of characters |
| `%lf` | Double precision floating-point number |

## 3. Input/Output Functions

- **`scanf()`**: Reads formatted input from standard input (keyboard).
- **`printf()`**: Displays formatted output to standard output (screen).
- **`getchar()`**: Reads a single character from the input stream.
- **`putchar()`**: Writes a single character to the output screen.
- **`fgets()`**: Reads a line/string safely from standard input, including spaces[cite: 1].
- **`puts()`**: Writes a string to the output screen followed by a newline.

## 4. Escape Sequences

- `\n`: Moves cursor to a new line.
- `\t`: Inserts a horizontal tab space.
- `\\`: Displays a backslash character.
- `\"`: Displays a double quote character.
- `\r`: Carriage return (moves cursor to start of current line).

## 5. Precision Handling in Floating-Point Output

Precision in floating-point output is controlled using the `%.nf` specifier in `printf()`, where `n` represents the number of decimal places to display.

**Example:**
```c
float pi = 3.14159;
printf("%.2f\n", pi); // Outputs: 3.14
printf("%.4f\n", pi); // Outputs: 3.1416
