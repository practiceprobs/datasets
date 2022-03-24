# mnist
The famous [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database)!

[_Source_][source]

## Preview

|       | label | 1x1 | 1x2 | 1x3 | 1x4 | 28x23 | 28x24 | 28x25 | 28x26 | 28x27 | 28x28 |
|:------|------:|----:|----:|----:|----:|------:|------:|------:|------:|------:|------:|
| 1     |     7 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 2     |     2 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 3     |     1 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 4     |     0 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 5     |     4 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| ...   |   ... | ... | ... | ... | ... |   ... |   ... |   ... |   ... |   ... |   ... |
| 9996  |     2 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 9997  |     3 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 9998  |     4 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 9999  |     5 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |
| 10000 |     6 |   0 |   0 |   0 |   0 |     0 |     0 |     0 |     0 |     0 |     0 |

## How to load the data

### Python Pandas

```python
import pandas as pd
mnist = pd.read_csv("https://raw.githubusercontent.com/practiceprobs/datasets/main/mnist/mnist.csv")
```

### R data.table

```r
library(data.table)
mnist = fread("https://raw.githubusercontent.com/practiceprobs/datasets/main/mnist/mnist.csv")
```

[source]: https://www.kaggle.com/datasets/oddrationale/mnist-in-csv