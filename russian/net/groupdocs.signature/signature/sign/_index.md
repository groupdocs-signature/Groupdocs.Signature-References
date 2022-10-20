---
title: Sign
second_title: Справочник по API GroupDocs.Signature для .NET
description: Подписывает документ с помощьюSignOptionsgroupdocs.signature.options/signoptions и сохраняет результат в поток.
type: docs
weight: 160
url: /ru/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Подписывает документ с помощью[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Выходной поток документов. |
| signOptions | SignOptions | Варианты подписи. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Подписывает документ с помощью[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток с предопределенными[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Выходной поток документов. |
| signOptions | SignOptions | Варианты подписи. |
| saveOptions | SaveOptions | Варианты сохранения. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Подробнее о том, как сохранить документы с электронной подписью и настроить процесс сохранения: [Как настроить документы с электронной подписью при сохранении с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Подписывает документ с коллекцией[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Выходной поток документов. |
| signOptionsList | List`1 | Список вариантов подписи. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Подписывает документ с коллекцией[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в поток с предопределенными[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Выходной поток документов. |
| signOptionsList | List`1 | Список вариантов подписи. |
| saveOptions | SaveOptions | Варианты сохранения. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Подробнее о том, как сохранить документы с электронной подписью и настроить процесс сохранения: [Как настроить документы с электронной подписью при сохранении с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Подписывает документ с помощью[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptions | SignOptions | Варианты подписи. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Подписывает документ с помощью[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу с предопределенным[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptions | SignOptions | Варианты подписи. |
| saveOptions | SaveOptions | Варианты сохранения. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Подробнее о том, как сохранить документы с электронной подписью и настроить процесс сохранения: [Как настроить документы с электронной подписью при сохранении с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Подписывает документ с коллекцией[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptionsList | List`1 | Список вариантов подписи. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Подписывает документ с коллекцией[`SignOptions`](../../../groupdocs.signature.options/signoptions) и сохраняет результат в указанный путь к файлу с предопределенным[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к выходному файлу. |
| signOptionsList | List`1 | Список вариантов подписи. |
| saveOptions | SaveOptions | Варианты сохранения. |

### Возвращаемое значение

Возвращает экземпляр[`SignResult`](../../../groupdocs.signature.domain/signresult) со списком вновь созданных подписей.

### Примечания

**Учить больше**

* Подробнее о типах электронных подписей, поддерживаемых GroupDocs.Signature: [Типы электронных подписей, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Подробнее о документах eSign на C#: [Как подписывать документы электронной подписью с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Подробнее о том, как сохранить документы с электронной подписью и настроить процесс сохранения: [Как настроить документы с электронной подписью при сохранении с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Смотрите также

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
