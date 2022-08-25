# i4sect

insertect(x0, y0, x1, y1, x2, y2, x3, y3) calucurate intersection between two line segments and return the coordinate of the intersection.

Four points: p1(x0, y0), p1(x1, y1), p3(x2, y2), p4(x3, y3)

Two line segments: segment1(p1, p2) and segment2(p3, p4)

return value: (x, y) or False

# How to install

pip install i4sect

# How to use
```python:sample
from i4sect import *
p = intersect(0, 0, 15, 0, 0, 5, 10, 5) # paralell
if p == False:
   print('no intersection.')
else:
   print(p[0], p[1])
```
