# Optimized Round Robin Scheduling algorithm using dynamic time quantum
Round robin Scheduling algorithm optimized by using dynamic time quantum. Implemented in C++.


	Round Robin scheduling algorithm is the widely used scheduling algorithm in multitasking and real time environment. It is the most popular algorithm due to its fairness and starvation free nature towards the processes, which is achieved by using the time quantum.

	Each scheduling algorithm has its own advantages and disadvantages. Similarly classical RR has a drawback which increases average waiting time, average turnaround time and minimizes the throughput, known as Context switch. The processes in RR are assigned with a time quantum which is static by nature.

	Dynamic time quantum refers to changing time quantum based on the burst times of processes present in ready queue.


IMPROVED METHOD

	In our proposed algorithm, we are arranging the processes in ascending order according to their burst time present in the ready queue.
	For finding an optimal time quantum,  median method is followed. The median can be calculated using the following formulae.
   
    MEDIAN (M)= Y(n+2)/2       if n is odd
                1/2(Y n/2  + Y (1+n)/2)   if n is even
                
                where n- no. of processes.
                      Y- The number in the middle when in ascending order.
                
                
    Optimal time quantum (oqt)= (Highest Burst Time+Median)/2
    
    
    

