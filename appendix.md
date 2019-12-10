# Appendix: {#appendix}

### 1.  Flake8 configuration for Windows/Linux:

```
[flake8]
# H903  Windows style line endings not allowed in code
# E266 too many leading '#' for block comment
# D203 : One blank line required before class docstring
# H306  : imports not in alphabetical order
ignore = H903, E266, D203, H306
exclude = .git,
max-complexity = 10
max_line_length = 120

```



### 2.  pydoc generated `Sample_fixed.html`:

![](/media/samplehtml.jpg)
###### Fig 10. Example of Html generated from pydoc{#fig-10-example-of-html-generated-from-pydoc}

[Example Html file code](https://raw.githubusercontent.com/Laurie0131/PythonDevelopmentProcess/master/media/index.html)

### 3. Example of `tox.ini`
```ini
[flake8]

exclude = .git

# Maximum length of the line
max-line-length = 120

# Maximum allowed McCabe complexity value for a block of code.
max-complexity = 10

# H903  Windows style line endings not allowed in code
# E266 too many leading '#' for block comment
# D203 : One blank line required before class docstring
# H306  : imports not in alphabetical order

ignore = H903, E266, D203, H306

```





### 4. Example sample.py


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
                    print("Unknown Errror")
                    return None

a = AddTen(10)
c = a.add_ten()
print(c)
```
### 5. Example `sample_fixed.py`




```python
class AddTen:
    """Class for add ten to a given number"""

    def __init__(self, user_input: int = 0):
        self.user_input = user_input
        self.new_varaible = 10

    def add_ten(self)->int:
        """Init for calss."""
        try:
            return self.new_varaible + self.user_input
        except Exception as e:
            raise e



a = AddTen(10)
c = a.add_ten()
print(c)

```

### 6. Example `test_sample.py`


```python

from sample_fixed import AddTen

def test_answer():
    sum10 = AddTen(20)
    assert sum10.add_ten() == 30
    

```


