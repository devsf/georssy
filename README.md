# GeoRSSy
[![PyPI](https://img.shields.io/pypi/v/georssy.svg)](https://pypi.python.org/pypi/georssy)
[![PyPI](https://img.shields.io/pypi/status/georssy.svg)](https://pypi.python.org/pypi/georssy)
[![PyPI](https://img.shields.io/pypi/l/georssy.svg)](https://pypi.python.org/pypi/georssy)
[![PyPI](https://img.shields.io/pypi/pyversions/georssy.svg)](https://pypi.python.org/pypi/georssy)
[![PyPI](https://img.shields.io/pypi/format/georssy.svg)](https://pypi.python.org/pypi/georssy)
[![PyPI](https://img.shields.io/pypi/wheel/georssy.svg)](https://pypi.python.org/pypi/georssy)
[![PyPI](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/devsf)

A rough Python GeoRSS (Geographically Encoded Objects for RSS feeds) decoder.

GeoRSSy is a very rough (but powerfull!) decoder for the GeoRSS (Geographically Encoded Objects for RSS feeds) standard.

For information about GeoRSS: http://www.georss.org/

## How to install
To install GeoRSSy, simply:
```bash
$ pip install georssy
```

## How to use
To use georss, simply:
```python
from georssy import GeoRssDecoder
...
georss_entry = GeoRssDecoder( parent_node = r, polygons_over_boxes = True )
tmp = georss_entry.polygon_list
```

## How to Contribute
1. Check for open issues or open a fresh issue to start a discussion around a feature idea or a bug.
2. Fork the repository on GitHub to start making your changes to the master branch (or branch off of it).
3. Write a test which shows that the bug was fixed or that the feature works as expected.
4. Send a pull request and ask the maintainer to merge and publish it.

## TODO
GeoRSSy is a very young project, so there's a lot of things to do! This is a short TO-DO list:
- accept URL to a remote/local XML as input files
- GML: add "Coordinate Reference System" attributes implementation (and add new tests)
- check Python 3 compatibility

---
# WARNING!!! GeoRSSy is currently under development! So it's not so stable as you can expect! :)
---
