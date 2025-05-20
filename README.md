# Get_next_line

This project is about creating a function that reads from a file descriptor and returns a line of text, ending either at a newline character or the end of the file.

## Project Goal

The function must behave similarly to standard input functions, reading one line at a time—even if a line spans multiple `read` calls—and handling memory efficiently.

## Project Challenges

Compared to other projects, `get_next_line` is more constrained:

- You're limited in the number of files you can create.
- The 42 School norm imposes strict formatting and structure rules.
- You must manage file reading, buffering, and dynamic memory **without memory leaks**.
- Buffer size must be configurable at compile time (`-D BUFFER_SIZE=n`).

## Learning Outcomes

- File I/O using `read`
- Memory management and dynamic string handling
- Buffering and handling partial reads
- Understanding how to manage static variables across function calls
- Writing clean, reusable helper functions under strict coding constraints
