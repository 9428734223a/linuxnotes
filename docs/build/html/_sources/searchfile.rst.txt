--Search for Files--
====================
Search by Name
^^^^^^^^^^^^^^^^^^^^^^^^^^
Use the 'find' command to search for a file by name::

    find -name "text_file.txt"

The '-name' argument searches for the name of a file specified in the field that follows it, which is "text_file.txt" in this example. By default, this will only search for "text_file.txt" in the working directory(?). To specify a particular directory to search in, the path must be passed in before the -name argument::

    find / -name "text_file.txt"

This searches for text_file.txt from the root directory and will return the path where the file is located. 

For a quick synopsis of the file system, use the 'df -h' command::

    df -h

This will display the various partitions and where they are mounted on the hard drive. 
On large file systems this can be useful for finding a more specific path as to where a file might be located in order to cut search time. 

In order to ignore case sensitivity, pass in the '-iname' argument instead of '-name'::

    find / -iname "text_file.txt"

This will return all results of "text_file" regardless of case.

(NEEDS TO BE FINISHED)
