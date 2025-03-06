# cs-classic-papers

## Motivation
- For fun
- A collection of classical, impactful papers on the field of computer science
- Any PR/MR/issues are appreciated :>

## Listing

### genesis of computer
- **An automatic machine that generates mathematical facts and proofs?**:David Hilbert. "Mathematical Problems" (1900)
- **Incompletenss theorem, no automatic machine generating mathematical facts and proofs**: Kurt Gödel. "On Formally Undecidable Propositions of Principia Mathematica And Related Systems" (1930)
- **Turing machine, from an easier proof for Gödel's theorem**: Alan Turing. "On Computable Numbers, with an Application to the Entscheidungsproblem" (1936)
- **Lambda calculus**: Alonzo Church. "The Calculi of Lambda-Conversion" (1941)
- **Boolean logic**: George Boole. "An Investigation of the Laws of Thought" (1853)
- **Switch and boolean logic**: Claude Shanon. "A Symbolic Analysis of Relay And Switching Circuits" (1938)
- **von Neumann architecture**: [John Von Neumann. "First Draft of a Report on the EDVAC" (1945)](https://ieeexplore.ieee.org/abstract/document/238389)

### algorithms
- **Binary search**: Have been existing for a long time (src: https://en.wikipedia.org/wiki/Binary_search#History)
- **Quick sort**: A. R. Hoare. "Quick Sort" (1961)
- **Dynamic programming**: (TODO) Richard bellman, dynamic programming
- **SAT, the NP-complete problem found**: Sameul A. Cook. “The Complexity of Theorem-Proving Procedures” (1971)
- **Reducing many problems into 3SAT**: Richard M. Karp. "Reducibility Among Combinatorial Problems" (1972)

### languages & compilers
- **defining an ISA** (TODO)
- **syntax, abstract grammar**: Noam Chomsky. "Three models for the description of language" (1956)
- **semantics**: A. R. Hoare. "An Axiomatic Basis for Computer Programming" (1969)
- **defining a programming language**: Peter J. Landin. "The Next 700 Programming Languages" (1966)
- **FORTARN, the first high-level language**: John W. Backus et al. "The FORTRAN Automatic Coding System" (1959)
- **type system, foundation for functional languages**: Robin Milner. "A Theory of Type Polymorphism in Programming" (1977)
-  **Java: object-oriented / garbage collection** (TODO)
- **parsing**: (TODO)
- **IR & optimization**: (TODO)

### verification
- **abstract interpretation, static analysis**: Patric Cousot. "Abstract interpretation: a unified lattice model for static analysis of programs by construction or approximation of fixpoints" (1977)
- **TCB**: Ken Thompson. "Reflections on Trusting Trust" (1984)
- **machine-checked proof**: (TODO: Coq?)
- **separation logic**: John C. Raynolds. "Separation logic: a logic for shared mutable data structures" (2002)
- Atsushi Igarashi, Benjamin C. Pierce, and Philip Wadler: Featherweight Java: A Minimal Core Calculus for Java and GJ (2001)
- **CompCert, a formally verified C compiler**: Xavier Leroy. "Formal verification of a realistic compiler" (2009)

### architectures (TODO: add the name of the chip, instead of papers, due to its special case?)
- **caching**: (TODO) caching
- **instruction pipelining**: (TODO) 5-stage pipelined processor
- **superscalar**: Intel Itanium (VLIW) vs. AMD x86-64 (OoO)
  - **VLIW**: Code generation schema for modulo scheduled loops (1992)
  - **OoO**: (TODO)
- **speculation**: (TODO)
- **multithreading**: (TODO) HW-level multithreading (there was Sun microsystems something)
- **SIMD**: (TODO) SIMD, e.g., AVX-512
- **The memory wall, fundamental problem of von Neumman architecture**: [Wm. A. Wulf, and Sally A. McKee. "Hitting the memory wall: implications of the obvious" (1995)](https://dl.acm.org/doi/10.1145/216585.216588)
- **NVIDIA GPGPU, SIMT(Multithreading + SIMD) for general-purpose parallel computing**: [Peter N. Glaskowsky. "NVIDIA’s Fermi: The First Complete GPU Computing Architecture" (2009)](https://www.nvidia.com/content/pdf/fermi_white_papers/p.glaskowsky_nvidia's_fermi-the_first_complete_gpu_architecture.pdf)
- (TODO) Why systolic architecture? (1982)
- **Goolge TPU**: [Norman P. Jouppi et al. "In-datacenter performance analysis of a tensor processing unit" (2017)](https://dl.acm.org/doi/abs/10.1145/3079856.3080246)

### OS / cloud
- **UNIX**: Dennis Ritchie and Ken Thompson. "The UNIX Time-Sharing System" (1974)
- **Virtualization**: Paul Barharm, et al. "Xen and the art of virtualization" (2003)
- **Cloud computing**: Michale Armbrust, et al. "A View of Cloud Computing" (2010)
- **Containerization**: (TODO) containerization -> Docker

### DB
- **Relational DB**: Edgar Codd. “A Relational Model of Data for Large Shared Data Banks” (1970)
- **SQL**: Donald Chamberlin and Raymond Boyce. "SEQUEL: A Structured English Query Language” (1974)

### communication / network / web
- **Information theory**: Claude Shanon. "A Mathematical Theory of Communication" (1948)
- **TCP/IP**: Vinton Cerf and Robert Khan. "A Protocol for Packet Network Intercommunication" (1974)
- **The Web, WWW**: Tim Berners-Lee, Robert Cailliau, Jean-François Groff, and Bernd Pollermann. "World-Wide Web: The Information Universe" (1992)
- **PageRank, search engine, Google**: Larry Page, Sergey Brin, Rajeev Motwani, and Terry Winograd. "The PageRank Citation Ranking: Bringing Order to the Web" (1999)

### security / cryptography
- **Public-private key**: Whitfield Diffie and Martin Hellman. "New Directions in Cryptography" (1976)
- **RSA, digital signature**: A Method for Obtaining Digital Signatures and Public-Key Cryptosystems (1978)
- **Crypto-anarchy**: Timothy C. May, "The Crypto Anarchist Manifesto" (1992)
- (TODO) Craig Gentry, 2009, Fully homomorphic encryption
- (TODO) zero-trust?
- (TODO) VPN
- (TODO) DDoS

### distributed / concurrent systems
- Leslie Lamport. "Time, Clocks, and the Ordering of Events in a Distributed System" (1978)
- (TODO) Message-Passing Interface
- (TODO) Paxos
- (TODO) MapReduce: simplified data processing on large clusters (2008)
- (TODO) Bitcoin: A Peer-to-Peer Electronic Cash System (2008)
- (TODO) Lock
- (TODO) parallel algorithm: tiling?

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


## References
- [Havard CSCI E-191](https://canvas.harvard.edu/courses/34992/assignments/syllabus)
- [컴퓨터 과학이 여는 세계, 이광근](https://www.yes24.com/Product/Goods/17976737)
- https://terriblesoftware.org/2025/01/22/the-7-most-influential-papers-in-computer-science-history/
