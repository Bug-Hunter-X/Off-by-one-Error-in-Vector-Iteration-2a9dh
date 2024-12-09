# Off-by-one Error in Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs when the loop condition uses `<= vec.size()` instead of `< vec.size()`. This leads to accessing an element beyond the valid range of the vector, resulting in undefined behavior.