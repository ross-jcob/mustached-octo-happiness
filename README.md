mustached-octo-happiness
========================

Ron Swanson's toolshop

About the project
=================
Purpose:
- learning, experimenting
- comments, code reviews welcomed and greatly appreciated

Project goals:
(short version)
Move data from delimited file to SQL database, while checking for errors,
typos in text entries etc. Fix those. And be able to save information about how the file was parsed
to a file for later reuse.

As this project is mainly for learning purposes,
it is not a weekend, quick'n'dirty solution.
I will rewrite it in other languages (currently in C#, next up: C/++, python).

Progress:
- [done] string approximation library
- [wip] core library
- command line interface
- [wip] gtk# interface
- web interface
- windows forms interface



Longer version:
Take delimited file (*.csv, *.txt atm.), specify delimiters, text qualifiers etc.
while showing sample of n lines from the file.
[Next] Guess/specify data types, consistency/error check.
Specify which columns will go through string approximation for error/typo checking.
String approximation etc. (word order, general typos ..)
[Next]
[option]: Save parsing information as template for reuse.
[option]: Save result as local SQLite file.
Save result to specified SQL database.

