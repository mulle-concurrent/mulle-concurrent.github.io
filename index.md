# mulle-concurrent

The mulle-concurrent library collection is written for C11. 

*mulle-concurrent* provides a few wait-free/lock-free 
datastructures. The underlying platform thread library is abstracted 
using *mulle-thread*. The problem of thread-safe memory reclamation is handled
by *mulle-aba*.


Library                                                             | Description
--------------------------------------------------------------------|----------------------
[mulle-thread](//github.com/mulle-concurrent/mulle-thread)          | Cross-platform thread/mutex/tss/atomic operations 
[mulle-aba](//github.com/mulle-concurrent/mulle-aba)                | A lock-free, cross-platform solution to the ABA problem
[mulle-concurrent](//github.com/mulle-concurrent/mulle-concurrent)  | A lock- and wait-free hashtable (and an array too)

*mulle-concurrent* is based on [mulle-c](//github.com/mulle-c). 

The [mulle-objc](https://mulle-objc.github.io) runtime is based on *mulle-concurrent*.
