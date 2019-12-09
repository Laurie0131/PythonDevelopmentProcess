## 3\. Run flake8: {#3-run-flake8}

Run flake8 . The output of flake8 on sample.py shown below

![](media/media/image4.png)

Fix flake8 issues and run falke8 again to check there are no error reported.

*************************************************************************************

**#Source code sample.fixed.py:**

**“””Sample file with flake8 errors fixed.”””**

class AddTen:

&quot;&quot;&quot;Class for add ten to a given number.&quot;&quot;&quot;

def __init__(self, user_input: int = 0):

“””Initialization.”””

self.user_input = user_input

self.new_varaible = 10

def add_ten(self)-&gt;int:

&quot;&quot;&quot;Method to add ten to given number.&quot;&quot;&quot;

try:

return self.new_varaible + self.user_input

except Exception as e:

raise e

*************************************************************************************

Modified code with no errors looks like below and Sample_fixed.py attached in appendix.

![](media/media/image5.png)