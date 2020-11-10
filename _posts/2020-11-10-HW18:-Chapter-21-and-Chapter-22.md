---
published: true
---
### 21.4
### Explain why an object-oriented approach to software development may not be suitable for real-time systems.
Object-oriented apporoaches to software development are not suitable for real-time systems becasue these systems must meet their timing constraints and object-oriented development involves hiding and encapsulated data and accessing values through operations defined with the object. There is also "significant performance overhead" in O.O. languages becasue extra code is required to mediate access to attributes and handle calls to operations and this loss of performance makes it pretty much impossible to meet real-time deadlines.In order to use object-oriented lnguage correctly in real-time systems, you need to allow threads to be specified that will not be interrupted by the garbage collector and include asynchronous event handling and timing specifications. Real-time systems are best implemented in C.

### 22.6
### Fixed-price contracts, where the contractor bids a fixed price to complete a system development, may be used to move project risk from client to contractor. If anything goes wrong, the contractor has to pay. Suggest how the use of such contracts may increase the likelihood that product risks will arise.
