---
title: Search
second_title: Справочник по API GroupDocs.Signature для .NET
description: Ищет подписи в документе поSearchOptionsgroupdocs.signature.options/searchoptions список.
type: docs
weight: 150
url: /ru/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Ищет подписи в документе по[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) список.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchOptionsList | List`1 | Коллекция параметров поиска. |

### Возвращаемое значение

Возвращает экземпляр[`SearchResult`](../../../groupdocs.signature.domain/searchresult) со списком найденных подписей.

### Примечания

**Учить больше**

* Подробнее о поиске электронных подписей в документах с помощью GroupDocs.Signature: [Как искать электронные подписи внутри документа с помощью C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Подробнее о поиске электронных подписей в зависимости от типа eSign: [Расширенные варианты использования поиска электронных подписей с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Смотрите также

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Ищет подписи в документе по[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) варианты.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchOptions | SearchOptions | Параметры поиска. |

### Возвращаемое значение

Возвращает список найденных подписей.

### Примечания

**Учить больше**

* Подробнее о поиске электронных подписей в документах с помощью GroupDocs.Signature: [Как искать электронные подписи внутри документа с помощью C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Подробнее о поиске электронных подписей в зависимости от типа eSign: [Расширенные варианты использования поиска электронных подписей с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Смотрите также

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Ищет точный тип подписи в документе по[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) значение.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureType | SignatureType | Тип подписи для поиска. |

### Возвращаемое значение

Возвращает список найденных сигнатур с точным типом.

### Примечания

**Учить больше**

* Подробнее о поиске электронных подписей в документах с помощью GroupDocs.Signature: [Как искать электронные подписи внутри документа с помощью C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Подробнее о поиске электронных подписей в зависимости от типа eSign: [Расширенные варианты использования поиска электронных подписей с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Смотрите также

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Ищет указанные типы подписей в документе по[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) значение.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Один или несколько типов подписей для поиска. |

### Возвращаемое значение

Возвращает экземпляр[`SearchResult`](../../../groupdocs.signature.domain/searchresult) со списком найденных подписей.

### Примечания

**Учить больше**

* Подробнее о поиске электронных подписей в документах с помощью GroupDocs.Signature: [Как искать электронные подписи внутри документа с помощью C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Подробнее о поиске электронных подписей в зависимости от типа eSign: [Расширенные варианты использования поиска электронных подписей с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Смотрите также

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
