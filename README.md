# -RTOS-QNX-Suppier-Consumer
## Task 1
1. Using the semaphore mechanism, implement the program model of the "Supplier" and "Consumer" operation, ensuring that the following conditions are met:  
a. The "supplier" cannot write information and is blocked if the Buffer value exceeds a certain allowable value ("the buffer is full")  
b. Consumer is blocked if Buffer equals 0 ("buffer is empty")  
c. Simultaneous recording and simultaneous operation of streams with the Buffer variable is not allowed  
2. Fixing the values of the current time at the beginning and end of work in the "critical section" of the supplier and the Consumer, show the fulfillment of condition 1c.  
## Task 2
Implement the conditions of "Task 1" using the conditional variable mechanism for synchronization.
