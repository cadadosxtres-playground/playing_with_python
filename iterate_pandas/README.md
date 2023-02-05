# Pandas Iteration

This code is inspared by a post called [How to Iterate Over Rows in pandas, and Why You Shouldn't](https://realpython.com/pandas-iterate-over-rows/) where is meassured the performance difference between three type of iteration methods over a Panda DataFrame below:
* For Iteration
* List Comprehension
* Pandas Vectorized Method

The performance analysis is done for two different scenarios below:
* Summing a column
* Summing by creating a intermedia column

## Python environment

Please create a virtual python3 environment and install packages defined in [requirements.txt](requirements.txt)

```bash
### in repo/iterate_pandas
python3 -m venv .venv
source .venv/bin/active
python -m pip install -r requirements.txt
```


### Caveats
* All test has been done in a MacBook Pro Mid 2012 with 16GB RAM and Ubuntu 20.04.1
* Python 3.8.10