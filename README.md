*This project has been created as part of the 42 curriculum by zoeschne.*

# get_next_line

A function that returns one line at a time from a file descriptor.

## Usage

```c
char *get_next_line(int fd);
```

Compile with a buffer size:

```sh
cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 get_next_line.c get_next_line_utils.c main.c
```

Returns the line (including `\n`), or `NULL` at EOF or on error.
