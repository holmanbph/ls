LS
==========

List information about the files.  By default, the current directory is listed. 


INSTALLATION
------------

This program should be straightforward to run and work with once dependencies are installed. 
	
	$ git clone https://github.com/holmanbph/ls.git

	$ cd ls

	$ gcc ls.c -o ls -O2 


The program should now be ready to run! 

	$ ./ls


SYNOPSIS
--------

ls [OPTIONS]... [FILE]...

	
Runtime Options
---------------

OPTIONS

	-a 		 			prints all files, including files that start with . 

	-l 					long format

	-R					recursively print all subdirectories  

	-h	  				help instructions


EXAMPLES
--------
	./ls -R /

	./ls -l ../../


AUTHOR
------
	Written by Brett Holman in Spring 2018. 

