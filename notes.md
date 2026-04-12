# Truffula Notes

As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java

- Seems to be where the run commands would be in the terminal.
- Add options for show hidden files, or colors.

## ConsoleColor.java

- File that gives the list of colors for the terminal.
- Has a getCode method to recieve the ANSI code.

## ColorPrinter.java / ColorPrinterTest.java

- Class that is using the ConsoleColor enum, to apply color to the text.
- Seems to need to reset every time.
- Testing to make sure each test works?.

## TruffulaOptions.java / TruffulaOptionsTest.java

- Seems to be where you can set the options for running the terminal to print the tree.
- Full of boolean methods.

## TruffulaPrinter.java / TruffulaPrinterTest.java

- Prints the actual directory tree. Using the Colors and Options.

## AlphabeticalFileSorter.java

- Sorts the files into alphabetical order.
