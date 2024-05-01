---
title: PdfTextStickerAppearance
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Describes appearance of PDF text annotation sticker object and pop-up window of sticker.
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Describes appearance of PDF text annotation sticker object and pop-up window of sticker.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Creates PDF signature text annotation appearance object. |
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets or sets title of pop-up window. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets title of pop-up window. |
| [getSubject()](#getSubject--) | Gets or sets subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets subject. |
| [getContents()](#getContents--) | Gets or sets the contents of pop-up window. |
| [setContents(String value)](#setContents-java.lang.String-) | Gets or sets the contents of pop-up window. |
| [getOpened()](#getOpened--) | Setup if sticker pop-up window will be opened by default. |
| [setOpened(boolean value)](#setOpened-boolean-) | Setup if sticker pop-up window will be opened by default. |
| [getIcon()](#getIcon--) | Gets or sets the icon of sticker. |
| [setIcon(int value)](#setIcon-int-) | Gets or sets the icon of sticker. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets default appearance for sticker. |
| [resetDefaultAppearance()](#resetDefaultAppearance--) | Clears values of default appearance for sticker. |
| [toString()](#toString--) | Override string conversion. |
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Creates PDF signature text annotation appearance object.

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets or sets title of pop-up window.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gets or sets title of pop-up window.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets subject.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Gets or sets the contents of pop-up window.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Gets or sets the contents of pop-up window.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Setup if sticker pop-up window will be opened by default.

**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Setup if sticker pop-up window will be opened by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Gets or sets the icon of sticker.

**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Gets or sets the icon of sticker.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Gets default appearance for sticker. These properties are applied as default if Options.SignatureAppearance property is not specified. The properties could be changed by user any time.

**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Clears values of default appearance for sticker.

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
