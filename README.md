[![Bitcoin-770x433.webp](https://i.postimg.cc/mZzn0CSQ/Bitcoin-770x433.webp)](https://postimg.cc/grp4hwQJ)

# Module 3 Challenge

In this Challenge, I'm taking on the role of an analyst at a high-tech investment firm. The vice president (VP) of your department is considering arbitrage opportunities in Bitcoin and other cryptocurrencies.

As Bitcoin trades on markets across the globe, can you capitalize on simultaneous price dislocations in those markets by using the powers of Pandas?

---

## Technologies

The data we're analyzing comes from a jupyter notebook that we've created and imported files to. We'll be using Python to run and read our data. 

* [jupyter] - (https://github.com/jupyter/notebook) - Helps us run our code and get the information we need from the data listed in csv files.


---

## Installation Guide

In order for us to get the data we need we must import pandas, plots and the csv files we want to observe.

```python
import pandas as pd
from pathlib import Path
%matplotlib inline
```

---

## Usage

To find the information needed we build a jupyter notebook and run various functions to pull the data from csv files.

```python
# Create an overlay plot that visualizes the two dataframes over a period of one day from late in the dataset.

# Be sure that the plots include the parameters `legend`, `figsize`, `title`, `color` and `label` 

bitstamp_sliced.loc['2018-03-26'].plot(legend=True, kind='line', figsize=(17,10), color="green",  title="Bitstamp vs Coinbase Prices - March 26th, 2018", label="Bitstamp")

coinbase_sliced.loc['2018-03-26'].plot(legend=True, kind='line', figsize=(17,10), color="orange",  label="Coinbase")
```

[![output.png](https://i.postimg.cc/ht9cg94z/output.png)](https://postimg.cc/dhtzjZyw)
---

## Contributors

Brought to you by Elgin Braggs Jr.

---

## License

MIT