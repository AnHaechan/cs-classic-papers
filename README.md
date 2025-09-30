# cs-classic-papers

## Descrption
- A collection of classical, impactful papers on the field of computer science

## Listing

### genesis of computer
- **An automatic machine that generates mathematical facts and proofs?**:David Hilbert. "Mathematical Problems" (1900)
- **Incompletenss theorem, no automatic machine generating mathematical facts and proofs**: Kurt Gödel. "On Formally Undecidable Propositions of Principia Mathematica And Related Systems" (1930)
- **Turing machine, from an easier proof for Gödel's theorem**: Alan Turing. "On Computable Numbers, with an Application to the Entscheidungsproblem" (1936)
- **Lambda calculus**: Alonzo Church. "The Calculi of Lambda-Conversion" (1941)
- **Boolean logic**: George Boole. "An Investigation of the Laws of Thought" (1853)
- **Switch and boolean logic**: Claude Shanon. "A Symbolic Analysis of Relay And Switching Circuits" (1938)

### algorithms
- **Binary search**: Have been existing for a long time (src: https://en.wikipedia.org/wiki/Binary_search#History)
- **Quick sort**: A. R. Hoare. "Quick Sort" (1961)
- **Dynamic programming**: (TODO) Richard bellman, dynamic programming
- **SAT, NP-completeness**: Sameul A. Cook. “The Complexity of Theorem-Proving Procedures” (1971)
- **Reducing problems into 3SAT**: Richard M. Karp. "Reducibility Among Combinatorial Problems" (1972)

### languages
- **syntax, abstract grammar**: Noam Chomsky. "Three models for the description of language" (1956)
- **semantics**: A. R. Hoare. "An Axiomatic Basis for Computer Programming" (1969)
- **defining a programming language**: Peter J. Landin. "The Next 700 Programming Languages" (1966)
- **FORTARN, the first high-level language**: John W. Backus et al. "The FORTRAN Automatic Coding System" (1959)
- **type systems, foundation for functional languages**: Robin Milner. "A Theory of Type Polymorphism in Programming" (1977)

### compilers
- (TODO) **parsing**:
- (TODO) **static single-assignment form**
- **LLVM IR**: Chris Lattner et al. "LLVM: A Compilation Framework for Lifelong Program Analysis & Transformation" (2003)
- (TODO) **garbage collection**:

### verification
- **abstract interpretation**: Patric Cousot. "Abstract interpretation: a unified lattice model for static analysis of programs by construction or approximation of fixpoints" (1977)
- **TCB**: Ken Thompson. "Reflections on Trusting Trust" (1984)
- **machine-checked proof**: (TODO: Coq?)
- **separation logic**: John C. Raynolds. "Separation logic: a logic for shared mutable data structures" (2002)
- **CompCert**: Xavier Leroy. "Formal verification of a realistic compiler" (2009)

### architectures
- **caching**: (TODO) caching
- **instruction pipelining**: (TODO) 5-stage pipelined processor
- **superscalar**: Intel Itanium (VLIW) vs. AMD x86-64 (OoO)
  - **VLIW**: Code generation schema for modulo scheduled loops (1992)
  - **OoO**: (TODO)
- **speculation**: (TODO)
- **multithreading**: (TODO) HW-level multithreading (there was Sun microsystems something)
- **The memory wall**: [Wm. A. Wulf, and Sally A. McKee. "Hitting the memory wall: implications of the obvious" (1995)](https://dl.acm.org/doi/10.1145/216585.216588)
- **SIMD**: (TODO) SIMD, e.g., AVX-512
- **NVIDIA GPGPU, SIMT**: [Peter N. Glaskowsky. "NVIDIA’s Fermi: The First Complete GPU Computing Architecture" (2009)](https://www.nvidia.com/content/pdf/fermi_white_papers/p.glaskowsky_nvidia's_fermi-the_first_complete_gpu_architecture.pdf)
- **Systolic array**:  Kung, Hsiang-Tsung. "Why systolic architecture?" (1982)
- **Goolge TPU**: [Norman P. Jouppi et al. "In-datacenter performance analysis of a tensor processing unit" (2017)](https://dl.acm.org/doi/abs/10.1145/3079856.3080246)
- **FPGA**: (TODO)

### operating systems
- **UNIX**: Dennis Ritchie and Ken Thompson. "The UNIX Time-Sharing System" (1974)
- **Virtualization**: Paul Barharm, et al. "Xen and the art of virtualization" (2003)
- **Cloud computing**: Michale Armbrust, et al. "A View of Cloud Computing" (2010)
- **Containerization**: (TODO) containerization -> Docker

### data bases
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

### distributed systems
- Leslie Lamport. "Time, Clocks, and the Ordering of Events in a Distributed System" (1978)
- (TODO) Message-Passing Interface
- (TODO) Paxos
- (TODO) MapReduce: simplified data processing on large clusters (2008)
- (TODO) Bitcoin: A Peer-to-Peer Electronic Cash System (2008)

### machine learning
- **Turing's Test**: Alan Tuirng. "Computing Machinery and Intelligence" (1950)
- **Perceptron**: Frank Rosenblatt. "The perceptron: a probabilistic model for information storage and organization in the brain." (1958)
- **Evolutionary Algorithm**: John H. Holland. "Adaptation in Natural and Artificial Systems" (1975)
- **PAC Learning**: Leslie Valiant. "A Theory of the Learnable" (1984)
- **Backpropagation**: David E. Rumelhart, Geoffrey E. Hinton, and Ronald J. Williams. "Backpropagation: Learning representations by back-propagating errors" (1986)
- **Support Vector Machine**: Vladimir Vapnik. "The Nature of Statistical Learning Theory" (1995)
- **Universal Approximation Theorem**: G. Cybenko. "Approximation by Superpositions of a Sigmoidal Function" (1989)
- **LeNet, Convolutional NN**: Yann LeCun et al. "Gradient-Based Learning Applied to Document Recognition" (1998)
- **AlexNet, GPU for DNN Training**: Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton. "ImageNet Classification with Deep Convolutional Neural Networks" (2012)
- **Attention, Transformers**: Ashish Vaswani et al. "Attention is All You Need" (2017)
- **GPT-3, Large Language Models**: Tom Brown et al. "Language models are few-shot learners" (2020)
- **The Scaling Law**: Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch et al. "Training Compute-Optimal Large Language Models" (2022)

### systems (languages & compilers & runtimes) for AI
- (TODO) CUDA
- (TODO) Kernel fusion: DNNFusion?
- (TODO) Tiling & layout: CUTLASS
- (TODO) Tile-level abstraciton: Triton (2019)
- (TODO) ML framework: Tensorflow (2016)
- (TODO) Compute-Schedule separation: Halide (2013), TVM (2017)
- (TODO) Graph capture: PyTorch 2
- (TODO) Tensor parallelism: Megatron-LM
- (TODO) Kernel optimization for attention: FlashAttention 1-3
- (TODO) KV paging: PagedAttention
- (TODO) Iterative batching: ORCA

### graphics / vision
- (TODO) ray tracing?

### software engineering
- **No silver bullet**: Fred Brooks. "No Silver Bullet—Essence and Accident in Software Engineering" (1986)
- (TODO) version control (Git)
- (TODO) clean code?
- (TODO) TDD
- (TODO) Fuzzing <- the fuzzing book?

## References
- [Havard CSCI E-191](https://canvas.harvard.edu/courses/34992/assignments/syllabus)
- [컴퓨터 과학이 여는 세계, 이광근](https://www.yes24.com/Product/Goods/17976737)
- https://terriblesoftware.org/2025/01/22/the-7-most-influential-papers-in-computer-science-history/
- [Why Machines Learn: The Elegant Math Behind Modern AI, Anil Ananthaswamy](https://www.amazon.com/Why-Machines-Learn-Elegant-Behind/dp/0593185749)

-
