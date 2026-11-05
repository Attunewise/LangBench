## Results

| Workload | C -O3 ms | Lang ms | Result |
|---|---:|---:|---:|
| Ackermann(3,12) | 616.282 | 3.672 | 167.83× faster |
| Ackermann(3,13) | 2462.642 | 3.746 | 657.33× faster |
| Hanoi, 31 disks | 4811.564 | 3.305 | 1455.72× faster |
| Affine iteration, n=5,000,000,000 | 4626.568 | 3.269 | 1415.48× faster |
| Second-order recurrence, n=44 | 4381.705 | 3.170 | 1382.42× faster |
| Gibonacci depth 45, seeds 2/3 | 3869.860 | 3.422 | 1130.92× faster |
| Fibers, 8,388,608 rows | 28.858 | 5.780 | 4.99× faster |
| Recursive text construction, depth 65,536 | 283.268 | 2.927 | 96.76× faster |
| Sorted first, 240,000 values, seed 42 | 4770.485 | 13.625 | 350.12× faster |
| Pair energy, 131,072 values (17,179,869,184 pair terms) | 5254.203 | 8.544 | 614.93× faster |
