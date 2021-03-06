# Aratar
A simple programming language inspired by Rust and Python.  This repository is
home for the aratar REPL interpeter which depends on the yeet compiler and the
dive runtime.  For default builds, yote (Yo Text Editor) is included allowing
for an easy terminal IDE experience.

## Goals
 - Rust-Like Safety - Programs never will segmentation fault, safe
   multi-threading
 - Better Keywords - Useful identifiers like `type` and `int` shall not be
   keywords
 - Fast Runtime - Faster than C using language-specific optimizations.
 - Fast Compile - Compile times should be very small because of simple compilation rules.
 - Easy To Learn - Few Keywords and Syntax Rules
 - Usable as a REPL / Terminal IDE
 - Simple Lifetime Rules - No possible compiler errors for lifetime issues
 - Full Hardware Interface Support In Standard Library (not just files and
   networking, but also graphics including GUI, audio, input, etc.)
 - Compile specifically for RISC-V, but also have machine language transpilers
 - Free On Last Use - Similar to RAII but prevents the need to create many inner
   scopes
 - Good documentation - complete and coherent, built in docs generator
 - State-of-the-art mathematical programming (combines the best of high-level
   abstractions and low-level optimizations)
 - More pattern matching than Rust - Everywhere (and using mathematical sets)
 - Bounded variables - allowing invalid input to be caught at compile-time which
   means your code will *never* crash.
 - Arithmetic only wraps or saturates if you tell it to - otherwise it extends
   the bounds of the type.
 - Type inference - and a strict type system
 - Rust-like unit-tests - Easy!
 - Rust-like generics
 - Simple bloat reducing optimizations on monomorphization
 - Only compiles the parts of modules that are used - a top down dependency tree
   traversal avoids compiling unneeded pieces of shared code (Fast compiles!).

