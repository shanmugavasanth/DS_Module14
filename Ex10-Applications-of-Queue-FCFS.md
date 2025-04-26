# Ex10 Applications of Queue – FCFS
## DATE:10/03/2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. Start with process, burst time, and waiting time arrays. 
2. Loop through each process from i = 0 to n-1. 
3. Compute tat[i] = burst_time[i] + wait_time[i]. 
4. End the algorithm.

## Program:
```

Program to find and display the priority of the operator in the given Postfix expression

Developed by: Shanmuga Vasanth M

RegisterNumber:  212223040191

```
```
 
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) { 
   // calculating turnaround time by adding 
   // burst_time[i] + wait_time[i] 
   int i; 
   for ( i = 0; i < n ; i++) 
   tat[i] = burst_time[i] + wait_time[i]; 
   return 0; 
} 
```

## Output:


![437411135-0215026b-f47a-4fa1-8158-de7979020451](https://github.com/user-attachments/assets/453015ee-8e10-4475-b4fc-96135b130fcc)


## Result:

Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
