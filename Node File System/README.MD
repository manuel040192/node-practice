Node File System:

Read files:

Usage of "fs.readFile('demofile.html' ..." to read a HTML file and use it on a server that was created using "var http = require('http');" 
and "http.createServer( ...".

Create files:

Usage of "fs.appendFile('mynewfile1.txt', 'Hello content!' ..." to create a file called mynewfile1.txt that contains the text 
'Hello content!'.

Update files:

Usage of "fs.appendFile('mynewfile1.txt', ' This is my text.' ..." to update a file called mynewfile1.txt that contained the text 
'Hello content!' and after the update it now contains the text 'Hello content! This is my text.'.

Delete files:

Usage of "fs.unlink('mynewfile2.txt' ..." to delete the file mynewfile2.txt.

Rename files:

Usage of "fs.rename('mynewfile1.txt', 'myrenamedfile.txt' ..." to rename the file mynewfile1.txt to myrenamedfile.txt.
