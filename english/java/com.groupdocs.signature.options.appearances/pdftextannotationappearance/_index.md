---
title: PdfTextAnnotationAppearance
second_title: GroupDocs.Editor for Java API Reference
description: Describes appearance of PDF text annotation object Title Subject Content.
type: docs
weight: 13
url: /java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Describes appearance of PDF text annotation object (Title, Subject, Content).
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Creates PDF signature txt annotation appearance object. |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Creates PDF signature txt annotation with specified values (title, subject, contents). |
## Methods

| Method | Description |
| --- | --- |
| [getContents()](#getContents--) | Gets or sets content of annotation object. |
| [setContents(String value)](#setContents-java.lang.String-) | Gets or sets content of annotation object. |
| [getSubject()](#getSubject--) | Gets or sets Subject representing description of the object. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets Subject representing description of the object. |
| [getTitle()](#getTitle--) | Gets or sets a Title that will be displayed in title bar of annotation object. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets a Title that will be displayed in title bar of annotation object. |
| [getBorder()](#getBorder--) | Gets or sets different border settings |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Gets or sets different border settings |
| [getBorderEffect()](#getBorderEffect--) | Gets or sets border effect. |
| [setBorderEffect(int value)](#setBorderEffect-int-) | Gets or sets border effect. |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Gets or sets border effect intensity. |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Gets or sets border effect intensity. |
| [getHCornerRadius()](#getHCornerRadius--) | Gets or sets horizontal corner radius. |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | Gets or sets horizontal corner radius. |
| [getVCornerRadius()](#getVCornerRadius--) | Gets or sets vertical corner radius. |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | Gets or sets vertical corner radius. |
| [toString()](#toString--) | Override string conversion. |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Creates PDF signature txt annotation appearance object.

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Creates PDF signature txt annotation with specified values (title, subject, contents).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | Title. |
| subject | java.lang.String | Subject. |
| contents | java.lang.String | Contents. |

### getContents() {#getContents--}
```
public final String getContents()
```


Gets or sets content of annotation object.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Gets or sets content of annotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets Subject representing description of the object.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets Subject representing description of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets or sets a Title that will be displayed in title bar of annotation object.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gets or sets a Title that will be displayed in title bar of annotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Gets or sets different border settings

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Gets or sets different border settings

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Gets or sets border effect.

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Gets or sets border effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Gets or sets border effect intensity. Valid range of value is [0..2].

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Gets or sets border effect intensity. Valid range of value is [0..2].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Gets or sets horizontal corner radius.

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Gets or sets horizontal corner radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Gets or sets vertical corner radius.

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Gets or sets vertical corner radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
