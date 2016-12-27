--Compare Text Files and Binary Files--
=========================================

Use the 'sort' command to sort a text file::

    sort text_file.txt

By default, sort orders a file in alphabetical order. It also has other various arguments that can be passed for different methods of sorting. One example would be reverse alphabetical order::

    sort -r text_file.txt

Use the 'fmt' command to format a file. Synopsis of the fmt command::

    fmt [-c] [-s] [-w width | width] [inputfile]

Example of the fmt command to format a file with uniform spacing::

    fmt -u text_file.txt

The '-u' argument means that it will be formated in uniform format(?).
This command can be used for formatting log files with unusual spacing or characters (?).

Use the 'nl' command to list the number of lines in a given file::

    nl text_file.txt

Use the 'cut' command to...
