# recovery-project


## Objective 

Read files in bytes using the **recover** concept in Java, to read the contents of a file as an array of bytes.

## Problem

Implement the concept of recovering files using the `XOR` operation.


## Implementation

* Create two text files, `file1.txt` and `file2.txt`, with data.

* Read the contents of both files.


* Convert the contents of both files to **bytes**. to read the contents into a byte array.

* Perform an `XOR` operation on the bytes of both files. This will create a new byte array that represents the XOR of the two files.

* Store the resulting byte array in a new file, for example, xor_result.txt.

* Delete one of the original files, for example, file2.txt.

* Recover the deleted file, read the remaining file (file1.txt) and the XOR result file (xor_result.txt), and Perform an XOR operation on the bytes of these two files, which will give you the original contents of the deleted file (file2.txt).
