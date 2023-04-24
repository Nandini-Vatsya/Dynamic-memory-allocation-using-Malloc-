# Dynamic-memory-allocation-using-Malloc-
<br><b><ins>Dynamic Memory Allocation</b></ins> can be defined as a procedure in which the size of a data structure (like Array) is changed during the runtime.<br>
C provides some functions to achieve these tasks. There are 4 library functions provided by C defined under <stdlib.h> header file to facilitate dynamic memory allocation in C programming. They are: <br>

malloc()<br>
calloc()<br>
free()<br>
realloc()<br>
<br>
<b><ins>C malloc() method</b></ins><br>
The “malloc” or “memory allocation” method in C is used to dynamically allocate a single large block of memory with the specified size. It returns a pointer of type void which can be cast into a pointer of any form. It doesn’t Initialize memory at execution time so that it has initialized each block with the default garbage value initially. <br>
<br>
<b> Syntax: </b><br>
ptr = (cast-type*) malloc(byte-size)<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234002054-8c8e9269-929b-467b-a291-15f08414a7a0.png)

<br>
<br>
<b><ins>Output</b></ins><br>
<br>
<img width="946" alt="malloc" src="https://user-images.githubusercontent.com/125802204/234004970-47a4d886-d22c-4c55-9c99-94b1b599feb1.png">
