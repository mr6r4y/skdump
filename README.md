skdump
======

Simple tool to extract chat logs from Skype history file - main.db.

Usage
-----

    usage: skdump [-h] [-d DUMP_DIRECTORY] skype_db

    Takes skype history sqlite db and dumps it into chat files

    positional arguments:
      skype_db              Path to skype's messages sqlite db

    optional arguments:
      -h, --help            show this help message and exit
      -d DUMP_DIRECTORY, --dump-directory DUMP_DIRECTORY
                            Directory where skype log files are saved. Default is
                            current directory

Requirements
------------

* python-sqlite3