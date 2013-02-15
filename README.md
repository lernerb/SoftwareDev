# SPIMS
## Semester Project Image Matching Software
### CS4500 Software Development - Professor William Clinger
#### Course Website: http://www.ccs.neu.edu/course/cs4500wc/

##### Authors - Emails
 * Brandon Lerner - lernerbrandon@gmail.com
 * Nathan Heaps - nsheaps@gmail.com
 * Lennon Acosta - lacosta@ccs.neu.edu
 * Jayson Ng - jaysonzeon@gmail.com

##### Compiling
Because the program is based in python, no additional compiling is required in order to run the sofware

##### Installing
Add ./ to your path in order to run `./spims`.

##### Running
The software can be invoked using the format specified in the assignment. For convenience it has been duplicated here:

    ./spims -p <file1> -s <file2>

where:
 * `<file1>` is the name of an existing file in JPEG, PNG, or GIF format without animation (the "pattern image")
 * `<file2>` is the name of an existing file in JPEG, PNG, or GIF format without animation (the "source image")

##### Testing
Change directories into the Scripts folder and run the following

    ./tester assignment4

The tester uses the first argument to determine what set of tests to run. `assignment4` is the set of tests specified in the assignment given by Professor Clinger.

##### Additional notes
It was discussed with Prof. Clinger on Feb 12 that additional line returns at the end of the execution of the program do not matter.

##### Third-Party Software Credits
 * Python 2.6
   * numpy
   * scipy
   * PIL

