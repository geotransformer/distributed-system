# Time in Distributed System
## Why Do We Need Time?
- Ordering
- Causality
- Scheduling, Fairness, Service Level Objectives (SLOs)
- Progress measurement, gabage collection
## Why Can Not Use Nodesβ Local/physical Clocks?
- Physical clocks across nodes not guaranteed to be synchronized
## Logical clocks and logical time
- Introduce virtual time measured with virtual clocks
- Generate timestamps
- Advance in some manner
- Can be used to order events
## Common Notation
- ππ βΆ ππ  β  ππ happened before ππ Happens
- ππ -/-> ππ and ππ -/-> ππ  β  ππ β₯ ππ (Concurrent Events)
## Logical Clock
- ππ βΆ ππ  β  πͺ(ππ) < πͺ(ππ) (Logical Clock consistency)
- ππ βΆ ππ βΊ πͺ(ππ) < πͺ(ππ) (Strong clock consistency)
## Types of Logical Clock
- Scalar (Lamportβs) clocks: Time/clock is represented as a scalar.
- Vector clocks: Time/clock is represented as a vector.
- Matrix clocks: Time/clock is represented as a matrix.
## References
- Raynal and M. Singhal. Logical Time: A Way to Capture Causality in Distributed Systems
