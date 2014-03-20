Basic shell program with the following internal commands:

show W -- displays the word followed by newline
set W1 W2 -- set the value of the local variable to the value W2
unset W1 -- unset a previously set local variable W1
export W1 W2 -- export the global variable W1 with the value W2 to the environment
unexport W: unexport the global variable W from the environment
chdir W: change directory
exit i: exit with status i
wait i: the shell waits for process i to complete. 

The shell also supports local variable substituion, background commands (e.g sleep 5 &), stdin/stdout redirection etc.
