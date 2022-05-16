# FinTech-Module-7-ETF-Analyzer

# Create a Web Application for an ETF Analyzer

In this exercise you will build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

## Technologies

This project leverages Python 3.9.7 ((default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32) with the following packages:
 
* [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/user/urls.html#managing-workspaces-ui) - For information about the jupyter lab remote workspace hosted by a local computer.

* [numpy](https://numpy.org/doc/stable/) - Source repository. 
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
 
* [pandas](https://pandas.pydata.org/docs/) - Source repository. 
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [hvplot.pandas](https://hvplot.holoviz.org/) pandas documentation.
The PyData ecosystem has a number of core Python data containers that allow users to work with a wide array of datatypes

* [sqlalchemy](https://docs.sqlalchemy.org/en/14/) - SQLAlchemy 1.4 documentation.
The SQLAlchemy SQL Toolkit and Object Relational Mapper is a comprehensive set of tools for working with databases and Python. 
---

## Installation Guide

Before running the application first install the following dependencies.

```
import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy
```

Create a temporary SQLite database and populate the database with content from the etf.db seed file
```
database_connection_string = 'sqlite:///etf.db'
```

Create an engine to interact with the SQLite database
```
engine = sqlalchemy.create_engine(database_connection_string)
```

---

## Usage

The detailed instructions are divided into the following parts:

    Analyze a single asset in the ETF

    Optimize data access with Advanced SQL queries

    Analyze the ETF portfolio

    Deploy the notebook as a web application



---

## Contributors

Gerald Cortright and Berkeley Fintech support staff
---

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


PLEASE SEE RESULTS AS BELOW-


![ScreenShot](/screenshots/1.png)
![ScreenShot](/screenshots/2.png)
![ScreenShot](/screenshots/3.png)
![ScreenShot](/screenshots/4.png)
![ScreenShot](/screenshots/5.png)
