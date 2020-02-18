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

<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN">
<html><head><title>Python: module sample_fixed</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
</head><body bgcolor="#f0f0f8">

<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="heading">
<tr bgcolor="#7799ee">
<td valign=bottom>&nbsp;<br>
<font color="#ffffff" face="helvetica, arial">&nbsp;<br><big><big><strong>sample_fixed</strong></big></big></font></td
><td align=right valign=bottom
><font color="#ffffff" face="helvetica, arial"><a href=".">index</a><br><a href="file:c%3A%5Ckpurma%5Cpythondevelopmentprocess%5Csample_fixed.py">c:\kpurma\pythondevelopmentprocess\sample_fixed.py</a></font></td></tr></table>
    <p><tt>#&nbsp;-*-&nbsp;coding:&nbsp;UTF-8&nbsp;-*-<br>
#&nbsp;@file<br>
#<br>
#&nbsp;@copyright<br>
#&nbsp;INTEL&nbsp;CONFIDENTIAL<br>
#&nbsp;Copyright&nbsp;2019&nbsp;Intel&nbsp;Corporation.&nbsp;&lt;BR&gt;<br>
#<br>
#&nbsp;The&nbsp;source&nbsp;code&nbsp;contained&nbsp;or&nbsp;described&nbsp;herein&nbsp;and&nbsp;all&nbsp;documents&nbsp;related&nbsp;to&nbsp;the<br>
#&nbsp;source&nbsp;code&nbsp;("Material")&nbsp;are&nbsp;owned&nbsp;by&nbsp;Intel&nbsp;Corporation&nbsp;or&nbsp;its&nbsp;suppliers&nbsp;or<br>
#&nbsp;licensors.&nbsp;Title&nbsp;to&nbsp;the&nbsp;Material&nbsp;remains&nbsp;with&nbsp;Intel&nbsp;Corporation&nbsp;or&nbsp;its&nbsp;suppliers<br>
#&nbsp;and&nbsp;licensors.&nbsp;The&nbsp;Material&nbsp;may&nbsp;contain&nbsp;trade&nbsp;secrets&nbsp;and&nbsp;proprietary&nbsp;&nbsp;&nbsp;&nbsp;and<br>
#&nbsp;confidential&nbsp;information&nbsp;of&nbsp;Intel&nbsp;Corporation&nbsp;and&nbsp;its&nbsp;suppliers&nbsp;and&nbsp;licensors,<br>
#&nbsp;and&nbsp;is&nbsp;protected&nbsp;by&nbsp;worldwide&nbsp;copyright&nbsp;and&nbsp;trade&nbsp;secret&nbsp;laws&nbsp;and&nbsp;treaty<br>
#&nbsp;provisions.&nbsp;No&nbsp;part&nbsp;of&nbsp;the&nbsp;Material&nbsp;may&nbsp;be&nbsp;used,&nbsp;copied,&nbsp;reproduced,&nbsp;modified,<br>
#&nbsp;published,&nbsp;uploaded,&nbsp;posted,&nbsp;transmitted,&nbsp;distributed,&nbsp;or&nbsp;disclosed&nbsp;in&nbsp;any&nbsp;way<br>
#&nbsp;without&nbsp;Intel's&nbsp;prior&nbsp;express&nbsp;written&nbsp;permission.<br>
#<br>
#&nbsp;No&nbsp;license&nbsp;under&nbsp;any&nbsp;patent,&nbsp;copyright,&nbsp;trade&nbsp;secret&nbsp;or&nbsp;other&nbsp;intellectual<br>
#&nbsp;property&nbsp;right&nbsp;is&nbsp;granted&nbsp;to&nbsp;or&nbsp;conferred&nbsp;upon&nbsp;you&nbsp;by&nbsp;disclosure&nbsp;or&nbsp;delivery<br>
#&nbsp;of&nbsp;the&nbsp;Materials,&nbsp;either&nbsp;expressly,&nbsp;by&nbsp;implication,&nbsp;inducement,&nbsp;estoppel&nbsp;or<br>
#&nbsp;otherwise.&nbsp;Any&nbsp;license&nbsp;under&nbsp;such&nbsp;intellectual&nbsp;property&nbsp;rights&nbsp;must&nbsp;be<br>
#&nbsp;express&nbsp;and&nbsp;approved&nbsp;by&nbsp;Intel&nbsp;in&nbsp;writing.<br>
#<br>
#&nbsp;Unless&nbsp;otherwise&nbsp;agreed&nbsp;by&nbsp;Intel&nbsp;in&nbsp;writing,&nbsp;you&nbsp;may&nbsp;not&nbsp;remove&nbsp;or&nbsp;alter<br>
#&nbsp;this&nbsp;notice&nbsp;or&nbsp;any&nbsp;other&nbsp;notice&nbsp;embedded&nbsp;in&nbsp;Materials&nbsp;by&nbsp;Intel&nbsp;or<br>
#&nbsp;Intel's&nbsp;suppliers&nbsp;or&nbsp;licensors&nbsp;in&nbsp;any&nbsp;way.<br>
##</tt></p>
<p>
<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="section">
<tr bgcolor="#ee77aa">
<td colspan=3 valign=bottom>&nbsp;<br>
<font color="#ffffff" face="helvetica, arial"><big><strong>Classes</strong></big></font></td></tr>
    
<tr><td bgcolor="#ee77aa"><tt>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</tt></td><td>&nbsp;</td>
<td width="100%"><dl>
<dt><font face="helvetica, arial"><a href="builtins.html#object">builtins.object</a>
</font></dt><dd>
<dl>
<dt><font face="helvetica, arial"><a href="sample_fixed.html#AddTen">AddTen</a>
</font></dt></dl>
</dd>
</dl>
 <p>
<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="section">
<tr bgcolor="#ffc8d8">
<td colspan=3 valign=bottom>&nbsp;<br>
<font color="#000000" face="helvetica, arial"><a name="AddTen">class <strong>AddTen</strong></a>(<a href="builtins.html#object">builtins.object</a>)</font></td></tr>
    
<tr bgcolor="#ffc8d8"><td rowspan=2><tt>&nbsp;&nbsp;&nbsp;</tt></td>
<td colspan=2><tt><a href="#AddTen">AddTen</a>(user_input)<br>
&nbsp;<br>
Class&nbsp;for&nbsp;add&nbsp;ten&nbsp;to&nbsp;a&nbsp;given&nbsp;number<br>&nbsp;</tt></td></tr>
<tr><td>&nbsp;</td>
<td width="100%">Methods defined here:<br>
<dl><dt><a name="AddTen-__init__"><strong>__init__</strong></a>(self, user_input)</dt><dd><tt>Initialize&nbsp;self.&nbsp;&nbsp;See&nbsp;help(type(self))&nbsp;for&nbsp;accurate&nbsp;signature.</tt></dd></dl>

<dl><dt><a name="AddTen-add_ten"><strong>add_ten</strong></a>(self)</dt><dd><tt>Init&nbsp;for&nbsp;calss.</tt></dd></dl>

<hr>
Data descriptors defined here:<br>
<dl><dt><strong>__dict__</strong></dt>
<dd><tt>dictionary&nbsp;for&nbsp;instance&nbsp;variables&nbsp;(if&nbsp;defined)</tt></dd>
</dl>
<dl><dt><strong>__weakref__</strong></dt>
<dd><tt>list&nbsp;of&nbsp;weak&nbsp;references&nbsp;to&nbsp;the&nbsp;object&nbsp;(if&nbsp;defined)</tt></dd>
</dl>
</td></tr></table></td></tr></table><p>
<table width="100%" cellspacing=0 cellpadding=2 border=0 summary="section">
<tr bgcolor="#55aa55">
<td colspan=3 valign=bottom>&nbsp;<br>
<font color="#ffffff" face="helvetica, arial"><big><strong>Data</strong></big></font></td></tr>
    
<tr><td bgcolor="#55aa55"><tt>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</tt></td><td>&nbsp;</td>
<td width="100%"><strong>a</strong> = &lt;sample_fixed.AddTen object&gt;<br>
<strong>c</strong> = 20</td></tr></table>
</body></html>
```

