# Benchmark Results: AddWeighted

Number of images: 500

## CPU Information

- CPU: Apple M1 Pro
- Frequency: Current: 3228.00 MHz, Min: 600.00 MHz, Max: 3228.00 MHz
- Physical cores: 10
- Total cores: 10

## Package Versions

| Python                                | algocore   | opencv-python-headless   | numpy   | torchvision   |
|:--------------------------------------|:-----------|:-------------------------|:--------|:--------------|
| 3.9.20 (main, Oct  3 2024, 02:24:59)  | 0.0.20     | 4.10.0.84                | 2.0.2   | 0.19.1        |
| [Clang 14.0.6 ]                       |            |                          |         |               |

## Performance (images/second)

|             | algocore           | lut            | opencv           | numpy          | simsimd           |
|:------------|:-------------------|:---------------|:-----------------|:---------------|:------------------|
| AddWeighted | 10221.66 ± 1138.98 | 946.90 ± 72.75 | 5427.48 ± 416.56 | 916.15 ± 87.96 | 5596.14 ± 1418.57 |
