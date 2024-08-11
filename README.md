# cl-mumps-yottadb

Common Lisp interop with MUMPS as supported by GT.M/YottaDB. Allows for calling M routines in
idiomatic Lisp, and also to compile Lisp to M for maximum efficiency. It so happens that GT.M
and YottaDB's M routines are compiled to native code, so it can be advantageous for performance
reasons to use M in performance-critical applications.
