# File Recovery Project


## Objective 

Understand how to read files as an array of bytes and use the **XOR** operation to recover one file if missing. 

## Problem

Implement the **XOR** operation to recover a file.


## Implementation

* Create two text files, `first.txt` and `second.txt`, with data.

* Read the contents of both files as bytes.

* Convert the contents of both files to **bytes**. And store them in byte arrays.

* Perform an **XOR** operation on the bytes of both files. This will create a new byte array that represents the XOR of the two files.

* Store the resulting byte array in a new file, for example, **result.txt**.

* Delete one of the original files, for example, second.txt.

* Recover the deleted file by reading the remaining file (first.txt) and the XOR result file (result.txt), and perform an XOR operation on the byte arrays of these two files, which will give you the original contents of the deleted file (second.txt).
