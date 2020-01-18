# vm
Final project for object-oriented software development course.

A copy of the Vim text editor with syntax highlighting, custom themes and 55 commands, including macros. For a full list of supported commands, see below.

Designed following the SOLID principles for object-oriented design by using the MVC framework and multiple Design Patterns.

Created in Linux terminal using C++ and the ncurses library.

![Sample File](https://github.com/cherrykit/vm/blob/master/Sample%20file.png)

![An Empty File](https://github.com/cherrykit/vm/blob/master/An%20empty%20file.png)

![Recording a Macro](https://github.com/cherrykit/vm/blob/master/Recording%20a%20macro.png)

![Inserting Text](https://github.com/cherrykit/vm/blob/master/Inserting.png)

List of supported features:

* Cursor movement both character- and linewise, as well as to specific line numbers, the beginning or end of the file and matching brackets. Furthermore, word by word movement both backward and forward as well as movement to the beginning or end of a line is supported.
* Insertion through insert mode, both before and after the current character. Furthermore, insertion after first whitespace and at the end of the line is supported. 
* Replace mode and replacement of single characters.
* Deletion of single characters, whole lines, or of all characters between arbitrary movement commands.
* Search for next and previous instances of characters and strings.
* Replacement of newlines with a single space.
* Copy and paste commands, where copying of whole lines, single characters, or all characters between arbitrary movement commands is supported.
* Ability to undo an arbitrary amount of previous modifications.
* Repetition of previous modifications and searches is supported.
* Saving and quitting as well as the printing of file information is supported.
* Commands can be prefixed with numeric multipliers that execute the commands multiple times.
* Macros that allow the recording of a sequence of commands into a register and the subsequent repetition of the sequence.
* Line wrapping for long lines of text.
* Syntax highlighting including identifiers, strings, keywords, numerals and comments as well as custom colour themes.
