# Processes and Signals
0-what-is-my-pid: displays its own PID
1-list_your_processes: displays list of currently running processes
2-show_your_bash_pid: displays lines containing the bash word
3-show_your_bash_pid_made_easy: displays PID and name of processes containing bash
4-to_infinity_and_beyond: displays To infinity and beyond indefinitely
5-dont_stop_me_now: stops 4-to_infinity_and_beyond process
6-stop_me_if_you_can: stops 4-to_infinity_and_beyond without kill or killall
7-highlander: displays To infinity and beyond and handles SIGTERM
67-stop_me_if_you_can: kills 7-highlander process
8-beheaded_process: kills 7-highlander with SIGKILL
10-process_and_pid_file: creates PID file and handles signals
manage_my_process: writes I am alive to /tmp/my_process every 2 seconds
11-manage_my_process: manages manage_my_process with start stop restart
