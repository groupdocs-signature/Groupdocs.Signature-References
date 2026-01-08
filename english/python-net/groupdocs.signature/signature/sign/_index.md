---
title: sign method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 70
---

## sign {#io.RawIOBase-groupdocs.signature.options.SignOptions}

Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to a stream.


### Returns 


Returns instance of [`SignResult`](/signature/python-net/groupdocs.signature.domain/signresult) with list of newly created signatures.


```python
def sign(self, document, sign_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The output document stream. |
| sign_options | groupdocs.signature.options.SignOptions | The signature options. |


## sign {#io.RawIOBase-System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]]}





```python
def sign(self, document, sign_options_list):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase |  |
| sign_options_list | System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]] |  |


## sign {#System.String-groupdocs.signature.options.SignOptions}

Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to specified file path.


### Returns 


Returns instance of [`SignResult`](/signature/python-net/groupdocs.signature.domain/signresult) with list of newly created signatures.


```python
def sign(self, file_path, sign_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The output file path. |
| sign_options | groupdocs.signature.options.SignOptions | The signature options. |


## sign {#System.String-System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]]}





```python
def sign(self, file_path, sign_options_list):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String |  |
| sign_options_list | System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]] |  |


## sign {#io.RawIOBase-groupdocs.signature.options.SignOptions-groupdocs.signature.options.SaveOptions}

Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to a stream with predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions).


### Returns 


Returns instance of [`SignResult`](/signature/python-net/groupdocs.signature.domain/signresult) with list of newly created signatures.


```python
def sign(self, document, sign_options, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The output document stream. |
| sign_options | groupdocs.signature.options.SignOptions | The signature options. |
| save_options | groupdocs.signature.options.SaveOptions | The save options. |


## sign {#io.RawIOBase-System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]]-groupdocs.signature.options.SaveOptions}





```python
def sign(self, document, sign_options_list, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase |  |
| sign_options_list | System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]] |  |
| save_options | groupdocs.signature.options.SaveOptions |  |


## sign {#System.String-groupdocs.signature.options.SignOptions-groupdocs.signature.options.SaveOptions}

Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to specified file path with predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions).


### Returns 


Returns instance of [`SignResult`](/signature/python-net/groupdocs.signature.domain/signresult) with list of newly created signatures.


```python
def sign(self, file_path, sign_options, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The output file path. |
| sign_options | groupdocs.signature.options.SignOptions | The signature options. |
| save_options | groupdocs.signature.options.SaveOptions | The save options. |


## sign {#System.String-System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]]-groupdocs.signature.options.SaveOptions}





```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String |  |
| sign_options_list | System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SignOptions]] |  |
| save_options | groupdocs.signature.options.SaveOptions |  |



### See Also
* module [`groupdocs.signature`](../../)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignResult`](/signature/python-net/groupdocs.signature.domain/signresult)
* class [`Signature`](/signature/python-net/groupdocs.signature/signature)
