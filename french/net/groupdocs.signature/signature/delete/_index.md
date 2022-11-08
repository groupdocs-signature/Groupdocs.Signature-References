---
title: Delete
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Supprime la signature transmiseBaseSignaturegroupdocs.signature.domain/basesignature du document.
type: docs
weight: 110
url: /fr/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Supprime la signature transmise[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) du document.

```csharp
public bool Delete(BaseSignature signature)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signature | BaseSignature | Objet de signature à supprimer du document. |

### Return_Value

Renvoie true si l'opération a réussi.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la suppression de la signature électronique d'un document en C# : [Comment supprimer eSignature d'un document avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Cas d'utilisation avancés de la suppression des signatures électroniques de documents : [Comment supprimer différents types de signatures électroniques d'un document en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir également

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Supprime la liste des signatures passées[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) du document.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatures | List`1 | Liste des signatures à supprimer du document. |

### Return_Value

Renvoie DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la suppression de la signature électronique d'un document en C# : [Comment supprimer eSignature d'un document avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Cas d'utilisation avancés de la suppression des signatures électroniques de documents : [Comment supprimer différents types de signatures électroniques d'un document en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir également

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Supprime les signatures d'un certain type[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) seront supprimés. Les types de signature suivants sont pris en charge : Texte, Image, Numérique, Code-barres, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatureType | SignatureType | Type de signatures à supprimer du document. |

### Return_Value

Renvoie DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la suppression de la signature électronique d'un document en C# : [Comment supprimer des signatures électroniques avec un type spécifique d'un document avec GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Cas d'utilisation avancés de la suppression des signatures électroniques de documents : [Comment supprimer différents types de signatures électroniques d'un document en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir également

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Supprime les signatures de la liste de certains types[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) du document. Seules les signatures qui ont été ajoutées par la méthode Sign et marquées comme Signatures[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) seront supprimés. Les types de signature suivants sont pris en charge : Texte, Image, Numérique, Code-barres, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatureTypes | List`1 | La liste des types de signatures à supprimer du document. |

### Return_Value

Renvoie DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la suppression de la signature électronique d'un document en C# : [Comment supprimer des signatures électroniques avec un type spécifique d'un document avec GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Cas d'utilisation avancés de la suppression des signatures électroniques de documents : [Comment supprimer différents types de signatures électroniques d'un document en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir également

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Supprime la signature par son identifiant de signature spécifique du document.

```csharp
public bool Delete(string signatureId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatureId | String | L'ID de la signature à supprimer du document. |

### Return_Value

Renvoie true si l'opération a réussi.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la suppression de la signature électronique d'un document en C# : [Comment supprimer eSignature d'un document avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Cas d'utilisation avancés de la suppression des signatures électroniques de documents : [Comment supprimer différents types de signatures électroniques d'un document en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir également

* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Supprime la liste des signatures passées[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) du document.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatureIds | List`1 | Liste des identifiants des signatures à retirer du document. |

### Return_Value

Renvoie DeleteResult[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) avec la liste des signatures supprimées avec succès et celles qui ont échoué.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la suppression de la signature électronique d'un document en C# : [Comment supprimer eSignature d'un document avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Cas d'utilisation avancés de la suppression des signatures électroniques de documents : [Comment supprimer différents types de signatures électroniques d'un document en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Voir également

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
