# Miscellaneous Notes

### November 12th 7:12PM (3rd BP)

- Vectorization is the process of taking regular scalar code, say for example an array summation loop, and converting it into SIMD code using vector data types and vector data functions corresponding to the architecture
- `restrict` keyword in C tells the compiler that the memory for a certain object is not aliased, allowing the compiler to make according optimizations
- A vector dependency is when a loop iteration depends on or conflicts with another iteration computation, preventing parallelism
- `alignas` specifier on static arrays and the std::assume_aligned function can be used to mark pointers as aligned