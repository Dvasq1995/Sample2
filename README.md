# Issue: Jupyter Notebook Fails to Load CSV File using Pandas

## Problem Description

I am working on a Jupyter Notebook where I need to read a CSV file using the Pandas library. However, I encounter errors related to the filepath or filename when I try to execute the code.

### Code Sample

Here's the relevant code snippet:

```python
import pandas as pd

df = pd.read_csv('my_file.csv')
```

### Error Message

The error message displayed is as follows:

```
FileNotFoundError: [Errno 2] No such file or directory: 'my_file.csv'
```

## Sample CSV File

For this issue, I am using a simple CSV file named `my_file.csv` with the following structure:

```
Name,Age,Occupation
Alice,29,Engineer
Bob,35,Doctor
Cathy,40,Teacher
```
