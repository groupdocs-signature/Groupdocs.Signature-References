---
title: "Delete"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Elimina la firma proporcionada BaseSignaturegroupdocs.signature.domain/basesignature del documento."
type: docs
weight: 110
url: /es/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Elimina la firma proporcionada [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) del documento.

```csharp
public bool Delete(BaseSignature signature)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firma | BaseSignature | Objeto de firma que se eliminará del documento. |

### Valor de retorno

Devuelve true si la operación fue exitosa.

### Observaciones

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Elimina la lista de firmas proporcionada [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) del documento.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firmas | List`1 | Lista de firmas para eliminar del documento. |

### Valor de retorno

Devuelve DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con la lista de firmas eliminadas con éxito y las que fallaron.

### Observaciones

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Elimina firmas de un tipo determinado [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) del documento. Solo se eliminarán las firmas que fueron añadidas mediante el método Sign y marcadas como firmas [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature). Los siguientes tipos de firma son compatibles: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureType | SignatureType | El tipo de firmas que se eliminarán del documento. |

### Valor de retorno

Devuelve DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con la lista de firmas eliminadas con éxito y las que fallaron.

### Observaciones

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Elimina las firmas de la lista de ciertos tipos [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) del documento. Solo se eliminarán las firmas que fueron añadidas mediante el método Sign y marcadas como firmas [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature). Los siguientes tipos de firma son compatibles: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureTypes | List`1 | La lista de tipos de firmas que se eliminarán del documento. |

### Valor de retorno

Devuelve DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con la lista de firmas eliminadas con éxito y las que fallaron.

### Observaciones

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Elimina la firma por su Id de firma específico del documento.

```csharp
public bool Delete(string signatureId)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureId | String | El Id de la firma que se eliminará del documento. |

### Valor de retorno

Devuelve true si la operación fue exitosa.

### Observaciones

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Elimina la lista de firmas proporcionada [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) del documento.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signatureIds | List`1 | Lista de los identificadores de las firmas que se eliminarán del documento. |

### Valor de retorno

Devuelve DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con la lista de firmas eliminadas con éxito y las que fallaron.

### Observaciones

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
