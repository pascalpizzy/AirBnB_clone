PROJECT: 0x00. AirBnB clone - The console

Background Context

## Table of contents :clipboard:

 - [Description]
 - [Installation]
 - [File description]
 - [Example]
 - [Contributors]

## Description 
Firstly: To write a command interpreter that manages the AirBnB Objects

This is the first step towards building our first full web application: the AirBnB clone. This first step is very important because we will use what we build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration.

Each task is linked and will help to:

 - Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
 - Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
 - Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
 - Create the first abstracted storage engine of the project: File storage.
 - Create all unittests to validate all our classes and storage engine

What’s a command interpreter?

A command interpreter to manage our Airbnb clone objects:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object


## Installation :floppy_disk:
 - Clone this repository: `git clone "https://github.com/marktos247/AirBnB_clone.git"`
 - Access AirBnb directory: `cd AirBnB_clone`
 - Run hbnb(interactively): `./console` and enter command
 - Run hbnb(non-interactively): `echo "<command>" | ./console.py`

Execution
Your shell should work like this in interactive mode:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit

But also in non-interactive mode: (like the Shell project in C)
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
All tests should also pass in non-interactive mode: $ echo "python3 -m unittest discover tests" | bash



## File description :file_folder: 

```
AUTHORS     /models    test_base_model_dict.py    test_base_model.py    README.md    test_save_reload_base_model.py  
```

## Example : computer:

## Contributors:
```
Mark Ajakaiye - aj.marktos@yahoo.com
Pascal Ikechukwu - pascalikechukwu@gmail.com
```
