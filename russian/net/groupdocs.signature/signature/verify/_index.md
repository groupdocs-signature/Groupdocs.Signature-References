---
title: "Verify"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Проверяет подписи документа с заданными данными VerifyOptions."
type: docs
weight: 180
url: /ru/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Проверяет подписи документа с заданными данными VerifyOptions.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Параметры проверки подписи. |

### Возвращаемое значение

Возвращает экземпляр [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Свойство VerificationResult.IsValid возвращает true, если процесс проверки завершился успешно.

### Примечания

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### См. также

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Проверяет подписи документа, используя предоставленные параметры проверки, и фильтрует результаты на основе указанного предиката. Этот метод сначала ищет подписи, соответствующие параметрам проверки, фильтрует их с помощью предиката, а затем проверяет только отфильтрованные подписи.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Параметры проверки подписи. |
| predicate | Func`2 | Предикат фильтра для определения, какие подписи следует проверять. |

### Возвращаемое значение

Возвращает список экземпляров [`BaseSignature`](../../../groupdocs.signature.domain/basesignature), удовлетворяющих заданному предикату.

### Примечания

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### См. также

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Проверяет подписи документа с помощью списка данных VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| verifyOptionsList | List`1 | Коллекция параметров проверки подписи. Экземпляр VerifyOptionsCollection. |

### Возвращаемое значение

Возвращает экземпляр [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). Свойство VerificationResult.IsValid возвращает true, если процесс проверки завершился успешно.

### Примечания

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### См. также

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Проверяет подписи документа, используя все доступные параметры проверки, и фильтрует результаты на основе указанного предиката. Этот метод сначала ищет подписи, соответствующие параметрам проверки, фильтрует их с помощью предиката, а затем проверяет только отфильтрованные подписи.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| verifyOptionsList | List`1 | Коллекция параметров проверки подписи. Экземпляр VerifyOptionsCollection. |
| predicate | Func`2 | Предикат фильтра для определения, какие подписи следует проверять. |

### Возвращаемое значение

Возвращает список экземпляров [`BaseSignature`](../../../groupdocs.signature.domain/basesignature), удовлетворяющих заданному предикату.

### Примечания

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### См. также

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
