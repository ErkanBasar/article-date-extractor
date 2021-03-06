This is the Python 3 version of the date extractor created by [Webhose.io](https://webhose.io).
====

[![version][pypi-version]][pypi-url]

[![License][pypi-license]][license-url]
[![Downloads][pypi-downloads]][pypi-url]
[![Gitter][gitter-image]][gitter-url]

About
=====

articleDateExtractor (Article Date Extractor) is a simple open source Python module, built and maintained by [Webhose.io](https://webhose.io), that automatically detects, extracts and normalizes the publication date of an online article or blog post.

## Feature


1.  Extracting the publication date information when it is specified in a web page, with over 90% success rate.


## A Quick Example


```python

    import articleDateExtractor

    d = articleDateExtractor.extractArticlePublishedDate("http://edition.cnn.com/2015/11/28/opinions/sutter-cop21-paris-preview-two-degrees/index.html")

    print d

    d = articleDateExtractor.extractArticlePublishedDate("http://techcrunch.com/2015/11/29/tyro-payments/")

    print d

```


## Installing

You can install from source:

```bash

    $ git clone https://github.com/Webhose/article-date-extractor
    $ cd article-date-extractor
    $ python setup.py install
```

## Dependencies

* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) >= 3.2.1
* [python-dateutil](https://github.com/dateutil/dateutil/) >= 2.4.2


[license-url]: https://github.com/Webhose/article-date-extractor/blob/master/LICENSE

[gitter-url]: https://gitter.im/Webhose
[gitter-image]: https://img.shields.io/badge/Gitter-Join%20Chat-blue.svg?style=flat


[pypi-url]: https://pypi.python.org/pypi/articleDateExtractor
[pypi-license]: https://img.shields.io/pypi/l/articleDateExtractor.svg?style=flat
[pypi-version]: https://img.shields.io/pypi/v/articleDateExtractor.svg?style=flat
[pypi-downloads]: https://img.shields.io/pypi/dm/articleDateExtractor.svg?style=flat
