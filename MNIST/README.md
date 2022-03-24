# mnist
The famous [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database)!

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
