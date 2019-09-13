# pyIUDX - Python SDK for IUDX.

## Installation
```
pip install pyIUDX
```

## Usage

### Catalogue
```python
from pyIUDX import Catalogue 
cat = Catalogue()
print(cat.connectToCat("https://catalogue.iudx.org.in", "443", "1"))  # IP/ Domain, Port, Version 
print(cat.getItemCount())
print(cat.getAllItems())
print(cat.getResourceItem("rbccps.org/aa9d66a000d94a78895de8d4c0b3a67f3450e531/pscdcl/aqm-bosch-climo/Pune Railway Station_28"))

```
## PyPI
[https://pypi.org/project/pyIUDX/](https://pypi.org/project/pyIUDX/)

## Authors
* Mukunth A
* Jishnu P
