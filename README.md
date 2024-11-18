# AirBnB Clone - The Console

## Project Description
This is the first step of the AirBnB clone project. The command interpreter serves as a tool to manage AirBnB-like objects via the console.

## Features
- Interactive and non-interactive modes.
- Commands: `quit`, `help`, `EOF`.

## How to Start
```bash
./console.py
```

### Interactive mode (example)

```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) create User
1234-5678-9012
(hbnb) show User 1234-5678-9012
[User] (1234-5678-9012) { ... object attributes ... }
(hbnb) quit
$
```

### Non-interactive mode (example)

```bash
$ echo "create User" | ./console.py
(hbnb)
1234-5678-9012
(hbnb)
$
```
