---
title: "Delete"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Удаляет переданную подпись BaseSignaturegroupdocs.signature.domain/basesignature из документа."
type: docs
weight: 110
url: /ru/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Удаляет переданную подпись [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) из документа.

```csharp
public bool Delete(BaseSignature signature)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| подпись | BaseSignature | Объект подписи, который будет удалён из документа. |

### Возвращаемое значение

Возвращает true, если операция была успешной.

### Примечания

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### См. также

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Удаляет переданный список подписей [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) из документа.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| подписи | List`1 | Список подписей для удаления из документа. |

### Возвращаемое значение

Возвращает DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удалённых подписей и неудачных.

### Примечания

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### См. также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Удаляет подписи определённого типа [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) из документа. Будут удалены только подписи, добавленные методом Sign и помеченные как подписи [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature). Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureType | SignatureType | Тип подписей, которые будут удалены из документа. |

### Возвращаемое значение

Возвращает DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удалённых подписей и неудачных.

### Примечания

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### См. также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Удаляет подписи из списка определённых типов [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) из документа. Будут удалены только подписи, добавленные методом Sign и помеченные как подписи [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature). Поддерживаются следующие типы подписей: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureTypes | List`1 | Список типов подписей, которые будут удалены из документа. |

### Возвращаемое значение

Возвращает DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удалённых подписей и неудачных.

### Примечания

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### См. также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Удаляет подпись по её конкретному идентификатору из документа.

```csharp
public bool Delete(string signatureId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureId | String | Идентификатор подписи, которую следует удалить из документа. |

### Возвращаемое значение

Возвращает true, если операция была успешной.

### Примечания

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### См. также

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Удаляет переданный список подписей [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) из документа.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signatureIds | List`1 | Список идентификаторов подписей, которые нужно удалить из документа. |

### Возвращаемое значение

Возвращает DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) со списком успешно удалённых подписей и неудачных.

### Примечания

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### См. также

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
