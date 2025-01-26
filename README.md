# Hello World in BASIC

A simple Hello World implementation in BASIC.

## Installation

### macOS
```bash
brew install brandonp/homebrew-qbasic/qbasic
```

### Linux
For Debian/Ubuntu:
```bash
sudo apt-get update
sudo apt-get install freebasic
```

### Windows
Download QB64 from http://www.qb64.org/ or use DOSBox with QBasic.

## Running

With QB64:
```bash
qb64 main.bas -o hello
./hello
```

With FreeBASIC:
```bash
fbc main.bas
./main
```

## Code Explanation

The program uses numbered lines, a hallmark of BASIC programming. Line 10 prints the message and line 20 ends the program. The implementation follows classic BASIC conventions with line numbers and simple commands.
