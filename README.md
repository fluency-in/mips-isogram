# MIPS Assembly: Isogram

Determine if a word or phrase is an isogram.

Determine if a word or sentence is an isogram.
An isogram (also known as a "nonpattern word") is a word or phrase without a repeating letter.

Examples of isograms:

- lumberjacks
- background
- downstream

The word *isograms*, however, is not an isogram, because the s repeats.

For these problems, we use the popular MIPS simulator [MARS](http://courses.missouristate.edu/KenVollmar/mars/). Download the MARS jar archive from the MARS website and place it somewhere easily accessible. Also install the Java SDK if you do not have it already.

To run the tests, assemble and run the test runner file for a given exercise either via the MARS simulator GUI, or on the command line. To run on the command line,
specify first the runner file and then your implementation, like so:

    java -jar /path/to/mars.jar nc runner.mips impl.mips

To run in the GUI, `include` your implementation at the bottom of "runner.mips"
by uncommenting the final line.

The test runner will either complete with a “success” message or terminate on a failing test with a message specifying the input for which that test failed.

## Source

Wikipedia [https://en.wikipedia.org/wiki/Isogram](https://en.wikipedia.org/wiki/Isogram)

This exercise is from the [MIPS Assembly][mips] track on [Exercism][exercism]

[exercism]: http://exercism.io
[mips]: http://exercism.io/languages/mips



