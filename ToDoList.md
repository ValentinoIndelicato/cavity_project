# To Do List

## Tuesday, July 16th 2024

 - finish Vector class, by adding methods:
    - `__len__`
    - `__setitem__`
    - `__getitem__`
    - rewrite `__init__`, `__add__`, `__sub__`, `__mul__` with attributes for each component instead of `self.array`

 - write similar class for general matrix (n x m) with same methods as vector
 - instead of `__mul__` use `__matmul__` which uses hotkey `@` and add this 
  to the Vector class as well, with appropriate operations. (should represent a matrix multiplication which you'll need to google AND **look at notes**)
