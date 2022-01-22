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

### `Import(filePath)`
Loads an anko file and executes it. Very basic library "importing".

## Object `file`

### `Read(filePath)`
Reads a file and returns a string. Now allowed to read file outside of current working directory.

### `Write(filePath, content, ?shouldOverWrite)`
Creates file at `filePath` with `content`, if it does not already exist. `shouldOverWrite` used to write even if exists already.

### `SaveGame(filePath, content, password, ?shouldOverWrite)`
Same as `Write`, but encrypts file with aes-128 with an sha256'd `password`.

### `ReadGame`



