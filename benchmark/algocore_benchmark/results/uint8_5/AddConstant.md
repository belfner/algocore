# Benchmark Results: AddConstant

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

|             | algocore         | lut              | opencv           | numpy         | simsimd        |
|:------------|:-----------------|:-----------------|:-----------------|:--------------|:---------------|
| AddConstant | 4457.28 ± 468.43 | 2404.63 ± 277.90 | 2477.39 ± 574.07 | 278.56 ± 9.71 | 468.72 ± 66.92 |
