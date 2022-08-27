# Definition, history, and milestones
## What is a distributed system?
- A collection of computing units that interact by exchanging messages via an interconnection network and appear to external users as a single coherent computing facility
- “A distributed system is one in which the failure of a computer you didn't even know existed can render your own computer unusable”, Leslie Lamport
- The system gives correct answers always regardless of failures or delay of a node or the network
## Desirable properties of distributed system
- Consistent (C)
- Highly available (A)
- Tolerance to partitions (P)
- Scalable 
- Predictable Performance
- Secured
- Recoverable 
## Brewer’s CAP Theorem
-  You cannot have all three properties, i.e., Consistent (C), Highly available (A), Tolerance to partitions (P).
-  CP: If a network partition occurs (P), to guarantee consistency (C) may need to return errors/timeouts (lose A)
-  AP: If a network partition occurs (P), the system can continue providing responses (A), but some may return stale values (lose C)
## Partition is rare
Slow response == No response
Low latency == No availability
Availability vs. Consistency == Latency vs. Consistency 

## PACELC: 
- If there is a partition (P), how does the system trade off availability and consistency (A and C); else (E), when the system is running normally in the absence of partitions, how does the system trade off latency (L) and consistency (C)? 
## Models 
- Without models, we have no hope of mastering the complexity that underlies distributed systems
- Distributed systems raise new concerns and understanding these requires new models
## The 8 fallacies of distributed computing
1. The network is reliable.
2. Latency is zero.
3. Bandwidth is infinite.
4. The network is secure.
5. Topology doesn't change.
6. There is one administrator.
7. Transport cost is zero.
8. The network is homogeneous.
