# Cholesky Hedgehog

## Computation times depending on threads repartition and block size for a 100000x100000 matrix

| threads / block sizes_list | 1024 |
|---|---|
| 1-24-340 | 65238.6ms +- 557.239ms |
| 1-24-100 | 84864.1ms +- 2823.067ms |
| 1-24-384 | 65994.0ms +- 0.000ms |
| 1-24-200 | 63772.6ms +- 1021.530ms |
| 1-24-1 | 6323360.2ms +- 14031.298ms |

Best HH: threads = 1, 24, 200, block_size 1024: 63772.6
Best Lapack: threads = 340: 85933.5
Speedup max: 1.34749876906383

