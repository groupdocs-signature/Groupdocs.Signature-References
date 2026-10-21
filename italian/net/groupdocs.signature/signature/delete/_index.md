---
title: "Delete"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Elimina la firma passata BaseSignaturegroupdocs.signature.domain/basesignature dal documento."
type: docs
weight: 110
url: /it/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Elimina la firma passata [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dal documento.

```csharp
public bool Delete(BaseSignature signature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | BaseSignature | Oggetto firma da rimuovere dal documento. |

### Valore di ritorno

Restituisce true se l'operazione è riuscita.

### Osservazioni

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Vedi anche

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Elimina l'elenco di firme passate [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dal documento.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firme | List`1 | Elenco delle firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme eliminate con successo e di quelle non riuscite.

### Osservazioni

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Vedi anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Elimina le firme di un determinato tipo [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dal documento. Solo le firme aggiunte tramite il metodo Sign e contrassegnate come firme [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) verranno rimosse. Sono supportati i seguenti tipi di firma: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureType | SignatureType | Il tipo di firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme eliminate con successo e di quelle non riuscite.

### Osservazioni

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Vedi anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Elimina le firme di un elenco di determinati tipi [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dal documento. Solo le firme aggiunte tramite il metodo Sign e contrassegnate come firme [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) verranno rimosse. Sono supportati i seguenti tipi di firma: Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureTypes | List`1 | L'elenco dei tipi di firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme eliminate con successo e di quelle non riuscite.

### Osservazioni

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Vedi anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Elimina la firma tramite il suo ID firma specifico dal documento.

```csharp
public bool Delete(string signatureId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | String | L'Id della firma da rimuovere dal documento. |

### Valore di ritorno

Restituisce true se l'operazione è riuscita.

### Osservazioni

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Vedi anche

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Elimina l'elenco di firme passate [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dal documento.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureIds | List`1 | Elenco degli identificatori delle firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme eliminate con successo e di quelle non riuscite.

### Osservazioni

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Vedi anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
