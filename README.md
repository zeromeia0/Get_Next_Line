# get_next_line

## How to use

1. Clone the repository

   git clone <repository_url>
   cd get_next_line

2. Compile the code

   gcc -Wall -Wextra -Werror get_next_line.c get_next_line_utils.c main.c -o gnl

3. Run the executable

   - To read lines from a file:

     ./gnl

   Make sure to update main.c to open your desired file or use the terminal input version.

4. Using the function in your own project

   - Include get_next_line.h in your source files.
   - Call get_next_line(int fd) passing a valid file descriptor.
   - Remember to free the returned string after use.
