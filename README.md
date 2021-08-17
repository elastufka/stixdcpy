## Python APIs to interact with STIX data center

Example 
```python
from sdc import QuickLook
lc=QuickLook.LightCurves('2021-05-07T00:00:00', '2021-05-08T00:00:00', ltc=True)
lc.peek()
```
