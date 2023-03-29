# Object Oreiented Programming Notes 1 

i think OOP is awesome :D

```python
#example class

class person:
  def __init__(self, name):
    self.name = name
  
  def __str__(self):
    return f"Person Object called: {self.name}"
    
   def __repr__(self):
    return self.__str__()
```

