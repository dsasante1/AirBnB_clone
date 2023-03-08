# 0x00. AirBnB clone - The console

## 0x01 Introduction

Team project to build a clone of AirBnB

### console

The console will perform the following tasks:

* create a new object
* retrive an object from a file
* do operations on objects
* destroy an object

### Storage

All the classes are handled by the Storage engine in the FileStorage Class.

## 0x03 Installation

```bash
git clone https://github.com/aysuarex/AirBnB_clone.git
```

change to the `AirBnb` directory and run the command:

```bash
 ./console.py
```

### Execution

In interactive mode

```bash
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

in Non-interactive mode

```bash
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
``
