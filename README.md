![AirBnB logo](https://github.com/asmeyb/AirBnB_clone/blob/master/imgs/AriBaB.png)

# <h1 align="center">AirBnB clone The Console</h1>

> HolbertonBnB is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.

This is the first part of a project for Holberton School(ALX(The Room) SE): AirBnB clone - The console. First step: Write a command interpreter to manage the AirBnB objects.

## The command interpreter

The command interpreter is currently capable of:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc
- Do operations on objects (count, compute stats, etc)
- Update attributes of an object
- Destroy an object

## Execution

this shell works like this in interactive mode:
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```

But also in non-interactive mode
```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```

## Authors
* Asmamaw Yismaw Baylie | [GitHub](https://github.com/asmeyb) |
* Dagem Tsehay | [GitHub](https://github.com/dagemtsehay1) |
