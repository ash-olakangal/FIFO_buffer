# FIFO memory buffer

An implementation of FIFO memory buffer in verilog.

The size of each memory element is 4-bits wide. 
The size of each address is 3-bits and hence the maximum number of elements that it can hold is 8 (each 4-bits wide).

There are two operations of read and write that can be performed. If the memory is empty, the empty flag will be set and if it is full, the full flag will be set.
