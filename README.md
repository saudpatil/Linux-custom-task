# Linux-custom-task


 This command is designed for various operations related to CPU, memory, users, and files. Here's a breakdown of the script:

Manual Page Function (show_manual): Displays the manual page containing information about the command, its version, description, usage, available commands, options, and examples.

Help Function (show_help): Displays a concise help message showing the usage and available commands. It advises users to run 'internsctl COMMAND --help' for more detailed information on a specific command.

Version Function (show_version): Displays the version of the internsctl command.

Command-specific Functions:

get_cpu_info: Placeholder function to get CPU information.
get_memory_info: Placeholder function to get memory information.
create_user: Placeholder function to create a new user.
list_users: Placeholder function to list all regular users.
list_sudo_users: Placeholder function to list users with sudo permissions.
get_file_info: Placeholder function to get file information based on options.
Main Script Logic (case statement):

Processes the main command and directs it to the appropriate function based on the provided arguments.
Commands include "cpu," "memory," "user," "file," "--help," and "version."
Command Execution:

