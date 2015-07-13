### *An investigation of the applicability of new systems languages to the domain of High Performance Computing*\*.
===

This is the main repository for my 3rd year dissertation project. In here the main report will be found, as well as sub-module links to the implementations of the CloverLeaf mini-app that are involved with the dissertation.

The languages concerned for this dissertation will be the following:

* FORTRAN/C - Reference implementations provided by the UK Mini App Consortium.
* [Rust](http://www.rust-lang.org/) - Systems language developed by Mozilla, aimed at speed and memory safety.
* [Nim](http://nim-lang.org/) (formerly Nimrod) - Systems language that focuses on simplicity, type safety and speed.
* [D](http://dlang.org/) - Systems language designed to use dynamic typing, as well as uses an optional garbage collector.

All of these languages compile down to native machine code, removing the need for a language VM like the JVM, improving performance.

Performance for the implementations will measured against the reference for both a serial (no parallelism on the machine) and accelerator implementation (using OpenCL) where OpenCL bindings are made available.

\* Project title not yet finalised
