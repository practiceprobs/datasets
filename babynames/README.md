# babynames
US baby names provided by the SSA. Compiled from the [babynames R package].

## Preview

| year | sex | name      |    n |      prop |
|-----:|:----|:----------|-----:|----------:|
| 1880 | F   | Mary      | 7065 | 0.0723836 |
| 1880 | F   | Anna      | 2604 | 0.0266790 |
| 1880 | F   | Emma      | 2003 | 0.0205215 |
| 1880 | F   | Elizabeth | 1939 | 0.0198658 |
| 1880 | F   | Minnie    | 1746 | 0.0178884 |
|  ... | ... | ...       |  ... |       ... |
| 2017 | M   | Zykai     |    5 | 0.0000026 |
| 2017 | M   | Zykeem    |    5 | 0.0000026 |
| 2017 | M   | Zylin     |    5 | 0.0000026 |
| 2017 | M   | Zylis     |    5 | 0.0000026 |
| 2017 | M   | Zyrie     |    5 | 0.0000026 |

## How to load the data

### Python Pandas

```python
import pandas as pd
names = pd.read_csv("https://raw.githubusercontent.com/practiceprobs/datasets/main/babynames/babynames.csv")
```

### R data.table

```r
library(data.table)
names <- fread("https://raw.githubusercontent.com/practiceprobs/datasets/main/babynames/babynames.csv")
```

[babynames R package]: https://cran.r-project.org/web/packages/babynames/index.html