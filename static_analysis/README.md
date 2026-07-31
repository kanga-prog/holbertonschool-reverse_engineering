# Static Analysis

This project introduces static analysis techniques used in reverse engineering to inspect a binary without executing it.

## Task 0: Extracting and Analyzing Strings

The objective was to analyze `target-binary` and recover a hidden flag.

### Tools Used

- `strings`
- `grep`
- `nm`
- `objdump`
- Radare2

### Method

The binary strings were extracted and searched for useful information. The `check_flag` function was then identified and disassembled. The flag was reconstructed from the hexadecimal values loaded character by character into memory.

### Result

The recovered flag is stored in:

```text
0-flag.txt
