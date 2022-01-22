# Functions documentation


## Object `os`

### `Print("Hi")`
same as go's `fmt.Println`

### `Input(?"question")`
Functions as a prompt to get user input from stdin.
Optional parameter `string` used as a 'question', otherwise the prompt looks like `<Input>`

### `Sleep(x)`
Pauses the program for x seconds 

### `Quit()`
Closes the program with exit code 0

### `Error(?Message)`
Prints out this error message:
```
┌┤ERROR├───┐
│ ?Message │
└──────────┘
```
