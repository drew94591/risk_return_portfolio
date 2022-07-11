# Fund Risk-Management Analyzer
This project evaluates four new investment options to determine which should be included in a firm's client portfolio.  The four funds evaluated are Soros Fund Management LLC,
Paulson & Co. Inc, Tiger Global Management LLC, and Berkshire Hathaway Inc. Each fund's performance will be compared to the S&P 500 during the years 2014-2020.  The fund with 
the most investment potential will be analyzed based upon the following key risk-management metrics:

* Daily Returns
* Standard Deviations
* Variances / Covariances
* Betas
* Sharpe Ratios

---

## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [csv](https://docs.python.org/3/library/csv.html) - For reading and writing to csv files

* [path](https://docs.python.org/3/library/pathlib.html) - Used to define file path

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [numpy](https://numpy.org) - A Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices.

* [matplotlib](https://matplotlib.org) - A comprehensive library for creating static, animated, and interactive visualizations in Python.

---

## Usage

To use the fund risk-management analyzer application you must first launch Jupyter Lab by executing the following command within Git Bash:

```python
jupyter lab
```

Within Jupyter Lab you should then be able to run and execute the following notebook:

``` python
risk_return_analysis.ipynb
```

---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/andrewjherrera).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.
