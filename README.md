# 0x00. AirBnB clone - The console

<img src="hbnb.png" width="1000" height="400"/>

## Synopsis

The Airbnb clone project for which we are creating a copy of the Airbnb. This is the first step towards building our
first full web application.In this clone, only some features will be implemented and will be
listed below once completed.

## How to use the console?

Have you ever worked with the unix shell before? If yes, then that's exactly how this console works
It works both in interactive and non-interactive mode, the prompt **(hbnb)** is first display and
wait for the user for input.

## Usage

To launch the application:

- interactive mode

`./console.py`

- non-interactive mode

`echo ""command" | ./console.py`

#### Commands

| Commands | Description                                                                        | Usage                                                                                                                                 |
| -------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| help     | Display commands that are documented                                               | help                                                                                                                                  |
| help     | Display documented help for a command                                              | `(hbnb) help <command>`                                                                                                               |
| quit     | Exits the program.                                                                 | `(hnbnb) quit`                                                                                                                        |
| EOF      | Exits the program when an EOF signal is recieved.                                  | `crtrl d`                                                                                                                             |
| create   | Create an object, creates a json file with objects presentation and prints its id  | `(hbnb) create <class_name>`                                                                                                          |
| show     | Prints string representation of an object based on the given class name and id     | `(hbnb) show <class_name> <id>` `(hbnb) <class_name>.show(<id>)`                                                                      |
| destroy  | Deletes an object based on the given class name and id.                            | `(hbnb) destroy <class_name> <id>` `(hbnb) <class_name>.destroy(<id>)`                                                                |
| all      | Query all the object and print a list of all objects in a string format            | `(hbnb) all <class_name>` `(hbnb) <class_name>.all()`                                                                                 |
| update   | Update an object base on the given class name and id, it's update or add attribute | `update <class_name> <id> <attribute name> <attribute value>` `(hbnb) <class_name>.update(<id>, <attribute name>, <attribute value>)` |
| count    | Retrieve the number of instances of a class                                        | `(hbnb) <class_name>.count()`                                                                                                         |
