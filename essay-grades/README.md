# essay grades
A computer-generated toy dataset of essay scores for 50 students from 5 different graders.

## Preview

| grader_id | student_id | score |
|----------:|-----------:|------:|
|         1 |       6648 | 35.45 |
|         1 |      29337 |  5.45 |
|         1 |      38658 |  8.86 |
|         1 |      44058 |  4.03 |
|         1 |      54112 | 87.54 |
|         1 |      70645 | 82.98 |
|       ... |        ... |   ... |
|         5 |     890187 | 98.70 |
|         5 |     915496 | 40.68 |
|         5 |     946355 | 67.44 |
|         5 |     949135 | 87.37 |
|         5 |     951898 | 23.33 |
|         5 |     956616 | 66.87 |

## How to load the data

### Python Pandas

```python
import pandas as pd
grades = pd.read_csv("https://raw.githubusercontent.com/practiceprobs/datasets/main/essay-grades/grades.csv")
```

### R data.table

```r
library(data.table)
grades <- fread("https://raw.githubusercontent.com/practiceprobs/datasets/main/essay-grades/grades.csv")
```