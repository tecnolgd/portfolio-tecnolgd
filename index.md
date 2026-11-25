Systems & Developer Tools Engineer building high-performance C++ utilities, static analysis engines, and CLI workflows.

<div align = "center">
    <a href = "https://github.com/tecnolgd"> GitHub </a> |
    <a href = "https://tecnolgd.github.io/blog-tecnolgd"> Blog </a> |
    <a href = "mailto:tecnolgd@proton.me"> Email </a> |
    <a href = "https://github.com/tecnolgd.gpg"> GPG Key</a>
</div>

---

## Featured Projects       

- **velocache**        
    *C++17 • Hashmap • DLL(Doubly Linked List) • Deterministic O(1) Operations* 

    In-memory key-value store using a linked-list backed hash map structure. Built with explicit memory management, deterministic LRU eviction, and custom persistence layouts.  

    [Source Code](https://github.com/tecnolgd/velocache) • [Docker](https://hub.docker.com/r/tecnolgd/velocache)     

- **repoScanner**   
    *Python 3.12 • C++ Library Integration • Static Analysis • PyPI Package*

    Lightweight CLI tool for code metrics, dependency extraction, and file sorting. Uses Python standard library by default with optional C++ native acceleration (`libcvault`).

    [PyPI Package](https://pypi.org/tecnolgd/project/repoScanner/) • [Source Code](https://github.com/tecnolgd/repoScanner) • [Release Writeup](https://tecnolgd.github.io/blog-tecnolgd/posts/post-5.html)

- **TermiFlow**        
    *C++17 • Cross-Platform • CLI launcher • System Automation*

    Command-driven terminal launcher and productivity suite built to execute shortcuts, track command history, and display system metrics without leaving the shell.

    [Source Code](https://github.com/tecnolgd/TermiFlow)

---

## Open Source Contributions       

- [**OutSquareCapital/pyochain**](https://github.com/OutSquareCapital/pyochain)    *Python • Rust • Pyo3 • Functional Programming*      
    - [PR #89](https://github.com/OutSquareCapital/pyochain/pull/89) - Migrated doctests to markdown tests in stub files
    - [PR #92](https://github.com/OutSquareCapital/pyochain/pull/92) - Aligned `Range` constructor API with python `range`
    - [PR #95](https://github.com/OutSquareCapital/pyochain/pull/95) - Added `return_named_values` property to handle dscription leaks

- [**qualcomm/eld**](https://github.com/qualcomm/eld)    *Embedded Systems*     
    - [PR #1819](https://github.com/qualcomm/eld/pull/1819) - Renamed `checkUnsignedRange` to `reportUnsignedOverflow` for accurate description of the function

- [**Mher-DeLight/cpersist**](https://github.com/Mher-DeLight/cpersist)    *Data Serialization • Deserialization • File I/O*    
    - [PR #27](https://github.com/Mher-DeLight/cpersist/pull/27) - Added `std::filesystem::path` serialization support
    - [PR #37](https://github.com/Mher-DeLight/cpersist/pull/37) - Added custom save folder name support with I/P sanitization

- [**tyouhyou/imprint**](https://github.com/tyouhyou/imprint)    *C++17 • Embedded • Retained mode GUI • Cross Platform • WebAssembly*     
    - [PR #4](https://github.com/tyouhyou/imprint/pull/4) - Added `halign` and `valign` attributes to `.ui` files and builders
    - [PR #5](https://github.com/tyouhyou/imprint/pull/5) - Added `GroupBox` widget and gallery showcase

- [**cherries-works/pulse**](https://github.com/cherries-works/pulse)    *C • Linux • Monitoring Dashboard • Web Interface*
    - [PR #33](https://github.com/cherries-works/pulse/pull/33) - Added  independent cooldown parameter for alert notifications
    - [PR #45](https://github.com/cherries-works/pulse/pull/45) - Added `--current` flag to print current configuration
    - [PR #56](https://github.com/cherries-works/pulse/pull/56) - Support dynamic printing of operators in `config --current`

- [**CoreTrace/coretrace**](https://github.com/CoreTrace/coretrace)    *C++ • Analysis Orchestrator*    
    - [PR #166](https://github.com/CoreTrace/coretrace/pull/166) - Handled std::string_view safely and added missing `isMangled` and type tests
    - [PR #168](https://github.com/CoreTrace/coretrace/pull/168) - Migrated `isMangled` to `src/ctrace_tools/mangle.cpp`
    - [PR #197](https://github.com/CoreTrace/coretrace/pull/197) - Added unit tests for `ctrace::RunDirectory`

- [**wavefnd/Wave**](https://github.com/wavefnd/Wave)    *LLVM • Wave Lang • Programming Language*     
    - [PR #921](https://github.com/wavefnd/Wave/pull/921) - Used null-delimited git ls-files to prevent quote decoding errors
    - [PR #926](https://github.com/wavefnd/Wave/pull/926) - Preserved raw-string contents when detecting Rust function boundaries
    - [PR #1132](https://github.com/wavefnd/Wave/pull/1132) - Skip non-executable files in `package::which`

- [**FloofyPlasma/smelt**](https://github.com/FloofyPlasma/smelt)    *Declarative Build System • C/C++ Support*       
    - [PR #40](https://github.com/FloofyPlasma/smelt/pull/40) - Define `NDEBUG` when `debug_info` is disabled

---

## Core Libraries       

- **libcvault**         
    *C++17 • Static Analysis Library • FFI-Compatible*  

    Reusable C++ library engineered for static file metadata analysis and high-throughput directory scanning. Powers the native engine for `repoScanner`.  

    [Source Code](https://github.com/tecnolgd/libcvault)
