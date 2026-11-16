# C Programming Labwork

Laboratory exercises and larger programs written for the C Programming course at İzmir Institute of Technology (Electrical and Electronics Engineering). The repository will keep growing with more C projects and practice code.

## Contents

| Folder | What is inside |
|---|---|
| [`Labs-Iztech-EEE/`](Labs-Iztech-EEE/README.md) | Weekly lab programs (Labs 2 to 9) and two larger programs: a number guessing game and a Sudoku game |

## Topics covered

Input and output, conditionals and loops, math functions, arrays, sorting, strings, 2D arrays, random numbers and file handling.

## Build and run

Every program is a single `.c` file, so any C compiler works:

```bash
cd Labs-Iztech-EEE
gcc clab2.c -o clab2 -lm
./clab2
```

Use `-lm` for programs that include `math.h`. File names with spaces need quotes, for example `gcc "halil_yilmaz 1.c" -o sudoku`.
