<!--- @file
  appendix.md for Python Development Process and Coding Specification

  Copyright (c) 2019, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->

# Appendix: {#appendix}

### 1.  Flake8 configuration for Windows/Linux:

```phb
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


