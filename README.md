# OpenMP

## Image Processing Speedups

### Specs
+ Intel Core i7 2720QM
+ 8 GByte RAM
+ Windows 10 Pro, 64-Bit

### Runtime measurements
| Process                                                          | Runtime       | Speedup      |
| ---------------------------------------------------------------- |--------------:|-------------:|
| Sequential without any optimization                              | 12'931.0 ms   | n/a          |
| Sequential with compiler optimizations (/Ox /Ot /GL)             | 10'518.8 ms   | 1.23 (-2'412.2 ms)   |
| Sequential with minimal calls of getScanLine()                   | 859.01 ms      | 12.25 (-9'659.79 ms) |
| Parallelization of the optimized sequential implementation       | tbd      | tbd       |
Processes ran in x64 release configuration.
