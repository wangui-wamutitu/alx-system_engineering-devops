# 0x03. Shell, init files, variables and expansions

This project focuses on basic **Bash scripting** concepts including:

- Shell initialization files (`.bashrc`, `.profile`)
- Local and environment variables
- Shell arithmetic and expansions
- Aliasing and path manipulation

---

## Files and Descriptions

| Script | Description |
|--------|-------------|
| `0-alias` | Creates an alias `ls` that deletes all files in the current directory. |
| `1-hello_you` | Prints `hello` followed by the current Linux username. |
| `2-path` | Adds `/action` to the `PATH` environment variable. |
| `3-paths` | Counts the number of directories listed in the current `PATH`. |
| `4-global_variables` | Prints all global (environment) variables. |
| `5-local_variables` | Prints all local and global variables, including shell functions. |
| `6-create_local_variable` | Creates a local variable `BEST` with the value `School`. |
| `7-create_global_variable` | Creates a global variable `BEST` with the value `School`. |
| `8-true_knowledge` | Prints the result of `128 + $TRUEKNOWLEDGE`. |
| `9-divide_and_rule` | Prints the result of `POWER / DIVIDE` using environment variables. |
| `10-love_exponent_breath` | Prints the result of `BREATH` raised to the power of `LOVE`. |
| `11-binary_to_decimal` | Converts a binary number (`$BINARY`) to a decimal number. |
| `12-combinations` | Prints all two-letter lowercase combinations except `oo`. |
| `13-print_float` | Prints the `NUM` variable rounded to two decimal places. |

---

## Usage

To run a script:

```bash
source ./<script_name>

---

## Advanced Tasks

| Script | Description |
|--------|-------------|
| `100-decimal_to_hexadecimal` | Converts a base-10 number stored in the environment variable `DECIMAL` to its hexadecimal representation and prints the result. |
| `101-rot13` | Encodes and decodes input using the ROT13 cipher (assumes ASCII input). Useful for simple text obfuscation. |
| `102-odd` | Prints every other line of input, starting with the first line (i.e., lines 1, 3, 5, ...). |
| `103-water_and_stir` | Interprets two environment variables, `WATER` and `STIR`, as numbers in custom bases and adds them together. Then it prints the result in a custom base named `bestchol`. |
