--Create and Edit Text Files--
===================================

Creating a File
^^^^^^^^^^^^^^^^^
The 'touch' command will create file if non-existent::

    touch text_file.txt

The 'echo' command relays a string back to the terminal::

    echo "Hello"

Using redirection with echo, a string can be sent to a file::

    echo "Hello" > text_file.txt

Echo can also append text to file::

    echo "New Info" >> text_file.txt

This will also create a file if non-existent.

cat command - 'concatenate' - send to terminal by default(?)::

    cat text_file.txt

Editors
^^^^^^^^^^^
There are two default command line editors: vim/vi and nano. Nano is self-explanatory.

vi/vim
^^^^^^^^
Vi and vim are command line text editors. They are essentially the same, however, vim has some plugin capabilities(?) that vi doesn't. Vim is a contraction of "vi improved." 

Vi operates in three different modes: command mode, insert mode, and last line mode. 

Insert Mode
^^^^^^^^^^^^^
By default, vi is in command mode. To invoke insert mode, press 'i.'The "-- INSERT --" sign should appear in the bottom left corner if done correctly. Insert mode allows you to write in the file and navigate that file with the arrow keys. Hit the esc key to exit insert mode. This will send you back to command mode. 

Command Mode
^^^^^^^^^^^^^^
Command mode is a case sensitive combinations of one or more letters, can be prefix with a number to repeat the command a certain number of times.

Common commands::

    a - append after cursor
    A - append at the end of a line
    d - delete single character 
    dd -delete full line
    o - insert line
 
    yw - copy word
    yy - copy entire line
    2yy - copy two lines
    p - paste after cursor
    P - paste before cursor 

    U - undo command
    u - step back through all changes 
    / - find a string 

    :w - write (save) the file, but don't exit
    :wq - write and quit
    :q - quit, fails if changes have been made
    :q! - quit without writing

Last Line Mode
^^^^^^^^^^^^^^^^^^

Stream Editor
^^^^^^^^^^^^^^
Using sed
