# Ccode
C coding exercises

File general.h is a colection of macros and functons for general propuse.
File test.h is a program that calls a selected macro by program's first argument, and next arguments are used as a macros's arguments if they are required.
Both codes work correctly in any operative system, case are independent for any C's library except for use of printf function to show results from each test process.

Instructions:
-Compile test.c using your prefered compiler.
-Select a label from fucntion_list enum at top of general.h.
-Searach for the label defined in functionlist matrix at top of the code that refers to macro's index delectred from function_list.
-Run the output binary file from compilation using the selected label from function list, and next for macro's arguments if are needed.
-Macro label can be calles with upper or lower case indistincly.
-Examle ./<binary_file_name> <macro_label> <macros_argument_1> <macros_argument_2>...

Error codes:
-255: There aren't arguments.
-254: Label not defined.
-253: Test code not defined.
-252: Not enough arguments
-251: Invalid type of arguments for selected macro.
