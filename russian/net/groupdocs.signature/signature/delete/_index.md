---
title: Delete
second_title: Справочник по API GroupDocs.Signature для .NET
description: Удаляет переданную подписьBaseSignaturegroupdocs.signature.domain/basesignature из документа.
type: docs
weight: 110
url: /ru/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Удаляет переданную подпись[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) из документа.

```csharp
public bool Delete(BaseSignature signature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signature | BaseSignature | Объект подписи, подлежащий удалению из документа. |

### Возвращаемое значение

Возвращает true, если операция прошла успешно.

### Примечания

**Учить больше**

* Подробнее о том, как удалить электронную подпись из документа на C#: [Как удалить электронную подпись из документа с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Расширенные варианты использования удаления электронных подписей документов: [Как удалить разные типы электронных подписей из документа на С#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Смотрите также

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Удаляет переданный список подписей[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) из документа.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatures | List`1 | Список подписей, которые необходимо удалить из документа. |

### Возвращаемое значение

Возвращает Удалить Результат[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удаленных подписей и неудачных.

### Примечания

**Учить больше**

* Подробнее о том, как удалить электронную подпись из документа на C#: [Как удалить электронную подпись из документа с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Расширенные варианты использования удаления электронных подписей документов: [Как удалить разные типы электронных подписей из документа на С#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Смотрите также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Удаляет подписи определенного типа[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) из документа. Только подписи, добавленные методом Sign и помеченные как Signatures[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) будет удален. Поддерживаются следующие типы подписи: Текст, Изображение, Цифровая, Штрих-код, QR-код

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureType | SignatureType | Тип подписи, которую необходимо удалить из документа. |

### Возвращаемое значение

Возвращает Удалить Результат[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удаленных подписей и неудачных.

### Примечания

**Учить больше**

* Подробнее о том, как удалить электронную подпись из документа на C#: [Как удалить электронные подписи определенного типа из документа с помощью GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Расширенные варианты использования удаления электронных подписей документов: [Как удалить разные типы электронных подписей из документа на С#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Смотрите также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Удаляет подписи определенного списка типов[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) из документа. Только подписи, добавленные методом Sign и помеченные как Signatures[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) будет удален. Поддерживаются следующие типы подписи: Текст, Изображение, Цифровая, Штрих-код, QR-код

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureTypes | List`1 | Список типов подписей, которые необходимо удалить из документа. |

### Возвращаемое значение

Возвращает Удалить Результат[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удаленных подписей и неудачных.

### Примечания

**Учить больше**

* Подробнее о том, как удалить электронную подпись из документа на C#: [Как удалить электронные подписи определенного типа из документа с помощью GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Расширенные варианты использования удаления электронных подписей документов: [Как удалить разные типы электронных подписей из документа на С#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Смотрите также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Удаляет подпись по ее конкретному идентификатору подписи из документа.

```csharp
public bool Delete(string signatureId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureId | String | Идентификатор подписи, которую необходимо удалить из документа. |

### Возвращаемое значение

Возвращает true, если операция прошла успешно.

### Примечания

**Учить больше**

* Подробнее о том, как удалить электронную подпись из документа на C#: [Как удалить электронную подпись из документа с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Расширенные варианты использования удаления электронных подписей документов: [Как удалить разные типы электронных подписей из документа на С#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Смотрите также

* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Удаляет переданный список подписей[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) из документа.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureIds | List`1 | Список идентификаторов подписей, подлежащих удалению из документа. |

### Возвращаемое значение

Возвращает Удалить Результат[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удаленных подписей и неудачных.

### Примечания

**Учить больше**

* Подробнее о том, как удалить электронную подпись из документа на C#: [Как удалить электронную подпись из документа с помощью GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Расширенные варианты использования удаления электронных подписей документов: [Как удалить разные типы электронных подписей из документа на С#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Смотрите также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* пространство имен [GroupDocs.Signature](../../signature)
* сборка [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
