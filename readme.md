# Canvas Cli v0.0.1
A way to interface with canvas from the command line.

# Why?
Because I wanted to practice web scraping, and I always forget when things are due, so here we are.

# How to Use
Python 3 is required  
```
$ pip install -r requirements.txt
$ ./canvas-cli -u <username> -d <sub domain>

example: ./canvas-cli -d unt -u student01 : prints upcoming assignments for student01 who goes to unt

options:
  --username / -u   Canvas username (required)
    --domain / -d   Canvas sub domain (required)
       --all / -a   Show past assignments
      --help / -h   Print this screen
```
Note: -d is the school name most of the time, it's the 'name' in the url "https://name.instructure.com"

# Future Features
+ ability to see grades for past assignments 
+ ability to turn in an assignment by supplying a path, class id, and assignment id
+ ability to turn in an assignment by supplying a path and selecting a class and assignment by menu
+ print user info such as name, groups, unread messages, etc.
+ 
