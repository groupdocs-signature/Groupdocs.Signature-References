---
title: "FormFieldSignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет класс параметров подписи полей формы для PDF‑документов."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Представляет класс параметров подписи полей формы для PDF‑документов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | Инициализирует новый экземпляр класса PdfFormFieldSignOptions со значениями по умолчанию. |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Инициализирует новый экземпляр класса PdfFormFieldSignOptions с подписью FormField. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSignature()](#getSignature--) | Получает или задает FormField подписи. |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Получает или задает FormField подписи. |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


Инициализирует новый экземпляр класса PdfFormFieldSignOptions со значениями по умолчанию.


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


Инициализирует новый экземпляр класса PdfFormFieldSignOptions с подписью FormField.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


Получает или задает FormField подписи.


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


Получает или задает FormField подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

