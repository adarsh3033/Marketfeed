# Marketfeed
Assignment  for Devops Intern

1.The script starts with the shebang #!/bin/bash to specify that it should be executed using the Bash shell.

2.The log_file_path and log_file variables store the paths to the log files.

3.The log_format variable defines the format for log messages.

4.The log_file_handler function reads log messages from standard input and appends them to the log file with the specified format.

5.The signal_handler function is called when Ctrl+C is pressed. It prints a message and exits the script.

6.The monitor_log_file function starts monitoring the log file using the tail -F command. It traps the SIGINT signal (Ctrl+C) to call the signal_handler function.

7.If the log file does not exist, an error message is printed, and the script exits with a non-zero status.
