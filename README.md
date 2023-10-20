
# AirBnB Clone - The Console
The console is the first segment of the AirBnB project at Holberton School that will collectively cover fundamental concepts of higher level programming. The goal of AirBnB project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB). A command interpreter is created in this segment to manage objects for the AirBnB(HBnB) website.

#### Functionalities of this command interpreter:
* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc...
* Do operations on objects (count, compute stats, etc...)
* Update attributes of an object
* Destroy an object

## Table of Content
* [Environment](#environment)
* [Installation](#installation)
* [Project Description](#project-descriptions)
* [Project Structure](#project-structure)
* [Project Usage](#examples-of-use)
* [Bugs](#bugs)
* [Authors](#authors)
* [License](#license)

## Environment

<!-- ubuntu -->
<a href="https://ubuntu.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Ubuntu&color=E95420&logo=Ubuntu&logoColor=E95420&labelColor=2F333A" alt="Suite CRM"></a> <!-- bash --> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GNU%20Bash&color=4EAA25&logo=GNU%20Bash&logoColor=4EAA25&labelColor=2F333A" alt="terminal"></a> <!-- python--> <a href="https://www.python.org" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Python&color=FFD43B&logo=python&logoColor=3776AB&labelColor=2F333A" alt="python"></a> </a> <!-- vim --> <a href="https://www.vim.org/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Vim&color=019733&logo=Vim&logoColor=019733&labelColor=2F333A" alt="Suite CRM"></a> <!-- vs code --> <a href="https://code.visualstudio.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Visual%20Studio%20Code&color=5C2D91&logo=Visual%20Studio%20Code&logoColor=5C2D91&labelColor=2F333A" alt="Suite CRM"></a> </a><!-- git --> <a href="https://git-scm.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Git&color=F05032&logo=Git&logoColor=F05032&labelColor=2F333A" alt="git distributed version control system"></a> <!-- github --> <a href="https://github.com" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GitHub&color=181717&logo=GitHub&logoColor=f2f2f2&labelColor=2F333A" alt="Github"></a>
 <!-- Style guidelines -->
* Style guidelines:
  * [pycodestyle (version 2.7.*)](https://pypi.org/project/pycodestyle/)
  * [PEP8](https://pep8.org/)

All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0 . Control version using Git 2.25.1.

## Installation
* Clone this repository: `git clone "https://github.com/Kboateng346/AirBnB_clone.git"`
* Access AirBnb directory: `cd AirBnB_clone`
* Run hbnb(interactively): `./console` and enter command
* Run hbnb(non-interactively): `echo "<command>" | ./console.py`

## Project Description

This project is a command line interpreter that permits management of the backend of HolbertonBnB.

## Project Structure

The project structure is as follows:

```
├── console.py
├── models
│   ├── BaseModel.py
│   ├── City.py
│   ├── Place.py
│   └── User.py
├── README.md
└── tests
    └── test_console.py
```

## Project Commands

The following commands are available in the console:

* `create`: Creates a new instance of a given class.
* `show`: Prints all string representation of all instances of a given class.
* `count`: Prints the number of instances of a given class.
* `destroy`: Destroys an object.

## Project Usage

To use the console, simply run the following command:

```
python3 console.py
```

The console will then prompt you for a command. Enter the desired command and press Enter.

## Bugs
No known bugs at this time. 

## Authors
Hasford Kwadwo Boateng - [Github](https://github.com/Kboateng346) | [Twitter](https://twitter.com/HasfordKwadwo)  | [Email](kboateng346@gmail.com)

## License
Public Domain. No copy write protection. 