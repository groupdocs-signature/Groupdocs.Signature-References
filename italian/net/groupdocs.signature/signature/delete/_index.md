---
title: Delete
second_title: Riferimento API GroupDocs.Signature per .NET
description: Elimina la firma passataBaseSignaturegroupdocs.signature.domain/basesignature dal documento.
type: docs
weight: 110
url: /it/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Elimina la firma passata[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dal documento.

```csharp
public bool Delete(BaseSignature signature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signature | BaseSignature | Oggetto firma da rimuovere dal documento. |

### Valore di ritorno

Restituisce vero se l'operazione è andata a buon fine.

### Osservazioni

**Saperne di più**

* Ulteriori informazioni su come eliminare la firma elettronica dal documento in C#: [Come eliminare la firma elettronica dal documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casi d'uso avanzati per l'eliminazione delle firme elettroniche dei documenti: [Come eliminare diversi tipi di firme elettroniche dal documento in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Guarda anche

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Elimina l'elenco delle firme passate[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dal documento.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatures | List`1 | Elenco delle firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme cancellate con successo e quelle fallite.

### Osservazioni

**Saperne di più**

* Ulteriori informazioni su come eliminare la firma elettronica dal documento in C#: [Come eliminare la firma elettronica dal documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casi d'uso avanzati per l'eliminazione delle firme elettroniche dei documenti: [Come eliminare diversi tipi di firme elettroniche dal documento in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Guarda anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Elimina le firme di un determinato tipo[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dal documento. Solo le firme aggiunte con il metodo Firma e contrassegnate come Firme[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) verrà rimosso. Sono supportati i seguenti tipi di firma: testo, immagine, digitale, codice a barre, codice QR

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureType | SignatureType | Il tipo di firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme cancellate con successo e quelle fallite.

### Osservazioni

**Saperne di più**

* Ulteriori informazioni su come eliminare la firma elettronica dal documento in C#: [Come eliminare le firme elettroniche con un tipo specifico dal documento con GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Casi d'uso avanzati per l'eliminazione delle firme elettroniche dei documenti: [Come eliminare diversi tipi di firme elettroniche dal documento in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Guarda anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Elimina le firme dell'elenco di determinati tipi[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) dal documento. Solo le firme aggiunte con il metodo Firma e contrassegnate come Firme[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) verrà rimosso. Sono supportati i seguenti tipi di firma: testo, immagine, digitale, codice a barre, codice QR

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureTypes | List`1 | L'elenco dei tipi di firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme cancellate con successo e quelle fallite.

### Osservazioni

**Saperne di più**

* Ulteriori informazioni su come eliminare la firma elettronica dal documento in C#: [Come eliminare le firme elettroniche con un tipo specifico dal documento con GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Casi d'uso avanzati per l'eliminazione delle firme elettroniche dei documenti: [Come eliminare diversi tipi di firme elettroniche dal documento in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Guarda anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Elimina la firma in base al suo ID firma specifico dal documento.

```csharp
public bool Delete(string signatureId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | String | L'ID della firma da rimuovere dal documento. |

### Valore di ritorno

Restituisce vero se l'operazione è andata a buon fine.

### Osservazioni

**Saperne di più**

* Ulteriori informazioni su come eliminare la firma elettronica dal documento in C#: [Come eliminare la firma elettronica dal documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casi d'uso avanzati per l'eliminazione delle firme elettroniche dei documenti: [Come eliminare diversi tipi di firme elettroniche dal documento in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Guarda anche

* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Elimina l'elenco delle firme passate[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) dal documento.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureIds | List`1 | Elenco degli identificatori delle firme da rimuovere dal documento. |

### Valore di ritorno

Restituisce DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con l'elenco delle firme cancellate con successo e quelle fallite.

### Osservazioni

**Saperne di più**

* Ulteriori informazioni su come eliminare la firma elettronica dal documento in C#: [Come eliminare la firma elettronica dal documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casi d'uso avanzati per l'eliminazione delle firme elettroniche dei documenti: [Come eliminare diversi tipi di firme elettroniche dal documento in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Guarda anche

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* spazio dei nomi [GroupDocs.Signature](../../signature)
* assemblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
