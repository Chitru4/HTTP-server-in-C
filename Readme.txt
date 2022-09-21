This is a HTTP server made in C and works in Linux.
To compile file use this command on the command line:
gcc HTMLserver.c -o HTML
The executable file will be named HTML and can be run by:
./HTML

After initiating server go to your browser and type localhost:Portnumber (Replace portnumber by the
portnumber displayed on the terminal, can be changed in config.txt)
--The connection is established

The portnumber and the filenames can be changed in config.txt.
If you plan to host more html files just add the html files in the same folder and
add the file name in continuation after a space.

portnumber 80 is the default port number for HTTP.
