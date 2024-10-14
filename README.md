Steam has the achievement "Solve SELF-TEST DIAGNOSTIC in over 100,000 cycles.", but I went further and wanted to complicate the algorithm as much as possible.

The essence of the algorithm: 
in both slots of the block, the maximum possible number is created, one is constantly subtracted from one slot, 
when the slot value reaches a negative number, the algorithm will subtract 1 from the second slot, and the cycle will start anew. 
This happens until the second slot becomes a negative number, which means the end of all cycles, and the data is finally transferred further to its destination.

As a result, we have 1000*1000 operations on numbers only, and a certain number of mandatory binding operations to make the program work

Let's go further: in one block for one number of 1M + operations, there are 8 blocks in total and 156 numbers (in one test there are 39 numbers, total 4 tests). 
We multiply and get the number of operations over a billion.

Experimentally, I found out that in fast mode, the device performs about 6k operations per second, so the level with this algorithm will be solved in about 8 hours!

In general, this is my first file on Git and I do not know what to write in the ReadMe, let it be this :)



Exactly, here you can also specify the instructions where to save the file!

Open the TIS-100 and select the "Self-test diagnostic" level, in the upper left corner there will be the "Open save directory" button. 
A folder opens in which you need to insert the file (with a replacement if there is already a file with that name), and the code from the file should appear in the third save slot.

That seems to be it now. Thank you all, bye everyone)
