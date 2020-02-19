<!--- @file
  6 generate documents using pydoc.md for Python Development Process and Coding Specification

  Copyright (c) 2020, Intel Corporation. All rights reserved.<BR>

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


## 4.7 Generate documents using pydoc

By using the `pydoc` module, documentation is generated in the desired format. 

For example, following command helps to generate html version of pydoc at your source level directory.


```shell
  python -m pydoc -w sample_fixed

```


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td> <br />
 <br />
<strong>sample_fixed</strong></td>
<td style="text-align: right;"><a href=".">index</a><br />
<a href="file:c%3A%5Ckpurma%5Cpythondevelopmentprocess%5Csample_fixed.py">c:\kpurma\pythondevelopmentprocess\sample_fixed.py</a></td>
</tr>
</tbody>
</table>

\# -\*- coding: UTF-8 -\*-  
\# @file  
\#  
\# @copyright  
\# INTEL CONFIDENTIAL  
\# Copyright 2019 Intel Corporation. &lt;BR&gt;  
\#  
\# The source code contained or described herein and all documents related to the  
\# source code ("Material") are owned by Intel Corporation or its suppliers or  
\# licensors. Title to the Material remains with Intel Corporation or its suppliers  
\# and licensors. The Material may contain trade secrets and proprietary    and  
\# confidential information of Intel Corporation and its suppliers and licensors,  
\# and is protected by worldwide copyright and trade secret laws and treaty  
\# provisions. No part of the Material may be used, copied, reproduced, modified,  
\# published, uploaded, posted, transmitted, distributed, or disclosed in any way  
\# without Intel's prior express written permission.  
\#  
\# No license under any patent, copyright, trade secret or other intellectual  
\# property right is granted to or conferred upon you by disclosure or delivery  
\# of the Materials, either expressly, by implication, inducement, estoppel or  
\# otherwise. Any license under such intellectual property rights must be  
\# express and approved by Intel in writing.  
\#  
\# Unless otherwise agreed by Intel in writing, you may not remove or alter  
\# this notice or any other notice embedded in Materials by Intel or  
\# Intel's suppliers or licensors in any way.  
\#\#

   
**Classes**

`      `

 

[builtins.object]

[AddTen]

   
<span id="AddTen">class **AddTen**</span>([builtins.object])

`   `

`AddTen(user_input)   Class for add ten to a given number `

 

Methods defined here:  

<span id="AddTen-__init__">**\_\_init\_\_**</span>(self, user\_input)  
`Initialize self.  See help(type(self)) for accurate signature.`

<!-- -->

<span id="AddTen-add_ten">**add\_ten**</span>(self)  
`Init for calss.`

------------------------------------------------------------------------

Data descriptors defined here:  

**\_\_dict\_\_**  
`dictionary for instance variables (if defined)`

<!-- -->

**\_\_weakref\_\_**  
`list of weak references to the object (if defined)`

   
**Data**

`      `

 

**a** = &lt;sample\_fixed.AddTen object&gt;  
**c** = 20

  [builtins.object]: builtins.html#object
  [AddTen]: sample_fixed.html#AddTen

