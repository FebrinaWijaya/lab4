# lab4
# question A
By using nm, I found these 2 lines associated with the functions.
<br> 00000000004052d T _Z7averageif
<br> 0000000000404ed T _Z7averagePdRd
<br> The first one is for function "int average(int n1, float n2)". The symbols "_Z7averageif" mean that the function name is average with length 7, and its parameters are of type integer and float.
<br> The second one is for function "double average(double * n1, double & n2)", and the symbols "_Z7averagePdRd" mean that the function name is average with length 7, and its parameters is of type Pointer to Double, and Reference to Double.
# question B
I got this output for question B:
<br> 1 8
<br> 4 8
<br> 4 8
<br> 8 8
<br> The size of char is 1, the size of integer and float is 4 bytes, the size of double is 8 bytes, while the size of all type of pointer is 8 bytes.
<br> The size of pointer depends on whether we compile the program in 16-bit, 32-bit, or 64-bit machine. Because I am compiling it in 64-bit machine, so the size of the pointer is 8 bytes. If it is 16-bit, then the size of the pointer will be 16 bits which is equal to 2 bytes. If it is 32-bit, then the size will be 32 bits = 4 bytes.
