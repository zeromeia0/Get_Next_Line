# get_next_line

## How to use

1. Clone the repository

   ```git clone git@github.com:zeromeia0/Get_Next_Line.git && cd get_next_line```

2. Compile the code

     ``` gcc -Wall -Wextra -Werror get_next_line.c get_next_line_utils.c main.c -o gnl```

3. Run the executable

   - To read lines from a file (by dafult you have teste.txt):

     ```./gnl <your file>```
     
   - To read lines from terminal, change the main in main.c and run
     ```./gnl```

   Make sure to update main.c to open your desired file or use the terminal input version.
