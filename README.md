# CPU Sceduling System using java 
"Created  Unified CPU Sceduling System For Different System Simulation."
# Discription:
This Java-based project brings together a bunch of real-world scheduling systems into one unified simulation—think hospitals, restaurants, call centers, ride-sharing apps, sports tournaments, and cloud job schedulers. Each module works like its real-life counterpart, using classic CPU scheduling algorithms like FCFS, SJF, Round Robin, and Priority to manage queues and tasks efficiently. The whole system runs through a simple, interactive command-line interface, and everything is built using custom data structures to really mimic how things work under the hood. The goal is to show how smart scheduling can solve all kinds of problems, all in one clean, modular Java framework.

# Data Structures Used:
1.Queue (FIFO):
Used in several modules such as the Hospital Queue System, Restaurant Order System, Call Center System, and Ride Sharing System. It's ideal for handling processes in the order they arrive, ensuring fairness and real-time responsiveness.

2.PriorityQueue:
Applied in systems where tasks or entities must be served based on priority rather than arrival time. For instance, in the Hospital Queue System, patients with higher severity are prioritized. In the Cloud Job Scheduler, it's used to manage jobs based on custom priority levels.

3.Stack (LIFO):
Used in the Restaurant Order System to simulate plating, where the last prepared order is placed on top and served first.

4.HashMap / Map:
Heavily used throughout the project to map categories to queues or collections. For example, mapping areas to drivers in the Ride Sharing System or skills to agents in the Call Center System.

5.Set (HashSet):
Utilized to track ongoing or active sessions such as current rides or active call routes. It ensures no duplication or conflicts in scheduling.

6.LinkedList:
Used as the underlying structure for queues due to its efficient insertions and deletions, especially when handling dynamic scheduling tasks.

7.Custom Classes and Data Models:
Custom classes like Job, Patient, Order, Driver, and Agent are integral to the project. These classes often include fields for attributes like name, status, priority, and availability, and they support the business logic tied to each scheduling scenario.



