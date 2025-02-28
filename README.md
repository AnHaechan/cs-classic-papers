# cs-classic-papers

## Motivation
- For fun

## Listing
- Any PR/MR/issues are appreciated :>

### genesis of computer
- David Hilbert. "Mathematical Problems" (1900)
- **Incompletenss theorem, no automatic machine generating mathematical facts and proofs**: Kurt Gödel. "On Formally Undecidable Propositions of Principia Mathematica And Related Systems" (1930)
- **Turing machine, easier proof for Gödel's theorem**: Alan Turing. "On Computable Numbers, with an Application to the Entscheidungsproblem" (1936)
- **Lambda calculus**: Alonzo Church. "The Calculi of Lambda-Conversion" (1941)
- **Boolean logic**: George Boole. "An Investigation of the Laws of Thought" (1853)
- **Circuit and boolean logic**: Claude Shanon. "A Symbolic Analysis of Relay And Switching Circuits" (1938)
- **More efficient version of Turing machine**: Burks, Arthur W., Herman H. Goldstine, and John Von Neumann. "Preliminary Discussion of the Logical Design of an Electronic Computing Instrument" (1941)

### algorithms
- (TODO) binary search
- **Quick sort**: A. R. Hoare. "Quick Sort" (1961)
- (TODO) Richard bellman, dynamic programming
- (TODO) integer linear programming
- **SAT, the NP-complete problem found**: Sameul A. Cook. “The Complexity of Theorem-Proving Procedures” (1971)
- **Reducing many problems into 3SAT**: Richard M. Karp. "Reducibility Among Combinatorial Problems" (1972)

### languages
- **FORTARN, the first high-level language**: John W. Backus et al. "The FORTRAN Automatic Coding System" (1959)
- (TODO) C
- (TODO) ML
- (TODO) Java and JVM
- (TODO) Javascript
- (TODO) Python
- (TODO) "CUDA: SCALABLE PARALLEL PROGRAMMING FOR HIGH-PERFORMANCE SCIENTIFIC COMPUTING" (2008)
- (TODO) Rust

### formalism / verification
- **syntax**: Noam Chomsky. "Three models for the description of language" (1956)
- **semantics**: A. R. Hoare. "An Axiomatic Basis for Computer Programming" (1969)
- **defining a programming language**: Peter J. Landin. "The Next 700 Programming Languages" (1966)
- **abstract interpretation, static analysis**: Patric Cousot. "Abstract interpretation: a unified lattice model for static analysis of programs by construction or approximation of fixpoints" (1977)
- **type theory**: Robin Milner. "A Theory of Type Polymorphism in Programming" (1977) 
- **separation logic**: John C. Raynolds. "Separation logic: a logic for shared mutable data structures" (2002)
- **CompCert, a formally verified C compiler**: Xavier Leroy. "Formal verification of a realistic compiler" (2009)

### architectures
- (TODO) caching
- (TODO) pipelining
  - instruction-level: (TODO) 5-stage pipelined processor
  - superscalar: Intel Itanium (VLIW) vs. AMD x86-64 (OoO)
    - VLIW: Code generation schema for modulo scheduled loops (1992)
    - OoO: (TODO)
  - thread-level: (TODO) HW-level multithreading (there was Sun microsystems something)
- (TODO) SIMD, e.g., AVX-512
- (TODO) Hitting the memory wall: implications of the obvious (1995)
- (TODO) Multithreading + SIMD: SIMT + high-bandwidth memory (GDDR/HBM) -> NVIDIA GPUs
- (TODO) Why systolic architecture? (1982)
- (TODO) TPU: In-datacenter performance analysis of a tensor processing unit (2017)

### OS / cloud
- **UNIX**: Dennis Ritchie and Ken Thompson. "The UNIX Time-Sharing System" (1974)
- **Virtualization**: Paul Barharm, et al. "Xen and the art of virtualization" (2003)
- **Cloud computing**: Michale Armbrust, et al. "A View of Cloud Computing" (2010)
- **Containerization**: (TODO) containerization -> Docker

### DB
- **Relational DB**: Edgar Codd. “A Relational Model of Data for Large Shared Data Banks” (1970)
- **SQL**: Donald Chamberlin and Raymond Boyce. "SEQUEL: A Structured English Query Language” (1974)

### communication / network / internet
- Claude Shanon. "A Mathematical Theory of Communication" (1948)
- Vinton Cerf and Robert Khan. "A Protocol for Packet Network Intercommunication" (1974)
- Tim Berners-Lee, Robert Cailliau, Jean-François Groff, and Bernd Pollermann. "World-Wide Web: The Information Universe" (1992)
- Larry Page, Sergey Brin, Rajeev Motwani, and Terry Winograd. "The PageRank Citation Ranking: Bringing Order to the Web" (1999)

### security / cryptography
- (TODO) Manuel Blum: use NP problems for security
- Whitfield Diffie and Martin Hellman. "New Directions in Cryptography" (1976)
- (TODO) A Method for Obtaining Digital Signatures and Public-Key Cryptosystems (1978)
- Lawrence Carter and Mark Wegman. "Universal Classes of Hash Functions" (1979)
- Ken Thompson. "Reflections on Trusting Trust" (1984)
- (TODO) Craig Gentry, 2009, Fully homomorphic encryption
- (TODO) zero-trust
- (TODO) VPN
- (TODO) DDoS

### ML / AI
- **AI, Turing's Test**: Alan Tuirng. "Computing Machinery and Intelligence" (1950)
- **Perceptron**: Frank Rosenblatt. "The perceptron: a probabilistic model for information storage and organization in the brain." (1958)
- **Evolutionary/Genetic Algorithm**: John H. Holland. "Adaptation in Natural and Artificial Systems" (1975)
- **Backpropagation**: David E. Rumelhart, Geoffrey E. Hinton, and Ronald J. Williams. "Backpropagation: Learning representations by back-propagating errors" (1986)
- **PAC Learning**: Leslie Valiant. "A Theory of the Learnable" (1984)
- **VC Dimesion, Support Vector Machine**: Vladimir Vapnik. "The Nature of Statistical Learning Theory" (1995)
- **AlexNet, GPU for CNN Training**: Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton. "ImageNet Classification with Deep Convolutional Neural Networks" (2012)
- **Attention, Transformers**: Ashish Vaswani et al. "Attention is All You Need" (2017)
- **GPT-3, Few-shot Learning**: Tom Brown et al. "Language models are few-shot learners" (2020)

### AI systems
- (TODO) Tensorflow (2016)
- (TODO) Adams optimizer?
- (TODO) TVM (2017)
- (TODO) PyTorch 2
- (TODO) Megatron-LM
- (TODO) FlashAttention
- (TODO) PagedAttention
- (TODO) Clockwork
- (TODO) ORCA

### graphics / vision
- (TODO) ray tracing?

### software engineering
- **No silver bullet**: Fred Brooks. "No Silver Bullet—Essence and Accident in Software Engineering" (1986)
- (TODO) version magenemnt (Git)
- (TODO) clean code?
- (TODO) TDD
- (TODO) Fuzzing <- the fuzzing book?

### distributed / parallel / concurrent systems
- Leslie Lamport. "Time, Clocks, and the Ordering of Events in a Distributed System" (1978)
- (TODO) Message-Passing Interface
- (TODO) Paxos
- (TODO) MapReduce: simplified data processing on large clusters (2008)
- (TODO) Bitcoin: A Peer-to-Peer Electronic Cash System (2008)
- (TODO) Lock
- (TODO) parallel algorithm: tiling?

## References
- [Havard CSCI E-191](https://canvas.harvard.edu/courses/34992/assignments/syllabus)
- [컴퓨터 과학이 여는 세계, 이광근](https://www.yes24.com/Product/Goods/17976737)
- https://terriblesoftware.org/2025/01/22/the-7-most-influential-papers-in-computer-science-history/