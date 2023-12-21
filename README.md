# Shell-scripting

![Shell Scripting](./img/Shell-Scripting.jpg)

Shell script is a text file that contains a list of executable commands. Shell scripting is primarily used to automate repetitive system tasks, such as backing up files, monitoring system resources, and managing user accounts.The shell is a command-line interpreter that provides a command-line user interface to the operating system. Common Unix and Unix-like operating systems include shells such as Bash, sh, and others.

## Shell Scripting Syntax Elements
## 1 Variables
variables are used to store and manipulate data. Variable names are case-sensitive. in writing a variable, note that there must be no spaces around the "=" sign: VAR=value and its wise to avoid using special characters or reserved words when writing variables

### Assigning a value to a variable and retrieving a value from variable
![variable](./img/1%20Variable.png)

## 2 Control flow

Control flow refers to the order in which statements are executed in a program. In shell scripting, control flow is managed through conditional statements and loops
one way to control flow is the use of if-else to execute script.  The if-else statement is used to make decisions based on conditions. Exaple is shown in this script
![control flow](./img/3%20Control%20Script.png)

make the script execuable with chmode +x
The chmod +x command is used in Unix-like operating systems to add execute permission to a file. The chmod command stands for "change mode," and +x is an argument indicating that the execute permission should be added.
![x](./img/4%20make%20text%20file%20executable.png)

Execute the file with ./
The ./ (dot slash) notation is used in Unix-like operating systems to specify the current directory. When you use ./ in conjunction with a command, it tells the system to look for the executable file in the current directory.
![exec](./img/5%20shell%20script%20execution.png)

## 3 Command substitution
Command substitution is a feature in Unix-like operating systems that allows you to use the output of a command as an argument to another command or as part of a larger command. There are two common syntaxes for command substitution:
Backticks:
Enclose the command within backticks (`) to perform command substitution. and 
Dollar Parentheses:
Enclose the command within $() to perform command substitution.

![command subst.](./img/6%20command%20sub.png)

## 4 Input and output
In Bash scripting, input and output are means of interacting with the user, reading data from external sources, and displaying information.

![Accept user input](./img/7%20Input%20output.png)

[ouput text to terminal](./img/8%20input%20output..png)

![Pass the result of a command as input to another command](./img/9%20input%20output.png)

## 5 Functions
Functions are blocks of reusable code that can be defined once and called multiple times within a script. They help in organizing and modularizing code. Functions can be defined using the function keyword or by decalring the function name, followed by parentheses. 


![function](./img/10.%20nice.png)

#!/bin/bash is the shebang line for a Bash script. The shebang line, often seen at the beginning of a script, specifies the interpreter to be used for executing the script. #!/bin/bash indicates that the script should be interpreted and executed using the Bash shell.

![function](./img/11%20hello%20script.png)

execute the fuction
![exec](./img/12%20execute%20hello%20script.png)

Iterating through a list using a for loop

Creat a text file iterate.sh and edit with vim

![iterate.sh](./img/12.1%20iterate.png)

Compose script

![ietrate.sh](./img/12.2%20iterate%20script.png)

![iterate.sh](./img/12.3%20iterate%20executable.png)

Execute script

![iterate.sh](./img/12.4%20iterate%20exec.png)

## First Shell Script

### Steps in writting a shell script
create and open a folder named shell-scripting

creat a text file for the script in shell-scripting

Use a text editor,nano, vim, to write script. 

![Sc](./img/13%20user%20script%20crtion.png)

Start script with a shebang line to specify interpreter

Compose the main body of script. Include commands, logic, and any other functionality needed

Explain complex sections of code with comments, starting with the # sign. the # sign indicates the line is a comment, not a command

![script](./img/14.%20script2.png)

Save script. .sh extention is adviced for easy identification of script

Make the script executable by running the chmod +x script-name command

![Exec-comd](./img/15%20make%20script%202%20executable.png)

Execute script by running ./script-name

[exec.](./img/16%20script2%20exec.png)

In the case of debugging, add debugging statements or use the set -x option to trace script execution.

### Directory manipulation
Bash provides various commands for directory manipulation and navigation as used in navigating-linux-filesystem.sh

creat a text file, navigating-linux-filesystem.sh  

Use a text editor, vim to write script. 

Make the script executable by running the chmod +x script-name command

![navigating-linux-filesystem.sh](./img/17%20script3.png)

Execute script by running  ./navigating-linux-filesystem.sh
![navigating-linux-filesystem.sh](./img/18%20script3%20exec.png)

### File Operation and Sorting
this includes reading from a file, writing to a file, sorting lines in a file, duplicate sorting and removal,reverserse order sorting, numerical sorting, selecting a range of line and more

creat a text file, sorting.sh
edit sorting.sh with vim

![sorting.sh](./img/19%20sorting%20txt%20file.png)

Start script with a shebang line to specify interpreter

Compose the main body of script. Include commands, logic, and any other functionality needed

Explain complex sections of code with comments, starting with the # sign. the # sign indicates the line is a comment, not a command

![sorting.sh](./img/20%20script%204.png)

Make the script executable by running the chmod +x sorting.sh command

![sorting.sh](./img/21%20script4%20executable.png)

Execute script by running  ./sorting.sh

![sorting.sh](./img/22%20script%204%20exec.png)

### Working with numbers and Calculations
there are built-in arithmetic operations that aids working with numbers. In bash scripting, various calculations can be performed

creat a text file, calculation.sh
edit calculation.sh with vim

Start script with a shebang line to specify interpreter

Compose the main body of script. Include commands, logic, and any other functionality needed

Explain complex sections of code with comments, starting with the # sign. the # sign indicates the line is a comment, not a command

![calculation.sh](./img/23%20script5.png)

Make the script executable by running
chmod +xcalculation.sh

![calculation.sh](./img/24%20script%205%20executable.png)

Execute script by running 
./calculation.sh

![calculation.sh](./img/25%20script5%20exec.png)

### File Backup and Timestamping

creat a text file, backup.sh
edit backup.sh with vim
![backup.sh](./img/26%20backup%20script.png)

Start script with a shebang line to specify interpreter

Compose the main body of script. Include commands, logic, and any other functionality needed

Explain complex sections of code with comments, starting with the # sign. the # sign indicates the line is a comment, not a command

[backup.sh](./img/27.1%20script%206.png)

Make the script executable by running
chmod +x backup.sh

![backup.sh](./img/28%20script%206%20executable.png)

Execute script by running ./backup.sh

![backup.sh](./img/29%20script%206%20exec.png)

