# Meow Editor
A simple terminal-based text editor written in C.

![Screenshot of editor](https://i.imgur.com/1zvEtO4.jpeg)

Click to watch the video on YouTube:

[![Watch the video](https://img.youtube.com/vi/qPfo2XE8Zwk/0.jpg)](https://youtu.be/qPfo2XE8Zwk)


## Version History
Current version: **3.1416**

## Features (Implemented)

- View files in the terminal
- Navigate using arrow keys
- Insert characters at cursor position
- Delete characters using `Backspace`
- Save a file named as Output.txt(`CTRL + S`)
- Exit the editor (`CTRL + Q`)
- Handles raw terminal input (canonical mode off)
- Scroll through large files (vertical scrolling)

## Planned Features (Coming Soon 🚧)

- File opening via command line argument
- Syntax highlighting
- Search functionality
- Undo/redo operations
- Line numbers
- Status bar
- Multi-file support
- Clipboard operations (cut, copy, paste)

## How to Compile

Use `gcc` to compile the project:

```bash
gcc -o meow meow.c
```
## How to Run
```bash
./meow
```

Key bindings:
- Arrow keys: Navigate
- Backspace: Delete character
- CTRL + S: Save changes
- CTRL + Q: Exit

Build Dependencies:
- Standerd C library
- Works on Linux and macOS
- Uses POSIX APIs for terminal handling

Notes
- This project usas raw terminal mode(Termios) to handle keyboard input
- Inspired by the Kilo editor
- I have gone through this website process to make this project: https://viewsourcecode.org/snaptoken/kilo/index.html
- Bugs are there but I hope to fix them soon