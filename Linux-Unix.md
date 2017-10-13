<center> <h1>Linux and Unix command line foo</h1> </center>

### OS X Unix commands
1. OS X - Figure out what is listening on any port (:80 used in example)

   `sudo lsof -i ':80'`
    found here  
    https://superuser.com/questions/597398/no-idea-what-is-listening-on-port-80-in-os-x

2. Search for a string in files

    Within a git repository
        `git grep "<enter_any_string_here>"

    Alternate method
        `grep "<enter_any_string_here>" -R .
    
    This solution was shown to me by Jason Meridth https://github.com/jmeridthgst

3. Open file with a specific application from the command line in OS X

    `open <filename.extension> -a Google\ Chrome` Replace <filename.extension> with the file you wish to open

    This tells your machine to open the file with application Google Chrome. `-a` denotes "with application"

    I combined the information found in this thread, https://superuser.com/questions/85151/how-to-open-a-browser-from-terminal