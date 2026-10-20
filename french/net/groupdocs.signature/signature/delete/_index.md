---
title: "Delete"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Supprime la signature transmise BaseSignaturegroupdocs.signature.domain/basesignature du document."
type: docs
weight: 110
url: /fr/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Supprime la signature transmise [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) du document.

```csharp
public bool Delete(BaseSignature signature)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signature | BaseSignature | Objet de signature à supprimer du document. |

### Valeur de retour

Renvoie true si l'opération a réussi.

### Remarques

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir aussi

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Supprime la liste transmise de signatures [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) du document.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatures | List`1 | Liste des signatures à supprimer du document. |

### Valeur de retour

Renvoie DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir aussi

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Supprime les signatures d'un certain type [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) seront supprimées. Les types de signatures suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatureType | SignatureType | Le type de signatures à supprimer du document. |

### Valeur de retour

Renvoie DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir aussi

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Supprime les signatures d'une liste de certains types [`SignatureType`](../../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures [`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) seront supprimées. Les types de signatures suivants sont pris en charge : Text, Image, Digital, Barcode, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatureTypes | List`1 | La liste des types de signatures à supprimer du document. |

### Valeur de retour

Renvoie DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignatures with specific type from document with GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir aussi

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Supprime la signature par son identifiant de signature spécifique du document.

```csharp
public bool Delete(string signatureId)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatureId | String | L'Id de la signature à supprimer du document. |

### Valeur de retour

Renvoie true si l'opération a réussi.

### Remarques

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir aussi

* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Supprime la liste transmise de signatures [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) du document.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signatureIds | List`1 | Liste des identifiants des signatures à supprimer du document. |

### Valeur de retour

Renvoie DeleteResult [`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Learn more**

* More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir aussi

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
