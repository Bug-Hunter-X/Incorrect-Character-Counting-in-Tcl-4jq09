# Incorrect Character Counting in Tcl
This repository demonstrates a common error in Tcl when attempting to count characters in a string using the split command with an empty string argument. The error lies in an incorrect understanding of how split behaves with an empty string and how to correctly iterate over a string's characters. 

## Description
The bug is in the `count_chars` procedure.  The intention is to count the characters in an input string. However, the `split` command with an empty string argument splits the string into individual characters, leading to a correct character count. The original problem was intended to illustrate an error where the empty string splitting wasn't handled correctly, but the example was unintentionally correct.

## Solution
The solution shows a corrected version of the procedure that handles empty strings gracefully and properly counts characters.

## How to reproduce the bug
1. Save the code in `bug.tcl`.
2. Run the script using a Tcl interpreter (e.g., `tclsh bug.tcl`).

## How to fix the bug
1. Replace `bug.tcl` with `bugSolution.tcl`.
2. Run the script using a Tcl interpreter.