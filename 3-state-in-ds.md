# States in Distributed System
## Global State,Snapshots,and Other Terminology
- Global State: 
  - Process state defined by most recent event
  - Channel state defined by inflight messages
- State transitions:
  - Each event changes the state of at least one of the entities, therefore changes the global state of the distributed system
