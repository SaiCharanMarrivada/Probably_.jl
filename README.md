# Probably.jl Documentation
_probabilistic data structures in Julia_

Probably.jl provides an implementation of common probabilistic data structures that are:
- Written in pure Julia
- Both fast and memory-efficient
- Good for default or casual use cases, easy to use in other projects
- Manipulated via functions with names from Julia's Base library

This package does __not__ attempt to:
- Provide a wide array of of functionality
- Provide structures 100% optimized for different use cases
- Gloss over the limitation of the data structures. Instead, you are expected to understand in broad strokes how the data structures work before you use them.

## Package features
Probably.jl currently includes the following data structures:
 - Bloom filter
 - Cuckoo filter
 - Count-min sketch
 - HyperLogLog
