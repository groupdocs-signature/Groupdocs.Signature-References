---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Описывает отображение цифровой подписи в PDF‑документах."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Описывает отображение цифровой подписи в PDF‑документах.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Создает объект внешнего вида подписи с значениями по умолчанию. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Получает или задает метку контактной информации. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Получает или задает метку контактной информации. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Получает или задает метку причины. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Получает или задает метку причины. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Получает или задает метку местоположения. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Получает или задает метку местоположения. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Получает или задает метку цифровой подписи. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Получает или задает метку цифровой подписи. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Получает или задает метку даты подписи. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Получает или задает метку даты подписи. |
|
|  | [getBackground()](#getBackground--) | Получить или установить фоновый цвет внешнего вида подписи. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Получить или установить фоновый цвет внешнего вида подписи. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Получить или установить фоновый цвет внешнего вида подписи. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Получает или задает название семейства шрифта для отображения меток. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Получает или задает название семейства шрифта для отображения меток. |
|
|  | [getFontSize()](#getFontSize--) | Получает или задает размер шрифта для отображения меток. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Получает или задает размер шрифта для отображения меток. |
|
|  | [getForeground()](#getForeground--) | Получить или установить цвет переднего текста внешнего вида подписи. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Получить или установить цвет переднего текста внешнего вида подписи. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Получить или установить цвет переднего текста внешнего вида подписи. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Создает объект внешнего вида подписи с значениями по умолчанию.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Получает или задает метку контактной информации. Значение по умолчанию: "Contact".
если это значение пусто, метка контакта не будет отображаться в области цифровой подписи.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Получает или задает метку контактной информации. Значение по умолчанию: "Contact".
если это значение пусто, метка контакта не будет отображаться в области цифровой подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Получает или задает метку причины. Значение по умолчанию: "Reason".
если это значение пусто, метка причины не будет отображаться в области цифровой подписи.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Получает или задает метку причины. Значение по умолчанию: "Reason".
если это значение пусто, метка причины не будет отображаться в области цифровой подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Получает или задает метку местоположения. Значение по умолчанию: "Location".
Если это значение пусто, то метка местоположения не будет отображаться в области цифровой подписи.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Получает или задает метку местоположения. Значение по умолчанию: "Location".
Если это значение пусто, то метка местоположения не будет отображаться в области цифровой подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Получает или задает метку цифровой подписи. Значение по умолчанию: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Получает или задает метку цифровой подписи. Значение по умолчанию: "Digitally signed by".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Получает или задает метку даты подписи. Значение по умолчанию: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Получает или задает метку даты подписи. Значение по умолчанию: "Date".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Получить или установить фоновый цвет внешнего вида подписи.
По умолчанию значение равно SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Получить или установить фоновый цвет внешнего вида подписи.
По умолчанию значение равно SystemColors.Windows


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Получить или установить фоновый цвет внешнего вида подписи.
По умолчанию значение равно SystemColors.Windows


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Получает или задает название семейства шрифтов для отображения меток. Значение по умолчанию: "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Получает или задает название семейства шрифтов для отображения меток. Значение по умолчанию: "Arial".


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Получает или задает размер шрифта для отображения меток. Значение по умолчанию: 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Получает или задает размер шрифта для отображения меток. Значение по умолчанию: 10.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Получить или установить цвет переднего текста внешнего вида подписи.
По умолчанию значение равно Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Получить или установить цвет переднего текста внешнего вида подписи.
По умолчанию значение равно Color.FromArgb(76, 100, 255)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Получить или установить цвет переднего текста внешнего вида подписи.
По умолчанию значение равно Color.FromArgb(76, 100, 255)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

