# C++ Catch2
Example C++ using Catch2.

This program will accept the following arguments:

* the filename of a CSV file,
* the name of the column to overwrite in that file,
* the string that will be used as a replacement for that column,
* the filename where the output will be written.

For instance, if the CSV file had a column “City” with various values for the entries in the file, calling the tool with the name of the input file, City, London and the name of output file would result in a copy of the initial file, but with all cities set equal to “London”:

# Original Source
https://www.fluentcpp.com/2017/11/03/unit-tests-express-code-intent/
