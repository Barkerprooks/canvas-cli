# Canvas Cli v0.0.2
A way to interface with canvas from the command line.

## Why?
I wanted to practice web scraping, plus I always forget when things are due.

## How to Use
Python 3 is required  
```
$ pip install -r requirements.txt
$ ./canvas-cli -u <username> -d <sub domain>

canvas-cli:
    --username / -u    Canvas username (required)
      --domain / -d    Canvas subdomain (required)
        --help / -h    Prints this page
         --all / -a    Shows past assignments

example: ./canvas-cli -u student01 -d unt

Note: -d is the school name most of the time, 
      it's the 'name' in the url: https://name.instructure.com
```

## Features
+ Print all current assignments, their due dates, and how long until they're due
+ View assignment information like title, and description
+ Download assignment files to the current directory

## Upcoming
- Allow user to supply a new directory for specific assignment downloads
- See grades for past assignments 
- Turn in an assignment by supplying a path, class id, and assignment id
- Turn in an assignment by supplying a path and selecting a class and assignment by menu
- Print user info such as name, groups, unread messages, etc.
