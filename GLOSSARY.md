# Master engineering glossary

One-line definitions with examples, accumulated across the FDE and Python lessons.

## Programming and state

| Term | Definition and example |
|---|---|
| Computer | Machine that executes instructions and processes information; e.g. a laptop. |
| Programming | Designing and expressing instructions to solve problems using computers; e.g. calculating a bill. |
| Coding | Expressing instructions in a programming language; e.g. writing Python. |
| Program | Collection of instructions; e.g. a salary calculator. |
| Data | Information a program works with; e.g. prices and images. |
| Algorithm | Defined procedure for solving a problem; e.g. validate a PIN then check funds. |
| Computational thinking | Structuring a problem so a computer can help solve it; e.g. decompose a booking workflow. |
| Decomposition | Breaking a goal into smaller parts; e.g. authenticate, reserve, verify. |
| Atomic operation | A single unit at the chosen level of abstraction; in databases, an indivisible change. |
| Sequence | Ordered execution; e.g. create a receipt before displaying it. |
| Conditional branching | Choose a path using a condition; e.g. reject insufficient funds. |
| Dependency | Something required before a step can proceed; e.g. a receipt must exist before display. |
| Determinism | Identical complete starting conditions and instructions yield identical results; e.g. integer addition. |
| Input | Information entering a system; e.g. item prices. |
| Process | Operations applied to input; e.g. adding prices. |
| Output | Information or result produced; e.g. total price. |
| Variable | Name referring to a value; e.g. age = 25. |
| Function | Reusable unit of code that performs a task; e.g. sum(). |
| Instruction | A specific operation; e.g. print(total). |
| Data type | Category of a value; e.g. 25 is an integer. |
| State | Information describing the system at a moment; e.g. an account balance. |
| State transformation | Change in state; e.g. balance moves from ₦10,000 to ₦7,000. |
| State transition | Movement between states; e.g. pending to confirmed. |
| Pipeline | Connected processing stages; e.g. collect, clean, analyze, store. |
| State machine | Defined states and permitted transitions; e.g. requested, pending, confirmed. |
| Persistent state | State saved beyond a process lifetime; e.g. a database record. |
| Syntax | Grammar of a programming language; e.g. Python's colon after if. |
| Semantics | Meaning or behavior of an instruction; e.g. >= compares values. |
| Pseudocode | Structured language-independent algorithm description; e.g. IF valid THEN proceed. |
| Implementation | Turning a design into working software; e.g. coding the booking workflow. |
| Abstraction | Hiding complexity behind a simpler interface; e.g. a steering wheel or Python list. |

## Reliability and security

| Term | Definition and example |
|---|---|
| Invariant | Rule that must remain true at relevant points; e.g. no two confirmed bookings for one exclusive slot. |
| Validation | Check whether data meets requirements; e.g. age is a valid number. |
| Verification | Confirm correctness or an actual outcome; e.g. inspect a payment record. |
| Assertion | A check of an expected condition; e.g. assert sum(before) == sum(after). |
| Bug | Defect producing incorrect behavior; e.g. duplicate charges. |
| Debugging | Investigating and fixing defects; e.g. finding an incorrect balance update. |
| Timeout | Waiting limit reached without expected response; e.g. a gateway does not reply within 10s. |
| Idempotency | Repeating an operation has no additional intended effect beyond the first application; e.g. same payment key prevents a duplicate under the provider's contract. |
| Concurrency | Tasks progress over overlapping periods; e.g. two patients request a slot. |
| Race condition | Incorrect behavior depending on competing operations' timing; e.g. check-then-book conflict. |
| Stale state | Outdated information; e.g. a slot shown available after reservation. |
| Transaction | Coordinated unit of work; e.g. a ledger transfer. |
| Atomic database transaction | All its changes commit together or none do; e.g. debit and credit. |
| Reconciliation | Compare records to resolve differences; e.g. local payments versus provider records. |
| Authentication | Prove identity; e.g. login with MFA. |
| Authorization | Determine allowed actions; e.g. only authorized staff edit records. |
| Error handling | Define a response to failures; e.g. stop safely on invalid input. |
| Reliability | Ability to operate correctly under specified conditions; e.g. prevent duplicate bookings. |
| Availability | Extent to which a service is accessible when needed; e.g. 99.9% uptime. |

## Python and memory

| Term | Definition and example |
|---|---|
| High-level language | Hides many hardware details; e.g. Python. |
| Low-level language | Close to hardware instructions; e.g. assembly. |
| Machine code | Native instructions a CPU executes. |
| Assembly | Symbolic representation of machine instructions; e.g. ADD. |
| Source code | Human-readable programming instructions; e.g. app.py. |
| Compiler | Translates code into another representation; e.g. source to bytecode. |
| Interpreter | Software executing program instructions; e.g. CPython. |
| CPython | Standard Python implementation, largely written in C. |
| Cython | Compiler technology for Python-like code and native extensions. |
| Bytecode | Intermediate runtime instructions; e.g. CPython bytecode. |
| PVM | Python Virtual Machine, conceptual name for bytecode execution machinery. |
| Runtime | Components that support program execution; e.g. interpreter and libraries. |
| Runtime error | Error during execution; e.g. "hello" + 5. |
| Dynamic typing | Types belong to objects and names may refer to different types; e.g. x = 5 then x = "hi". |
| Static typing | Type constraints checked before execution; e.g. Java rejects incompatible assignment. |
| Strong typing | Informal term for enforcing type compatibility; e.g. Python rejects "5" + 5. |
| Integer | Whole number; e.g. 25. |
| Float | Floating-point number; e.g. 3.14. |
| String | Text value; e.g. "Ada". |
| Boolean | True or false value; e.g. True. |
| List | Ordered collection; e.g. [1, 2, 3]. |
| Type hints | Annotations of expected types; e.g. age: int. |
| Type conversion | Convert a suitable value to another type; e.g. int("25"). |
| Refactoring | Improve internal code structure without intended behavior change; e.g. extract a helper function. |
| RAM | Working memory used by running programs; e.g. storing a loaded dataset. |
| Memory allocation | Reserve memory for data; e.g. create a list. |
| Reference | Way to access an object; e.g. patients refers to a list. |
| Reference counting | Track references to an object; used in CPython memory management. |
| Garbage collection | Automatically reclaim certain unused objects; e.g. unreachable reference cycles. |
| Memory leak | Memory remains unnecessarily occupied; e.g. retaining unused images indefinitely. |
| Caching | Retain data or results for faster reuse; e.g. bytecode caches or a cached schedule. |
| Native code | Processor-executable instructions; e.g. compiled C++ numerical routines. |
| Language binding | Bridge allowing one language to call another component; e.g. Python calling compiled C. |
| Name binding | Associate a name with an object; e.g. x = 25. |

## AI and data ecosystem

| Term | Definition and example |
|---|---|
| Ecosystem | Interconnected tools and communities; e.g. Python's AI ecosystem. |
| Library | Reusable programming tools; e.g. NumPy. |
| Framework | Software structure and tools for building applications; e.g. PyTorch. |
| NumPy | Efficient numerical arrays and operations; e.g. prices * 0.9. |
| Array | Structured collection of values; e.g. a NumPy numeric array. |
| Vectorization | Express array-wide operations rather than explicit Python loops; e.g. array * 2. |
| Pandas | Tabular data manipulation library; e.g. clean sales rows. |
| DataFrame | Table of rows and columns in memory; e.g. appointment records. |
| Matplotlib | Charting library; e.g. plot visits over time. |
| Seaborn | Statistical visualization library; e.g. visualize measurement relationships. |
| scikit-learn | Classical machine-learning toolkit; e.g. classify transactions. |
| Machine learning | Learn useful patterns from data; e.g. predicting appointment no-shows. |
| Deep learning | ML using multi-layer neural networks; e.g. ultrasound segmentation. |
| Neural network | Trainable network of connected mathematical units; e.g. classify images. |
| PyTorch | Framework for developing neural networks; e.g. train an image model. |
| TensorFlow | Framework for machine learning; e.g. train and serve a model. |
| CPU | General-purpose processor; e.g. executes application instructions. |
| GPU | Processor designed for highly parallel work; e.g. accelerate suitable model calculations. |
| CUDA | NVIDIA platform for compatible GPU computing. |
| Model training | Adjust model parameters from data; e.g. learn labeled image patterns. |
| Inference | Apply a trained model; e.g. analyze a new ultrasound image. |
| Data pipeline | Ordered stages processing data; e.g. collect, clean, transform, store. |
| API | Defined interface for software communication; e.g. request appointment details. |
| Glue language | Connects other components; e.g. Python coordinating native libraries and APIs. |

## Performance and architecture

| Term | Definition and example |
|---|---|
| Execution time | Duration of an operation; e.g. a report takes 0.5s. |
| Execution speed | Rate of performing work; e.g. records processed per second. |
| Implementation speed | How quickly a system is built; e.g. prototype in two weeks. |
| Developer velocity | How effectively useful software is delivered over time; e.g. reliable weekly releases. |
| Latency | Delay for a request or operation; e.g. API response in 200ms. |
| Throughput | Work completed per unit time; e.g. 500 requests/s. |
| Bandwidth | Data-carrying capacity of a link; e.g. 100 Mbps. |
| Bottleneck | Limiting component; e.g. a slow query. |
| Profiling | Measure where code spends time or resources; e.g. identify expensive functions. |
| Benchmarking | Measure performance under defined conditions; e.g. compare repeated runs. |
| Optimization | Improve performance or resource use; e.g. speed up a query. |
| Trade-off | Gain one benefit at a cost elsewhere; e.g. implementation speed versus runtime performance. |
| Scalability | Ability to handle growing demand; e.g. expand to more concurrent users. |
| Centralization | Control concentrated under a central authority; e.g. centrally managed bank records. |
| Decentralization | Control shared across independent participants; e.g. independent network validators. |
| Distributed system | Multiple machines working together; may still be centrally controlled. |
| Server | Program or machine providing services; e.g. API backend. |
| Client | Program or device requesting services; e.g. mobile app. |
| Database | System storing and managing organized information; e.g. PostgreSQL. |
| Cloud computing | Remotely available computing resources; e.g. cloud server. |
| Deployment | Make software available in its target environment; e.g. release an API. |

## Linux, Bash and environment

| Term | Definition and example |
|---|---|
| Kernel | OS core managing processes, memory and devices; e.g. Linux. |
| Shell | Command interpreter; e.g. Bash. |
| Terminal emulator | Text interface for interacting with a shell; e.g. GNOME Terminal. |
| Bash | Bourne Again Shell, a command interpreter and scripting language. |
| CLI | Command-line interface; e.g. type ls rather than click folders. |
| Command | Instruction to a shell or program; e.g. pwd. |
| Option / flag | Modifies command behavior; e.g. ls -a. |
| Argument | Input supplied to a command; e.g. filename in cat report.txt. |
| Prompt | Text signaling readiness for input; e.g. $. |
| Process | Running instance of a program; e.g. Python executing a script. |
| REPL | Read-evaluate-print loop; e.g. Python's interactive prompt. |
| SSH | Secure protocol for operating a remote computer. |
| Automation | Execute repeated work with minimal manual intervention; e.g. scheduled reports. |
| Filesystem | Organization of files and directories. |
| Directory | Folder containing entries; e.g. data/. |
| Root | Top of the Linux filesystem, /. |
| Path | Address of a file or directory; e.g. data/train.csv. |
| Absolute path | Full path from root; e.g. /home/student/data. |
| Relative path | Path resolved from the working directory; e.g. ../data. |
| Working directory (cwd) | Current location used to resolve relative paths. |
| Parent directory | Directory one level up; represented by two dots (`..`). |
| Home directory | User's personal directory; commonly abbreviated ~. |
| Case sensitivity | Uppercase and lowercase are distinct; e.g. Core.py vs core.py. |
| Executable | File the operating system can run; e.g. /usr/bin/python3. |
| Environment variable | Named setting available to a process; e.g. HOME. |
| PATH | Ordered list of directories for external command lookup. |
| Version | Release identifier; e.g. Python 3.12.1. |
| Virtual environment | Isolated Python dependency environment; e.g. .venv. |
| Dependency | Software a program requires; e.g. NumPy. |
| Package | Distributable collection of software files; e.g. a pip-installable library. |
| pip | Python package installation tool. |
| pwd | Print working directory. |
| ls | List directory contents; -la includes hidden entries and details. |
| cd | Change working directory. |
| mkdir | Create directories; -p creates missing parents. |
| touch | Create empty file if absent or update timestamps if present. |
| Scaffolding | Create initial project files and folders. |
| Command chaining | Combine shell commands; ; continues, && requires preceding success. |
| GUI | Graphical interface with windows, buttons and menus. |
| Headless | Running without requiring a GUI. |
| Script | Saved program containing instructions; e.g. core.py. |
| stdin | Standard input channel; e.g. typed text. |
| stdout | Standard output channel; e.g. print output. |
| stderr | Diagnostic/error output channel. |
| Exit code | Numeric completion status; 0 conventionally means success. |
| Redirection | Route input/output elsewhere; e.g. > output.txt. |
| Logging | Recording events and diagnostics for later investigation. |
| Foreground process | Process occupying the terminal's foreground. |
| Background process | Process running without occupying terminal foreground; e.g. command &. |
| Process manager | Supervises processes and may restart them; e.g. systemd. |
| CI/CD | Automated integration, testing and delivery/deployment workflows. |

## Quick reference

Measure elapsed execution time: use time.perf_counter() before and after work, subtract start from end; repeat with timeit for small benchmarks.

Engineering rules: logic before code; validate inputs; verify important outcomes using authoritative records; never equate timeout with failure; protect invariants; design for concurrency and failures; measure before optimizing; choose technology based on requirements; do not confuse AI confidence with verified fact.
