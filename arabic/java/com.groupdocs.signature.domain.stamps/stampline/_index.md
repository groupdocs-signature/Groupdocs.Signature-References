---
title: "StampLine"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "حدد خصائص خط الطابع."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.domain.stamps/stampline/
---
**Inheritance:**
java.lang.Object
```
public class StampLine
```

حدد خصائص خط الطابع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [StampLine()](#StampLine--) | إنشاء StampLine بالقيم الافتراضية. |
|
|  | [StampLine(String text)](#StampLine-java.lang.String-) | إنشاء StampLine بالنص. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getHeight()](#getHeight--) | الحصول أو الضبط لارتفاع السطر على Stamp. |
|
|  | [setHeight(int value)](#setHeight-int-) | الحصول أو الضبط لارتفاع السطر على Stamp. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | الحصول أو الضبط للون الخلفية للتوقيع. |
|
|  | [getText()](#getText--) | الحصول أو الضبط لنص stamp line. |
|
|  | [setText(String value)](#setText-java.lang.String-) | الحصول أو الضبط لنص stamp line. |
|
|  | [getFont()](#getFont--) | احصل أو اضبط Font لنص Stamp Line. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | احصل أو اضبط Font لنص Stamp Line. |
|
|  | [getTextColor()](#getTextColor--) | الحصول أو الضبط للون نص التوقيع. |
|
|  | [setTextColor(Color value)](#setTextColor-java.awt.Color-) | الحصول أو الضبط للون نص التوقيع. |
|
|  | [setTextColor(String value)](#setTextColor-java.lang.String-) | الحصول أو الضبط للون نص التوقيع. |
|
|  | [getTextBottomIntent()](#getTextBottomIntent--) | الحصول أو الضبط لتوجيه النص السفلي. |
|
|  | [setTextBottomIntent(int value)](#setTextBottomIntent-int-) | الحصول أو الضبط لتوجيه النص السفلي. |
|
|  | [getTextRepeatType()](#getTextRepeatType--) | الحصول أو الضبط لنوع تكرار النص. |
|
|  | [setTextRepeatType(int value)](#setTextRepeatType-int-) | الحصول أو الضبط لنوع تكرار النص. |
|
|  | [getOuterBorder()](#getOuterBorder--) | إعداد Outer Border. |
|
|  | [setOuterBorder(Border value)](#setOuterBorder-com.groupdocs.signature.domain.Border-) | إعداد Outer Border. |
|
|  | [getInnerBorder()](#getInnerBorder--) | إعداد Internal Border. |
|
|  | [setInnerBorder(Border value)](#setInnerBorder-com.groupdocs.signature.domain.Border-) | إعداد Internal Border. |
|
|  | [getVisible()](#getVisible--) | احصل واضبط رؤية Stamp Line. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | احصل واضبط رؤية Stamp Line. |
|
### StampLine() {#StampLine--}
```
public StampLine()
```


إنشاء StampLine بالقيم الافتراضية.


### StampLine(String text) {#StampLine-java.lang.String-}
```
public StampLine(String text)
```


إنشاء StampLine بالنص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص Stamp Line. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


الحصول أو الضبط لارتفاع السطر على Stamp.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


الحصول أو الضبط لارتفاع السطر على Stamp.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public final void setBackgroundColor(String value)
```


الحصول أو الضبط للون الخلفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


الحصول أو الضبط لنص stamp line.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


الحصول أو الضبط لنص stamp line.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


احصل أو اضبط Font لنص Stamp Line.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


احصل أو اضبط Font لنص Stamp Line.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


الحصول أو الضبط للون نص التوقيع.


**Returns:**
java.awt.Color
### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public final void setTextColor(Color value)
```


الحصول أو الضبط للون نص التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setTextColor(String value) {#setTextColor-java.lang.String-}
```
public final void setTextColor(String value)
```


الحصول أو الضبط للون نص التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTextBottomIntent() {#getTextBottomIntent--}
```
public final int getTextBottomIntent()
```


الحصول أو الضبط لتوجيه النص السفلي.


**Returns:**
int
### setTextBottomIntent(int value) {#setTextBottomIntent-int-}
```
public final void setTextBottomIntent(int value)
```


الحصول أو الضبط لتوجيه النص السفلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTextRepeatType() {#getTextRepeatType--}
```
public final int getTextRepeatType()
```


الحصول أو الضبط لنوع تكرار النص.


**Returns:**
int
### setTextRepeatType(int value) {#setTextRepeatType-int-}
```
public final void setTextRepeatType(int value)
```


الحصول أو الضبط لنوع تكرار النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getOuterBorder() {#getOuterBorder--}
```
public final Border getOuterBorder()
```


إعداد Outer Border.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setOuterBorder(Border value) {#setOuterBorder-com.groupdocs.signature.domain.Border-}
```
public final void setOuterBorder(Border value)
```


إعداد Outer Border.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getInnerBorder() {#getInnerBorder--}
```
public final Border getInnerBorder()
```


إعداد Internal Border.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setInnerBorder(Border value) {#setInnerBorder-com.groupdocs.signature.domain.Border-}
```
public final void setInnerBorder(Border value)
```


إعداد Internal Border.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


احصل واضبط رؤية Stamp Line.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


احصل واضبط رؤية Stamp Line.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

