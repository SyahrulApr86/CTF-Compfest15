# KatVM [488 pts]

**Category:** Reverse Engineering
**Solves:** 8

## Description
>b"I made my own language! Its very simple, yet effective in comparing things. It has turing machine like properties as well.\r\n\r\nHere are the instructions available, write in just like how you write assembly or script, its top to down:\r\n\r\n- `left <N>`, `right <N>`: Move the tape head to left or right by N\r\n- `store <STRING>`: Store string to from current head, the head will move right after the string\r\n- `print`: Print from head to next empty\r\n- `input`: Input from stdin and store it in current head, the head will move right after the string\r\n- `push`: Push current head to stack\r\n- `popeq <CHAR>`: Pop current stack, and compare the character with given char. If true, it will skip next instruction\r\n- `quit`: Exit\r\n\r\nExample for Hello World:\r\n```\r\nstore Hello World!\r\nleft 12\r\nprint\r\n```\r\n\r\nYou may write it the code in a `.kat` file, and you can compile it with the website. Then execute it\r\nwith `python run_katvm.py output.kb`.\r\n\r\nNOTE: You need to run it on Python 3.10\r\n\r\n**Author: rorre**"

**Hint**
* -

## Solution

### Flag

