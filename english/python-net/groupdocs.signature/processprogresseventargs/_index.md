---
title: ProcessProgressEventArgs class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/processprogresseventargs/
is_root: false
weight: 80
---

## ProcessProgressEventArgs class

Provides data for OnProgress event of signing, verification and search processes.



**Inheritance:** [`ProcessProgressEventArgs`](/signature/python-net/groupdocs.signature/processprogresseventargs) → 
[`ProcessEventArgs`](/signature/python-net/groupdocs.signature/processeventargs)



The ProcessProgressEventArgs type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/processprogresseventargs/__init__/#) | Constructs a new instance of ProcessProgressEventArgs |


### Properties
| Property | Description |
| :- | :- |
| [status](/signature/python-net/groupdocs.signature/processprogresseventargs/status) | Indicates current process state. |
| [progress](/signature/python-net/groupdocs.signature/processprogresseventargs/progress) | Represents the progress in percents. Value range is from 0 to 100. |
| [ticks](/signature/python-net/groupdocs.signature/processprogresseventargs/ticks) | Represents the time spent in milliseconds since process Start event. |
| [processed_signatures](/signature/python-net/groupdocs.signature/processprogresseventargs/processed_signatures) | Represents the quantity of processed signatures. |
| [cancel](/signature/python-net/groupdocs.signature/processprogresseventargs/cancel) | Indicates whether process should be canceled. |



### See Also
* module [`groupdocs.signature`](..)
* class [`ProcessEventArgs`](/signature/python-net/groupdocs.signature/processeventargs)
* class [`ProcessProgressEventArgs`](/signature/python-net/groupdocs.signature/processprogresseventargs)
