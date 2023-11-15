Simple Shell
Shell Logo
## Table of Contents- Description- Features- Installation- Usage- Command Examples- Contributors- License## DescriptionSimple Shell is a basic command-line interpreter program developed by Ayoub Draid and Salwa Naciri. It provides a simplified interface for users to interact with the operating system. The shell allows users to execute various commands and provides basic shell functionalities such as executing programs, managing files and directories, and handling input/output redirection.## Features- Command Execution: The shell can execute both built-in commands and external programs.- Input/Output Redirection: Users can redirect the input and output of commands to files.- Piping: Users can pipe the output of one command as the input to another command.- Background Execution: Commands can be executed in the background by appending an ampersand (&) at the end of the command.- Environment Variable Handling: The shell supports environment variables and allows users to set, get, and delete them.- Signal Handling: The shell handles common signals such as SIGINT (Ctrl+C) and SIGTSTP (Ctrl+Z).- Command History: Users can access previous commands using the arrow keys or by typing !! to execute the last command.## Installation1. Clone the repository: shell   $ git clone https://github.com/your-username/simple-shell.git   ```2. Compile the source code:   shell $ gcc -Wall -Werror -Wextra -pedantic *.c -o shell ## Usage1. Run the shell:   ````shell   $ ./shell   2. Use the shell by entering commands. For example: shell   $ ls   $ echo "Hello, World!"   $ cat file.txt   ```## Command Examples- Execute an external program:  shell $ ls - Execute a built-in command:  ````shell  $ cd /path/to/directory  - Redirect output to a file: shell  $ ls > output.txt  ```- Pipe the output of one command to another:  shell $ ls | grep "pattern" - Run a command in the background:  ````shell  $ sleep 10 &  - Set an environment variable: shell  $ export MY_VARIABLE=value  ```- Access previous commands:  shell $ !! ```## Contributors- Ayoub Draid - @ayoub-draid- Salwa Naciri - @salwa-naciri## LicenseThis project is licensed under the MIT License.
