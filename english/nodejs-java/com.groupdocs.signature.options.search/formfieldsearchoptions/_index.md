---
title: FormFieldSearchOptions
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents abstract search Options for Form-field signatures.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Represents abstract search Options for Form-field signatures.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Initializes a new instance of the SearchFormFieldOptions class with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Specifies type of form field signature if it should be searched. |
| [setType(Integer value)](#setType-java.lang.Integer-) | Specifies type of form field signature if it should be searched. |
| [getName()](#getName--) | Specifies regular expression pattern of form field signature name if it should be searched. |
| [setName(String value)](#setName-java.lang.String-) | Specifies regular expression pattern of form field signature name if it should be searched. |
| [getValue()](#getValue--) | Specifies value of form field signature if it should be searched. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Specifies value of form field signature if it should be searched. |
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Initializes a new instance of the SearchFormFieldOptions class with default values.

### getType() {#getType--}
```
public final Integer getType()
```


Specifies type of form field signature if it should be searched. Default value is null.

**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Specifies type of form field signature if it should be searched. Default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Specifies regular expression pattern of form field signature name if it should be searched. You can use it simple as "text" or regular expression like "abc\\d+". Default value is empty string.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifies regular expression pattern of form field signature name if it should be searched. You can use it simple as "text" or regular expression like "abc\\d+". Default value is empty string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Specifies value of form field signature if it should be searched. Default value is null.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specifies value of form field signature if it should be searched. Default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

