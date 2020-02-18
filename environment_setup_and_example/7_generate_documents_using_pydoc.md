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


## 4.7 Generate documents using pydoc: {#7-generate-documents-using-pydoc}

By using the `pydoc` module, documentation is generated in the desired format. 

For example, following command helps to generate html version of pydoc at your source level directory.


```shell
  python -m pydoc -w sample_fixed

```

```

<table width="100%" cellspacing="0" cellpadding="2" border="0" summary="heading">

<tbody>

<tr bgcolor="#7799ee">

<td valign="bottom">   
<font color="#ffffff" face="helvetica, arial">   
<big><big>**sample_fixed**</big></big></font></td>

<td align="right" valign="bottom"><font color="#ffffff" face="helvetica, arial">[index](.)  
[c:\kpurma\pythondevelopmentprocess\sample_fixed.py](file:c%3A%5Ckpurma%5Cpythondevelopmentprocess%5Csample_fixed.py)</font></td>

</tr>

</tbody>

</table>

<tt># -*- coding: UTF-8 -*-  
# @file  
#  
# @copyright  
# INTEL CONFIDENTIAL  
# Copyright 2019 Intel Corporation. <BR>  
#  
# The source code contained or described herein and all documents related to the  
# source code ("Material") are owned by Intel Corporation or its suppliers or  
# licensors. Title to the Material remains with Intel Corporation or its suppliers  
# and licensors. The Material may contain trade secrets and proprietary    and  
# confidential information of Intel Corporation and its suppliers and licensors,  
# and is protected by worldwide copyright and trade secret laws and treaty  
# provisions. No part of the Material may be used, copied, reproduced, modified,  
# published, uploaded, posted, transmitted, distributed, or disclosed in any way  
# without Intel's prior express written permission.  
#  
# No license under any patent, copyright, trade secret or other intellectual  
# property right is granted to or conferred upon you by disclosure or delivery  
# of the Materials, either expressly, by implication, inducement, estoppel or  
# otherwise. Any license under such intellectual property rights must be  
# express and approved by Intel in writing.  
#  
# Unless otherwise agreed by Intel in writing, you may not remove or alter  
# this notice or any other notice embedded in Materials by Intel or  
# Intel's suppliers or licensors in any way.  
##</tt>

<table width="100%" cellspacing="0" cellpadding="2" border="0" summary="section">

<tbody>

<tr bgcolor="#ee77aa">

<td colspan="3" valign="bottom">   
<font color="#ffffff" face="helvetica, arial"><big>**Classes**</big></font></td>

</tr>

<tr>

<td bgcolor="#ee77aa"></td>

<td> </td>

<td width="100%">

<dl>

<dt><font face="helvetica, arial">[builtins.object](builtins.html#object)</font></dt>

<dd>

<dl>

<dt><font face="helvetica, arial">[AddTen](sample_fixed.html#AddTen)</font></dt>

</dl>

</dd>

</dl>

<table width="100%" cellspacing="0" cellpadding="2" border="0" summary="section">

<tbody>

<tr bgcolor="#ffc8d8">

<td colspan="3" valign="bottom">   
<font color="#000000" face="helvetica, arial"><a name="AddTen">class **AddTen**</a>([builtins.object](builtins.html#object))</font></td>

</tr>

<tr bgcolor="#ffc8d8">

<td rowspan="2"></td>

<td colspan="2"><tt>[AddTen](#AddTen)(user_input)  

Class for add ten to a given number  
 </tt></td>

</tr>

<tr>

<td> </td>

<td width="100%">Methods defined here:  

<dl>

<dt><a name="AddTen-__init__">**__init__**</a>(self, user_input)</dt>

<dd><tt>Initialize self.  See help(type(self)) for accurate signature.</tt></dd>

</dl>

<dl>

<dt><a name="AddTen-add_ten">**add_ten**</a>(self)</dt>

<dd><tt>Init for calss.</tt></dd>

</dl>

* * *

Data descriptors defined here:  

<dl>

<dt>**__dict__**</dt>

<dd><tt>dictionary for instance variables (if defined)</tt></dd>

</dl>

<dl>

<dt>**__weakref__**</dt>

<dd><tt>list of weak references to the object (if defined)</tt></dd>

</dl>

</td>

</tr>

</tbody>

</table>

</td>

</tr>

</tbody>

</table>

<table width="100%" cellspacing="0" cellpadding="2" border="0" summary="section">

<tbody>

<tr bgcolor="#55aa55">

<td colspan="3" valign="bottom">   
<font color="#ffffff" face="helvetica, arial"><big>**Data**</big></font></td>

</tr>

<tr>

<td bgcolor="#55aa55"></td>

<td> </td>

<td width="100%">**a** = <sample_fixed.AddTen object>  
**c** = 20</td>

</tr>

</tbody>

</table>
```

