# Example of a Machine Learning and Python Project

> # Note
>
> Pandas library is a great library

> ## Remember
>
> The official documentation for:
>
> * Pandas https://pandas.pydata.org/docs/index.html

> ### Note
>
> Make sure to import the library first

> #### Package Overview
>
> pandas is a [Python](https://www.python.org/) package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, **real-world** data analysis in Python. 

> ##### Make sure to create a new environment

---

### Code Block

```python
# comment 1
dates = pd.date_range('1/10/2021', periods=100, freq='H')
sales = np.random.randint(100, 500, size=len(dates))
ts = pd.Series(data=sales, index=dates, name='sales')
for i in range(10):
  try:
    print(i)
# comment 2
print(pd.date_range(start='1/10/2021', periods=10, freq='2D'))

```

