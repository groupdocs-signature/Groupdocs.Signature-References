---
title: "Sign"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Подписывает документ с помощью SignOptionsgroupdocs.signature.options/signoptions и сохраняет результат в поток."
type: docs
weight: 160
url: /ru/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Подписывает документ с помощью [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток выходного документа. |
| signOptions | SignOptions | Параметры подписи. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Подписывает документ с помощью [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток с предопределёнными [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток выходного документа. |
| signOptions | SignOptions | Параметры подписи. |
| saveOptions | SaveOptions | Параметры сохранения. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Подписывает документ с коллекцией [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток выходного документа. |
| signOptionsList | List`1 | Список вариантов подписи. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Подписывает документ с набором [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток с предопределёнными [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток выходного документа. |
| signOptionsList | List`1 | Список вариантов подписи. |
| saveOptions | SaveOptions | Параметры сохранения. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Подписывает документ с [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptions | SignOptions | Параметры подписи. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Подписывает документ с [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу с предопределёнными [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptions | SignOptions | Параметры подписи. |
| saveOptions | SaveOptions | Параметры сохранения. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Подписывает документ с набором [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptionsList | List`1 | Список вариантов подписи. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Подписывает документ с набором [`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу с предопределёнными [`SaveOptions`](../../../groupdocs.signature.options/saveoptions).

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptionsList | List`1 | Список вариантов подписи. |
| saveOptions | SaveOptions | Параметры сохранения. |

### Возвращаемое значение

Возвращает экземпляр [`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### См. также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
