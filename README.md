# POSIX-Shell-Implementation
The shell supports commands like cd, echo, pwd, pinfo, history, search, ls, and exit. It also features command history management and displays process information.

### Features:
  * Command Handling: Supports basic shell commands such as cd, echo, pwd, pinfo, history, search, ls, and exit.
  * Command History: Maintains a history of the last 20 commands executed.
  * Process Information: Retrieves and displays information about running processes.
  * File System Operations: Lists directory contents with options for showing hidden files and long format listing.
  * File Search: Searches for files in the current directory.
  * Prompt Customization: Displays a custom prompt with the username, hostname, and current working directory.

### Instructions:
  * The shell itself on execution requires .history.txt file to be created (or accessed if one already exists) from the directory it is executed to allow for persistent history across shell instances.
  * The shell is tested on g++ (Ubuntu 13.2.0-23ubuntu4) 13.2.0
  * To Run the Shell :
       * on command line type: g++ main.cpp
       * next type:            ./a.out

### Files:
  * Contains only 1 file in the source code and a README.md file
  * On running history command a file is created to store the commands

### Assumptions
  * echo command format : echo "text"
      - In this the text should not contain space

        
