--I/O Redirection--
=====================
Standard Output
^^^^^^^^^^^^^^^^
Most command line programs that relay information back to the display(?) do so by something called standard output. The standard output of a program can be redirected to something else like a file, using the '>' symbol. Ex. ls > file_list.txt - This directs the output of the ls command into a file called 'file_list.txt'

The '>' symbol will overwrite the contents of a file if used on the same file. However, using the '>>' symbol will add on to the information already present. Ex. ls >> file_list.txt
Note: If the file does not exist when attempting to use standard output redirection, the file will be created. 

Standard Input
^^^^^^^^^^^^^^^
Many programs also have the capability to accept input, this is known as standard input. This is done by using the '<' symbol. Ex. sort < file_list.txt - In this example, 'file_list.txt' is being sent to the sort program. 
The output of this command will be outputed to the screen, however, the output can be redirected if desired. Ex. sort < file_list.txt > sorted_file_list.txt
Note: The order of redirection does not matter. The only requirment is that the redirectioin operators must appear after the other options/arguments in the command.

Pipes
^^^^^^^
A 'pipe' is a form of I/O redirection that connects multiple programs together. This is a very powerful tool because the standard output of a program can be immediatly redirected into another program to streamline a task. Ex. ls -l | less - The output of the ls command is sent into the less command.
