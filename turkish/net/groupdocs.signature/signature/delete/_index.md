---
title: "Delete"
second_title: "GroupDocs.Signature for .NET API Referansı"
description: "Belgeden belirtilen BaseSignaturegroupdocs.signature.domain/basesignature imzasını siler."
type: docs
weight: 110
url: /tr/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Belgeden belirtilen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) imzasını siler.

```csharp
public bool Delete(BaseSignature signature)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imza | BaseSignature | Belgeden kaldırılacak imza nesnesi. |

### Dönüş Değeri

İşlem başarılıysa true döndürür.

### Açıklamalar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca Bakınız

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Belgeden belirtilen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) imzalarının listesini siler.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imzalar | List`1 | Belgeden kaldırılacak imzaların listesi. |

### Dönüş Değeri

Başarıyla silinen ve silinemeyen imzaların listesiyle birlikte DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) döndürür.

### Açıklamalar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca Bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Belgeden belirli bir türdeki [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) imzalarını siler. Yalnızca Sign yöntemiyle eklenen ve Imzalar [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) olarak işaretlenen imzalar kaldırılacaktır. Aşağıdaki imza türleri desteklenir: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureType | SignatureType | Belgeden kaldırılacak imza türü. |

### Dönüş Değeri

Başarıyla silinen ve silinemeyen imzaların listesiyle birlikte DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) döndürür.

### Açıklamalar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca Bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Belgeden belirli türler listesindeki [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) imzalarını siler. Yalnızca Sign yöntemiyle eklenen ve Imzalar [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) olarak işaretlenen imzalar kaldırılacaktır. Aşağıdaki imza türleri desteklenir: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureTypes | List`1 | Belgeden kaldırılacak imza türlerinin listesi. |

### Dönüş Değeri

Başarıyla silinen ve silinemeyen imzaların listesiyle birlikte DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) döndürür.

### Açıklamalar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca Bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Belgeden belirli imza Id'siyle imzayı siler.

```csharp
public bool Delete(string signatureId)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureId | Dize | Belgeden kaldırılacak imzanın Id'si. |

### Dönüş Değeri

İşlem başarılıysa true döndürür.

### Açıklamalar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca Bakınız

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Belgeden belirtilen [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) imzalarının listesini siler.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureIds | List`1 | Belgeden kaldırılacak imzaların tanımlayıcılarının listesi. |

### Dönüş Değeri

Başarıyla silinen ve silinemeyen imzaların listesiyle birlikte DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) döndürür.

### Açıklamalar

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca Bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
