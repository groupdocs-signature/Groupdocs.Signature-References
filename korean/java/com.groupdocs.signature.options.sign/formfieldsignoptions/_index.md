---
title: "FormFieldSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "Pdf 문서용 FormField 서명 옵션 클래스를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Pdf 문서용 FormField 서명 옵션 클래스를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | PdfFormFieldSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | PdfFormFieldSignOptions 클래스의 새 인스턴스를 FormField 서명으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSignature()](#getSignature--) | 서명의 FormField를 가져오거나 설정합니다. |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | 서명의 FormField를 가져오거나 설정합니다. |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


PdfFormFieldSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


PdfFormFieldSignOptions 클래스의 새 인스턴스를 FormField 서명으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


서명의 FormField를 가져오거나 설정합니다.


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


서명의 FormField를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

