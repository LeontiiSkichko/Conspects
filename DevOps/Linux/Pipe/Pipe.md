Takes the `stdout` of the left command and passes it as the `stdin` for the right one. This allows building chains.

- _Example:_ `cat logs.txt | grep "Error"` (read the file and immediately filter lines with the word "Error").