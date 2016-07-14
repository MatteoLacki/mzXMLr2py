# mzXMLr2py
A parser of the mzXML files. Uses R readMzXML package to read mzXML and then rPy2 to retrieve it in Python.

Requirements:
* R >= 2.15.0 (see [CRAN readMzXmlData page](https://cran.r-project.org/web/packages/readMzXmlData/))
* rPy2

To install the latter, use pip

```{Python}
pip install rpy2
```

The readMzXmlData package can be downloaded in advance using:

```{R}
install.packages('readMzXmlData')
```

or by running the script in the terminal and choosing the CRAN source manually.
