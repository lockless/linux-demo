# linux-demo
Linux系统中的各种机制的demo程序, 尽量通过代码来理解操作系统
# TO DO LIST
  * shared memory
  * pipeline
  * fifo
  * sem
  * message queue
  * malloc & free (jemalloc/tcmalloc/nedmalloc/ptmalloc)  --- write this on blog
  
  * Explain how shared memory works? a good candidate will konw details like why pointers aresorted as offsets and how to protect memory regions using semaphores. They should also know some of the common applications, e.g. in implementing databases.
   * What happens on a system call? an goog answer will include a description of processor interrupt and how the hardware handles them, scheduling decision, marshaling parameters, etc()
   * How do you reverse the bit in an int(a good solution to this problem will take a fewer operations than the number of bits being flipped)
   * Where can data be sort(stack, heap, data segment, embedded in an opcode, etc)
   
   
   
   
   
   * malloc and free in c
        * 1. how to use it
        * 2. what's the process
        * 3. where the malloc from
        * 4. what's the proble if we do not free the memory ? what occur?
        * 5. how we check memory 
        
   * dma / uio-dma
   
   * uio
   
   * red-black tree
