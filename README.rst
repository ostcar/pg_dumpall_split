pg_dumpall_split
================

The PostgreSQL command pg_dumpall generates one backupfile over all
databases. Sometimes you have to restore only one database. So you need to
get it out of the one big file. To solve this problem, you can use this
small python script.

The script takes a file created with pg_dumpall and generates one file for
each database.

Usage
-----
pg_dumpall_split PATH_TO_DUMP_FILE DIRECTORY

