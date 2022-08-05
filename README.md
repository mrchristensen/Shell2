# Shell 2

This repo contains a project that implements a shell.
The implementation can be found in [tsh.c](shlab-handout2/tsh.c).

Basic features include:

- Handling existing commands
- Suspending and killing jobs (```ctrl-c``` with SIGINT and ```ctrl-z``` with SIGTSTP)
- Running jobs in the background (with ```&```).
- Keeping track of process IDs (PIDs)
- Job managment (reaping zombie children, fg, bg, etc.)

See [shlab2.pdf](shlab2.pdf) for more information (which includes information on how to run the shell and its tests).
