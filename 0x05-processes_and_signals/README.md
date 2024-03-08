This project will focus on PID

Task 0:
Write a Bash script that displays its own PID.

Task 1:
Write a Bash script that displays a list of currently running processes.
Requirements:
Must show all processes, for all users, including those which might not have a TTY
Display in a user-oriented format
Show process hierarchy

Task 2:
Using your previous exercise command, write a Bash script that displays lines 
containing the bash word, thus allowing you to easily get the PID of your Bash process.
Requirements:
You cannot use pgrep
The third line of your script must be # shellcheck disable=SC2009

Task 3:
Write a Bash script that displays the PID, along with the process name, 
of processes whose name contain the word bash.
Requirements:
You cannot use ps

Task 4:
Write a Bash script that displays To infinity and beyond indefinitely.
Requirements:
In between each iteration of the loop, add a sleep 2

Task 5:
We stopped our 4-to infinity and beyond process using ctrl+c in the previous 
task, there is actually another way to do this.
Write a Bash script that stops 4-to infinity and beyond process.
Requirements:
You must use kill
Terminal #0
