# Py++
Merge of Python and C++ that can compile to either.

## Usage
All transpilers are bare versions that don't have the compiler/interpreter for the target language.
To use this language, you must install an application that can run the target code, like the Python
interpreter or the C++ compiler. The transpiler can compile then run or output the code to a file.
This language is not meant to be ran as-is or used in a final product. It is best to use one of the
existing target languages.

## File structure
Py++ files are renamed tar.gz archives, and inside, there is an 'options.json' and a 'code' file.
The options.json file allows you to set features of the code, like dynamic or static typing, or
a garbage collector. The code file contains the real code, and can be treated as a text file.

## Bugs/feature tracker
### version 0.0.0A
There is no transpiler for either language.
