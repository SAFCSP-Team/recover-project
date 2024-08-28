# File Recovery Project

## Objective 
Understand how file recovery systems work.
## Problem

Implement the **XOR** operation to recover a file.


## Implementation

* Create two text files, `first.txt` and `second.txt`, with some data inside each one of them.

* Read the contents of both files.

* Convert the contents of both files to **bytes** and store them in byte arrays.

* Perform an **XOR** operation between the byte arrays of both files, so this will create a new array that represents the XOR of the two files.

* Store the resulting byte array in a new file, for example, `result.out` (Note: The output will be binary not text).

* Delete one of the original files, for example, `second.txt`.

* Recover the deleted file by reading the remaining file `first.txt` and the XOR result file `result.out`, and perform an XOR operation on the byte arrays of these two files, which will give you the original contents of the deleted file `second.txt`.

* Write the result to a new file `second.txt` and check its content.
