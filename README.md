# shared-memory-semaphore
A C program demonstrating inter-process communication and synchronization. Two child processes write to different parts of a shared memory segment, synchronized with a semaphore. The parent process waits for both children to finish, then reads and prints the messages. Show use of fork, shared memory(shm_open, mmap) and semaphores.
