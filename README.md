![image](https://github.com/user-attachments/assets/33bf9879-926e-4962-bb15-225aa537c37e)

## Description

minishell is a project from the 42 school curriculum that involves creating a basic shell program in C. The goal is to understand how shells work, including parsing commands, executing programs, and handling input/output redirection.

## Features

- Prompt: Minishell displays a prompt to indicate it is ready to accept commands.
- History: The shell maintains a history of previously executed commands.
- Command Execution: Minishell searches for and launches the appropriate executable based on the PATH variable or using a relative/absolute path.
- Quoting: Minishell handles single quotes (') and double quotes (") to prevent interpretation of metacharacters within the quoted sequence.
- Redirection: The shell supports input (<) and output (>) redirection, as well as appending output (>>) to a file. It also supports here documents (<<) with a delimiter.
- Pipes: Minishell implements pipes (|) for connecting the output of one command to the input of another.
- Environment Variables: The shell expands environment variables (e.g., $VAR) to their corresponding values.
- Special Variables: Minishell expands $? to the exit status of the most recently executed foreground pipeline.
- Signal Handling: The shell handles signals such as ctrl-C, ctrl-D, and ctrl-\ as expected.
- Built-in Commands: Minishell provides several built-in commands:
    - echo -n: Prints arguments to the standard output without a trailing newline.
    - cd: Changes the current working directory to the specified path.
    - pwd: Prints the current working directory.
    - export: Sets or exports environment variables.
    - unset: Unsets environment variables.
    - env: Prints the environment variables.
    - exit: Exits the shell.
 
## Usage

Clone the repository:
```bash
git clone https://github.com/yourusername/minishell.git
cd minishell
```
Compile the program:
```bash
make
```
To run the shell, simply execute:
```bash
./minishell
```
Once the shell is running, you can enter commands and utilize the supported features.

