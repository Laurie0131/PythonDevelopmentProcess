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
