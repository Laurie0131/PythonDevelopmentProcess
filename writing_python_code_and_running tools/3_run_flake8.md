<!--- @file
  3 run flafe8.md for Python Development Process and Coding Specification

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

## 3\. Run flake8: {#3-run-flake8}

Run `flake8`. The output of `flake8` on `sample.py` shown below



```shell
python -m flake8 sample.py
```



![](/media/image4.png)
###### Fig 4. Output of flake8{#fig-4-output-of-flake8}

Fix `flake8` issues and run falke8 again to check there is no errors reported.

---

### Source code `sample_fixed.py`:



```python
“””Sample file with flake8 errors fixed.”””

class AddTen:
    """Class for add ten to a given number."""

    def __init__(self, user_input: int = 0):
        “””Initialization.”””
        self.user_input = user_input
        self.new_varaible = 10

    def add_ten(self)->int:
        """Method to add ten to given number."""
        try:
            return self.new_varaible + self.user_input
        except Exception as e:
            raise e

```

---

Modified code with no errors looks like below and `sample_fixed.py` attached in the appendix.

```shell
python -m flake8 sample_fixed.py
```
![](/media/image5.png)
###### Fig 5. Output of modified code with no errors{#fig-5-output-of-modified-code-with-no-errors}

<br>
