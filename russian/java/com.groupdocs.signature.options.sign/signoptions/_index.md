---
title: "SignOptions"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет параметры подписи."
type: docs
weight: 16
url: /ru/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Представляет параметры подписи.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Получает или задает номер страницы документа для подписи. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Получает или задает номер страницы документа для подписи. |
|
|  | [getAllPages()](#getAllPages--) | Поместить подпись на всех страницах документа. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Поместить подпись на всех страницах документа. |
|
|  | [getAppearance()](#getAppearance--) | Дополнительный внешний вид подписи. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Дополнительный внешний вид подписи. |
|
|  | [getExtensions()](#getExtensions--) | Расширения подписи. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Расширения подписи. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Параметры для указания страниц, которые необходимо подписать. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Параметры для указания страниц, которые необходимо подписать. |
|
|  | [getSignatureType()](#getSignatureType--) | Получить тип подписи [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Получить или задать тип документа параметров подписи [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Получить или задать тип документа параметров подписи [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Получает или задает позицию Z‑порядка текстовой подписи. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Получает или задает позицию Z‑порядка текстовой подписи. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Получает или задает алгоритм хеширования, используемый для криптографических операций. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Получает или задает алгоритм хеширования, используемый для криптографических операций. |
|
|  | [toString()](#toString--) | Переопределить преобразование строки. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Получает или задает номер страницы документа для подписи.
Минимальное и значение по умолчанию равно 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Получает или задает номер страницы документа для подписи.
Минимальное и значение по умолчанию равно 1.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Поместить подпись на всех страницах документа.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Поместить подпись на всех страницах документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Дополнительный внешний вид подписи.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Дополнительный внешний вид подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Расширения подписи.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Расширения подписи.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Параметры для указания страниц, которые необходимо подписать.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Параметры для указания страниц, которые необходимо подписать.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Получить тип подписи [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Получить или задать тип документа параметров подписи [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Получить или задать тип документа параметров подписи [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Получает или задает позицию Z‑порядка текстовой подписи.
Определяет порядок отображения перекрывающихся подписей.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Получает или задает позицию Z‑порядка текстовой подписи.
Определяет порядок отображения перекрывающихся подписей.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Получает или задает алгоритм хеширования, используемый для криптографических операций.
Поддерживается исключительно для цифровых подписей в PDF‑файлах.
Значение является одной из констант в [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Получает или задает алгоритм хеширования, используемый для криптографических операций.
Поддерживается исключительно для цифровых подписей в PDF‑файлах.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Переопределить преобразование строки.


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
