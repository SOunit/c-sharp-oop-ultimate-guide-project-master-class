# CLR / Common Language Runtime

- execution engine for all .NET languages
- code-execution environment for all .NET languages
- .net language run only on CLR
- CRL is part of .NET framework, pre-installed to windows
- sub components
  - class loader
  - memory manager
  - garbage collector
  - JIT compiler
  - exception manager
  - thread manager
  - security manager

# execution

- class loader
  - load class if needed
- memory manager
  - allocate memory to variable and object
- garbage collector
  - release memory once not needed
- JIT compiler
  - convert MSIL / MicroSoft Intermediate Language to Machine language
- Exception manager
  - raise notifications
  - create exception logs
- thread manager
  - create thread
  - the entire program is treated as main thread
  - developer can create sub thread
- security management
  - check code if the order is secure or not
