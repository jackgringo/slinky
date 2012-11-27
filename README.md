# Slinky - a symlinking tool

Work in progress.

- Place slinky in a directory in your $PATH e.g. /usr/local/bin
- Create a config directory

Try this...

    ~$ cp slinky /usr/local/bin
    ~$ mkdir ~/.slinky
    ~$ echo "/Users/username/Code" > ~/.slinky/directories
    
Use if like this...

    ~$ slinky link <source> <optional destination>
    
Try something like this...

    ~/Sites/project$ slinky link modernizr*
    
And you'll get something like this...

    2 files found:

    [0] /Users/username/Code/js/enquire.js/demo/js/libs/modernizr.js
    [1] /Users/username/Code/js/modernizr.js

    1 directories found:

    [2] /Users/username/Code/js/Modernizr
    
Choose an option, and there you have it!

To be continued.
