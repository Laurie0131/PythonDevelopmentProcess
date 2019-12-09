## 2\. Write python code : {#2-write-python-code}

Start writing python code. In this example `sample.py` used for as example.

![](/media/image3.png)
###### Fig 3. `Sample.py` as an example{#fig-3-sample-py-as-an-example}
---
### Source code `sample.py`:



```python
import os
        
class AddTen:
    """Class for add ten to a given number"""

    def __init__(self, user_input):
            self.user_input = user_input
            self.new_varaible = 10
            d = {}

    def add_ten(self):
            """Init for calss."""
            try:
                    return self.newvaraible + self.user_input
            except:
                    print("Unknown Error")
                    return None

```

