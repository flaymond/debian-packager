## How to install -

1. Copy checksize, controlc and packdeb to the /usr/local/bin/

## How to remove -
1. Uninstalling it by removing the files from /usr/local/bin/

## How to use -

1. Make sure your package name contain the version number (eg. mypackage-1.0)
2. Also make sure your package contain DEBIAN directory
		

## Running -

1. Firstly, cd to the location of your package (not into it)

2. Open up terminal, and type **checksize mypackage**
	
	- This will check mypackage directory size. Please remember the number after executing it, for control file.

3. Now type **controlc mypackage**
	
	- Just fill in the blanks. Use the number you saw after the **checksize mypackage** command to fill,
	  the Installed-Size section. (eg. Installed-Size: 20)

4. If you satisfied with control file in mypackage/DEBIAN/ , type **packdeb mypackage** to package it into as working .deb


## NOTE

I already made a pre-made package (mypackage-0.1.zip) on top directory, if you want to try package it right at the moment.

To test the package if it's work, install the .deb (after you build it), and type **roller.py** to see the outputs.

Feel free to leave a star for the repository if you like the idea and the scripts! :)
