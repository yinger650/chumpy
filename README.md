Modify the import rules to support python 3.

The tutorial is from https://blog.csdn.net/qq_28660035/article/details/81319055


chumpy
======

Chumpy is a Python-based framework designed to handle the **auto-differentiation** problem,
which is to evaluate an expression and its derivatives with respect to its inputs, by use of the chain rule.

Chumpy is intended to make construction and local
minimization of objectives easier.

Specifically, it provides:

- Easy problem construction by using Numpy’s application interface
- Easy access to derivatives via auto differentiation
- Easy local optimization methods (12 of them: most of which use the derivatives)

Chumpy comes with its own demos, which can be seen by typing the following:

```python
import chumpy
chumpy.demo() # prints out a list of possible demos
```

Licensing is specified in the attached LICENSE.txt.
