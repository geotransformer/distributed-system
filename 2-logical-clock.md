# Time in Distributed System
## Why Do We Need Time?
- Ordering
- Causality
- Scheduling, Fairness, Service Level Objectives (SLOs)
- Progress measurement, gabage collection
## Why Can Not Use Nodes’ Local/physical Clocks?
- Physical clocks across nodes not guaranteed to be synchronized
## Logical clocks and logical time
- Introduce virtual time measured with virtual clocks
- Generate timestamps
- Advance in some manner
- Can be used to order events
## Common Notation
- 𝒆𝟏 ⟶ 𝒆𝟐  ⇒  𝒆𝟏 happened before 𝒆𝟐 Happens
- 𝒆𝟏 -/-> 𝒆𝟐 and 𝒆𝟐 -/-> 𝒆𝟏  ⇒  𝒆𝟏 ∥ 𝒆𝟐 (Concurrent Events)
## Logical Clock
- 𝒆𝟏 ⟶ 𝒆𝟐  ⇒  𝑪(𝒆𝟏) < 𝑪(𝒆𝟐) (Logical Clock consistency)
- 𝒆𝟏 ⟶ 𝒆𝟐 ⟺ 𝑪(𝒆𝟏) < 𝑪(𝒆𝟐) (Strong clock consistency)
## Types of Logical Clock
- Scalar (Lamport’s) clocks: Time/clock is represented as a scalar.
- Vector clocks: Time/clock is represented as a vector.
- Matrix clocks: Time/clock is represented as a matrix.
## References
- Raynal and M. Singhal. Logical Time: A Way to Capture Causality in Distributed Systems
