# Results for Assignment 02

## Improvement Iterations

Here's my table showing the improvements I did to make the application go faster.  The **Time** column in the table represents the _wall-clock time_ for a program run.

| Version | Time | Speedup | Memory (KB) | Changes |
| :-----: | ---- | :-----: | :------: | ------- |
| [01](0.cpp) | 116.74s | &mdash; | 4904 | Static threaded version |
| [02](0.05.cpp)| 49.24s | 2.37x | 4912 | Implement getNext while loop |
| [03](0.1.cpp)| 48.74s | 1.01x | 4884 | Took out reverse operation |
| [04](1.cpp) |  46.24s | 1.07x | 4992 | Dynamic load Balancing |
