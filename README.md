# Hi, I'm Omri Shalev

Software engineer focused on **systems programming**, **C/C++**, and low-level software design.

---

## Systems & C/C++

Self-contained projects — each repo has its own source, tests, dependencies, and Makefile.

### Core systems
| Project | Description |
|---------|-------------|
| [**ROCS**](https://github.com/omrishalev10/rocs) | C++20 framework: thread pool, singleton, factory, message broker, PlugNPlay (`inotify` + `dlopen`), NBD + RAM storage |
| [**watchdog**](https://github.com/omrishalev10/watchdog) | Process immortality: mutual heartbeat, signals, `fork`/`exec`, heap-based scheduler |
| [**heap_scheduler**](https://github.com/omrishalev10/heap_scheduler) | Timed task scheduler backed by a binary heap |
| [**dhcp**](https://github.com/omrishalev10/dhcp) | DHCP-style IP allocation on a binary trie |
| [**pp_network**](https://github.com/omrishalev10/pp_network) | TCP/UDP ping-pong with `select` and non-blocking I/O |
| [**fs_parsing**](https://github.com/omrishalev10/fs_parsing) | Low-level ext2 filesystem parsing |

### Memory & data structures
| Project | Description |
|---------|-------------|
| [**vsa**](https://github.com/omrishalev10/vsa) | Variable-size pool allocator with coalescing |
| [**fsa**](https://github.com/omrishalev10/fsa) | Fixed-size O(1) freelist allocator |
| [**hash_table**](https://github.com/omrishalev10/hash_table) | Chained hash table with load statistics |
| [**calculator**](https://github.com/omrishalev10/calculator) | Infix calculator — state machine + precedence stacks |

### Concurrency & algorithms
| Project | Description |
|---------|-------------|
| [**prod_con**](https://github.com/omrishalev10/prod_con) | Producer–consumer: atomics → mutex → semaphores → condition variables |
| [**knight_tour**](https://github.com/omrishalev10/knight_tour) | Knight's tour — backtracking + Warnsdorff heuristic |

### C++ design
| Project | Description |
|---------|-------------|
| [**bit_array**](https://github.com/omrishalev10/bit_array) | Template `BitSet` with `BitProxy` |
| [**simple_string**](https://github.com/omrishalev10/simple_string) | Copy-on-write string on a refcounted buffer |
| [**cpp2c**](https://github.com/omrishalev10/cpp2c) | C++ object model hand-translated to C (vtables, inheritance, lifetime) |

---

## Other projects

| Project | Description |
|---------|-------------|
| [**SlashGame**](https://github.com/omrishalev10/SlashGame) | Unreal Engine slash game |
| [**CheckmateGame**](https://github.com/omrishalev10/CheckmateGame) | Checkmate game project |
| [**MatrixExponentioal**](https://github.com/omrishalev10/MatrixExponentioal) | Matrix exponential in Python and C++ with optimized runtime |

---

## Tech stack

`C` · `C++` · Linux · pthreads · sockets · memory allocators · data structures · Unreal Engine
