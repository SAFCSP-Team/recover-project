# File Recovery Project

## Objective 
Understand how file recovery systems work.
## Problem

Implement the **XOR** operation to recover a file.


## Implementation

* Create two text files, `first.txt` and `second.txt`, with data.

* Read the contents of both files.

* Convert the contents of both files to **bytes**. And store them in byte arrays.

* Perform an **XOR** operation between the byte arrays of both files. This will create a new byte array that represents the XOR of the two files.

* Store the resulting byte array in a new file, for example, `result.out` (Note: The output will be binary not text).

* Delete one of the original files, for example, `second.txt`.

* Recover the deleted file by reading the remaining file `first.txt` and the XOR result file `result.txt`, and perform an XOR operation on the byte arrays of these two files, which will give you the original contents of the deleted file `second.txt`.
