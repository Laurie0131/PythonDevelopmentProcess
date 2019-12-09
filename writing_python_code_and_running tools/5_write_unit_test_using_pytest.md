## 5. Write unit test using pytest **:** {#5-write-unit-test-using-pytest}

> Use pytest library to write unit test. Unit test for sample program shown

below and test_sample.py attached in appendix.

************************************************************************************

from sample_fixed import AddTen

def test_answer():

sum10 = AddTen(20)

assert sum10.add_ten() == 30

***********************************************************************

Run unit test and make sure no all tests passed.

![](media/media/image8.png)