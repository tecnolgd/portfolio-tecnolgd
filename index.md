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
*Python 3.12 • C++ Engine Integration • Static Analysis • PyPI Package*

Lightweight CLI tool for code metrics, dependency extraction, and file sorting. Uses Python standard library by default with optional C++ native acceleration (`libcvault`).

[PyPI Package](https://pypi.org/tecnolgd/project/repoScanner/) • [Source Code](https://github.com/tecnolgd/repoScanner) • [Release Writeup](https://tecnolgd.github.io/blog-tecnolgd/posts/post-5.html)

### TermiFlow
*C++17 • Cross-Platform CLI launcher • System Automation*  
Command-driven terminal launcher and productivity suite built to execute shortcuts, track command history, and display system metrics without leaving the shell.

[Source Code](https://github.com/tecnolgd/TermiFlow)

---

## Core Libraries

### libcvault
*C++17 • Static Analysis Library*  
Reusable C++ library engineered for static file metadata analysis and high-throughput directory scanning. Powers the native engine for `repoScanner`.  

[Source Code](https://github.com/tecnolgd/libcvault)
