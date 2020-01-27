# pytemplate

Command-line tool for creating a template python file

## Version
2.0

## Requirements
Python 3

## Installation
Copy pytemplate to /usr/local/bin and make sure permissions are set to rwxr-xr-x ($ chmod 755 /usr/local/bin/pytemplate)

## Usage
Run `pytemplate -h` for a list of options.

If you're running pytemplate for the first time, you need to setup the configuration file by running `pytemplate -c` and providing the values at the prompt. For now pytemplate will save the config file as ~/.pytemplate.conf in your home directory.

To create a python file run `pytemplate`.

To also have pytemplate create a git repo for the python file being created, run `pytemplate -g`.

## Author
Dayo Ntwari <dayontwari@gmail.com>

## License
GNU GPLv3
