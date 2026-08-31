# tecnolgd

Systems & Developer Tools Engineer building high-performance C++ utilities, static analysis engines, and CLI workflows.

[GitHub](https://github.com/tecnolgd) • [Blog](https://tecnolgd.github.io/blog-tecnolgd/) • [Email](mailto:tecnolgd@proton.me)

---

## Featured Projects

### velocache
*C++17 • Hashmap / DLL • Deterministic $O(1)$ Operations* 

In-memory key-value store using a linked-list backed hash map structure. Built with explicit memory management, deterministic LRU eviction, and custom persistence layouts.  

[Source Code](https://github.com/tecnolgd/velocache) • [Docker](https://hub.docker.com/r/tecnolgd/velocache)

### repoScanner
*Python 3.12 • C++ Engine Integration • AST Analysis • PyPI Package*

High-performance repository parser designed to extract abstract syntax trees and parse code dependencies over large codebases. Wraps a native C++ engine (`libcvault`) into a single `pip install` workflow.

[PyPI Package](https://pypi.org/tecnolgd/project/repoScanner/) • [Source Code](https://github.com/tecnolgd/repoScanner) • [Release Writeup](https://tecnolgd.github.io/blog-tecnolgd/posts/post-5.html)

### TermiFlow
*C++17 • Asynchronous Event Dispatcher • POSIX CLI*  
Keyboard-centric CLI command runner built for high-speed terminal productivity. Features modular plugin hooks and low-latency process execution.  

[Source Code](https://github.com/tecnolgd/TermiFlow)

---

## Core Libraries

### libcvault
*C++17 • Static Analysis Library*  
Reusable C++ library engineered for static file metadata analysis and high-throughput directory scanning. Powers the native backend engine for `repoScanner`.  

[Source Code](https://github.com/tecnolgd/libcvault)
