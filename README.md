# simple-shell---myshell--
Your first project is to write a simple shell - myshell - that has the following properties: 1. The shell must support the following internal commands: i. cd &lt;directory> - change the current default directory to &lt;directory>. If the &lt;directory> argument is not present, report the current directory. If the directory does not exist an appropriate error should be reported. This command should also change the PWD environment variable. ii. clr - clear the screen. iii. dir &lt;directory> - list the contents of directory &lt;directory> iv. environ - list all the environment strings v. echo &lt;comment> - display &lt;comment> on the display followed by a new line (multiple spaces/tabs may be reduced to a single space) vi. help - display the user manual using the more filter vii. pause - pause operation of the shell until 'Enter' is pressed viii. quit - quit the shell ix. The shell environment should contain shell=&lt;pathname>/myshell where &lt;pathname>/myshell is the full path for the shell executable (not a hardwired path back to your directory, but the one from which it was executed)