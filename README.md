# My house of horrors

- This is a project designed to inherently go against what each language was designed to do, don't waste your time and do this as well

### 1. **Python > Raw x86 Assembly Transpiler**
- Write a transpiler that takes a subset of Python code and outputs raw x86 assembly.
- No `Cython`, `Nuitka`, or existing compilers — parse, tokenize, and emit instructions yourself.
- **Skills:** Bytecode analysis (`dis`), compiler basics, CPU instructions.

### 2. **C++-Style Static Typing in Python**
- Implement a type-checking system in Python that enforces type safety *before* runtime.
- Use metaclasses, AST transforms, and decorators.
- **Skills:** AST parsing, metaprogramming, type theory.

### 3. **Manual Garbage Collection**
- Disable Python’s garbage collector (`gc.disable()`).
- Implement a custom reference-tracking system that allocates and frees objects manually.
- **Skills:** Object model internals, memory lifecycle management.

### 4. **Python Interpreter in Pure C++ Templates**
- Simulate a basic Python runtime entirely in template metaprogramming.
- No loops — only recursion and compile-time logic.
- **Skills:** Template metaprogramming, Turing completeness at compile-time.

### 5. **Garbage-Collected C++**
- Implement a tracing garbage collector for C++ objects without smart pointers.
- **Skills:** Memory management, heap inspection, pointer tracking.

### 6. **Pure Functional, Immutable C++**
- Write a project in C++ where *all* data is immutable and side effects are forbidden.
- **Skills:** Value semantics, functional patterns, persistence data structures.

### 7. **Python Objects in C++ Without Python Runtime**
- Reverse-engineer Python’s object model.
- Serialize Python objects and manipulate them from C++ without `Python.h`.
- **Skills:** Data layout reverse engineering, binary parsing.

### 8. **C++ Runtime Hot-Patching from Python**
- Write a Python script that injects compiled C++ code into a running C++ process.
- **Skills:** Shared memory, DLL/SO injection, symbol resolution.

### 9. **Python Program Compiled to C++ Constexpr**
- Store Python source in `constexpr` strings in C++.
- Parse and execute it entirely at compile time.
- **Skills:** Compile-time parsing, constexpr metaprogramming.

### 10. **C++ Templates That Generate Python Code**
- Use C++ template logic to emit Python source files as part of the build.
- **Skills:** Code generation, build systems, hybrid pipelines.

## Recommended Tooling & Resources
- **Python:** `ast`, `dis`, `gc`, `ctypes`
- **C++:** Template metaprogramming, `constexpr`, `std::variant`, low-level memory functions.
- **Cross:** LLVM, Capstone/Keystone, FFI (CFFI, SWIG), Make/CMake.




---

