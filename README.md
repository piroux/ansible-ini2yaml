Ansible INI to YAML inventory converter
=======================================

This repository contains a Python script for converting Ansible inventories in INI format to YAML format.

Usage
-----

```console
$ ./ini2yaml -h
usage: ini2yaml [-h] [-m {inventory,flat}] [-d] ini_filepath

Read a INI file and print it converted to a YAML format on stdout

positional arguments:
  ini_filepath          File path of the source INI file

optional arguments:
  -h, --help            show this help message and exit
  -m {inventory,flat}, --mode {inventory,flat}
                        Mode chosen for the final YAML file
  -d, --disable-default-section
                        Add one default section (required if the INI source
                        file is section-less)
```
