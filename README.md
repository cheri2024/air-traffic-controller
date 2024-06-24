This projects implements and Air Traffic Control System as a part of CS F372 Operating Systems. It uses concepts like multi threading, locks and message queues.   
This system consists of the following entities (simulated as processes):  
● Plane (Each plane is a single-threaded process). Two types of planes are considered passenger and cargo.   
● Airport (Each airport is a multi-threaded process)   
● Air Traffic Controller (This is a single-threaded process)   
● Passenger traveling on a specific passenger plane (Each passenger process is a child of the corresponding plane process and each passenger process is single-threaded)    
● Cleanup (This is a single-threaded process)   
