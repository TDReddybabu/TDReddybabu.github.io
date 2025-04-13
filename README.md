# DS
## Welcome to my interview experiance world
# Samsung Semiconductors

### virtual round:

1. Detailed Explanation about CV.
2. How will you change from secure to Non-secure state of exceptions?
3. what is boot loader and explain in details about each boot loader?
4. what is Primary BL and where it sits, can it be modified?
5. Secure boot In details?( explain about Chain of trust / root of trust)
6. What is Volatile, Static and explain about storage classes?
7. Compilation process steps (.I,.s,.o,.exe/.elf)
8. what is an interrupt, how it acts?
9. String literals?
char* s = "Hello world";
char* s[1]=y;
printf("s\n"); what is the output?
10. PCU Driver in details?
11. how MMU can act if hypervisor enabled?
12. what is CacheDump and how cache dump will read happen and what are registers used to read instructions and data explain in details?
13. How will you deliver cachedump?

### F2F round:

1. Exception explanation by drawing a picture?
2. Storage Classes, CacheDump hits and miss and how to avoid cache miss?
3. write a code to find area of square of circle in a grid? size of area of inside circle(100<r<1000).
4. #define add(a,b) a+b+add(a,b)
int main ()
{
pf("%d", add(a,b));
return 0;
}output?
5. write a code to find a number of islands i.e., 1's and 2's in a grid?
6. write a code whether the loop exist or not in a single linked list?
7. write a logic that should follow : 1,2+1,3+2,5+3,8+5,3+8,1, end here.(not understand question properly) 
8. asked complete flow and pros, consts in cachedump
9. implement a heap alogirithm
10. Write a code to extracts a bit in a 32 bit register(also set,clear and flip)?
11. Impement a strcpy without strcpy?
12. what is the efficient algorithm to implement cache dump in best cache approach?
13. What is pointer and double pointer?
14. int alloc (){}
int main () {
int *ptr = NULL;
alloc();
pf("%d", *p);
what is miising and output?

# MicroSoft

### Virtual Round:

1. Write code for creation of two threads, both the threads can share both same memory?
2. Diff between macro and inline function?
3. what is memory leak and write a code that creates Memory leak and prevention.
4. explain difference between bootloaders and firmware?
5. Explain about dereference Pointer with example code?
6. Difference between Mutex and Semaphore and write a code to create it?
7. const and volatile qualifiers in C?
8. Write a code to check an integer is power of 2,4?
9. output of the below code:
int main()
{ 
int x=-4;
x=x>>1;
printf("%d\n",x);
}

10. int main()
{
int x=-9;
x=x<<1;
printf("%d",x);
}
output?

### F2F Round:
### Morning session:

1. Detailed explanation of CV?
2. CacheDump RAMINDEX register and it's usage?
3. Code to count set bits in an integer?
4. Are the expressions *ptr++ and ++*ptr same?
5. what does the keyword const mean and used?
6. what is virtual memory? consider the two statements and find the difference between them?
7. Macros for data manipulations in C?( I wrote swap nibbles in a byte, macro to swap two bytes, macro to swap two numbers)
8. write a code for endianness?
9. why buffer flows are harmful?
10. How to call a function before main()?
11. program to copy string using pointers?
12. find the duplicate and remove number on a given integer array, a given place?
13. how to solve dangling pointer?

### Afternoon Session:

1. Question on Static vs Dynamic allocation. i.e., Explain the trade-offs between static and dynamic allocation in embedded systems. write a function that uses a statically allocated circular buffer for storing 8-bit sensor values.
2.write a function to fill unused stack space with a known pattern and detect overflows.(you are working on a resource-constrained system with limited RAM. Describe how you would estimate and monitor stack and heap usage during runtime.)
3. Explain how cache coherency can affect memory operations with DMA. then, write a C function to prepare a buffer for DMA transmission considering:
* Cache Invalidation or cleaning
* Memory alignment

### HR Round:
explain about your family?
what if you selected then what is approach towards work plan?

# AMD

### Virtual round 1:

1. completely on CV
2. write a assembly code add two elements without third variable.
3. Explain about Memory management in C
4. set a nth bit in a register
5. Exception Levels and Dynamic Shared Unit?

### Virtual round 2:

1. Write a code that prints only vowels starting words in a given sentence.
2. PCU driver modes and it's responsibilities
3. Boot flow with and without secure OS?
4. Implement a BFS and DFS algorithms, explain difference between them.

### Virtual round 3:

1. explain about cache dump flow and what are register used to read/write.
2. Explain about Boot loaders and exception levels.
3. what is an interrupt and how it works with schedulers?
4. what is process and threads, explain difference of them by opening a browser it is storage location.

### HR round:
Explain about your journey?
How can you come out of critical situation?
why should I hire you for this position?

# NVIDIA

### Virtual round:

1. Questions on CV in details
2. storage classes
3. what and why RAMINDEX register is important in cache dump?
4. Explain boot flow in CPU CP point of view?
5. what will happen as you press on POWER ON button?
6. write a code that should flops bits in 32 bit register from 9 to 0 and 17 to 26.

### F2F round:

1. Explain about Cache dump and it flow?
2. many question on bitwise operators like: swap, set, clear, power of 2 and 8, count set bits and flip bits.
3. question: Two process are there, both process start at same base X address and end of process1 calls the process2. Now write a code 
that should print base address and explain about the memory management between two process, it is storage location.
4. Explain and write a example of volatile keyword.
5. Multiply two numbers without multiplier.
6. Interrupt Handler by writing some examples.
