# OpenMP

## Image Processing Speedups

### Specs
+ Intel Core i7 2720QM
+ NVIDIA GeForce GTX 560M

### Runtime measurements
| Process                                                          | Runtime       | Speedup      |
| ---------------------------------------------------------------- |--------------:|-------------:|
| Sequential without any optimization                              | 12'931.0 ms     | n/a          |
| Sequential with compiler optimizations (/Ox /Ot /GL)             | 10'748.6 ms   | 2'182.4 ms   |
| Sequential with minimal calls of getScanLine()                   | tbd      | tbd       |
| Parallelization of the optimized sequential implementation       | tbd      | tbd       |
