## 5. Write a unit test using pytest **:** {#5-write-unit-test-using-pytest}

Use pytest library to write a unit test. Unit test for sample program shown below and test_sample.py attached in appendix.

---


```python
from sample_fixed import AddTen

def test_answer():
  sum10 = AddTen(20)
  assert sum10.add_ten() == 30
```



---
Run unit test and make sure all tests pass.

![](/media/image8.png)
###### Fig 8. Shows all tests pass{#fig-8-shows-all-tests-pass}

<br>