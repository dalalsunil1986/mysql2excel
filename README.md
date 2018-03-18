mysql2excel
=============

Command-line tool to dump MySQL tables to Microsoft Excel Spreadsheets written
in Java.


## Downloading

Download the precompiled .jar file or clone the repo from
https://github.com/DevDungeon/mysql2excel and then run:

    mvn package


## Usage

### Print help information

    java -jar mysql2excel-1.0.0.jar

### Generate a settings template file

    java -jar mysql2excel-1.0.0.jar -g sample.config

### Dump from MySQL to Excel using settings in config file

    java -jar mysql2excel-1.0.0.jar my.config


## Project Page

* https://www.devdungeon.com/projects
* https://www.github.com/DevDungeon/mysql2excel

## Contact

NanoDano <nanodano@devdungeon.com>


## Changelog

* 2018-18-03 v1.0.0 - Initial stable release
