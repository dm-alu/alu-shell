# 0x05. Processes and signals

Description of each script in this directory:

- `0-what-is-my-pid`: displays its own PID.
- `1-list_your_processes`: displays a list of currently running processes, all users, with hierarchy.
- `2-show_your_bash_pid`: displays lines containing "bash" from the process list.
- `3-show_your_bash_pid_made_easy`: displays the PID and name of processes whose name contains "bash".
- `4-to_infinity_and_beyond`: displays "To infinity and beyond" indefinitely, sleeping 2s between iterations.
- `5-dont_stop_me_now`: stops the `4-to_infinity_and_beyond` process using `kill`.
- `6-stop_me_if_you_can`: stops the `4-to_infinity_and_beyond` process without using `kill` or `killall`.
- `7-highlander`: displays "To infinity and beyond" indefinitely, printing "I am invincible!!!" on SIGTERM instead of dying.
- `67-stop_me_if_you_can`: stops the `7-highlander` process without using `kill` or `killall`.
- `8-beheaded_process`: kills the `7-highlander` process.
- `10-process_and_pid_file`: creates a PID file, loops indefinitely, and handles SIGINT/SIGTERM/SIGQUIT.
- `11-manage_my_process`: init-style script to start/stop/restart the `manage_my_process` daemon.
- `manage_my_process`: daemon that writes "I am alive!" to `/tmp/my_process` every 2 seconds, indefinitely.
