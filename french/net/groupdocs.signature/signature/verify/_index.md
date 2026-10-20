---
title: "Vérifier"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Vérifie les signatures du document avec les données VerifyOptions fournies."
type: docs
weight: 180
url: /fr/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Vérifie les signatures du document avec les données VerifyOptions fournies.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Les options de vérification de la signature. |

### Valeur de retour

Renvoie une instance de [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). La propriété VerificationResult.IsValid renvoie true si le processus de vérification a réussi.

### Remarques

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Voir aussi

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Vérifie les signatures du document en utilisant les options de vérification fournies et filtre les résultats selon le prédicat spécifié. Cette méthode recherche d'abord les signatures correspondant aux options de vérification, les filtre à l'aide du prédicat, puis ne vérifie que les signatures filtrées.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Les options de vérification de la signature. |
| predicate | Func`2 | Le prédicat de filtre pour déterminer quelles signatures doivent être vérifiées. |

### Valeur de retour

Renvoie une liste d'instances de [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) qui satisfont le prédicat fourni.

### Remarques

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Voir aussi

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Vérifie les signatures du document avec une liste de données VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| verifyOptionsList | List`1 | La collection d'options de vérification de la signature. Instance de VerifyOptionsCollection. |

### Valeur de retour

Renvoie une instance de [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). La propriété VerificationResult.IsValid renvoie true si le processus de vérification a réussi.

### Remarques

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Voir aussi

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Vérifie les signatures du document en utilisant toutes les options de vérification disponibles et filtre les résultats selon le prédicat spécifié. Cette méthode recherche d'abord les signatures correspondant aux options de vérification, les filtre à l'aide du prédicat, puis ne vérifie que les signatures filtrées.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| verifyOptionsList | List`1 | La collection d'options de vérification de la signature. Instance de VerifyOptionsCollection. |
| predicate | Func`2 | Le prédicat de filtre pour déterminer quelles signatures doivent être vérifiées. |

### Valeur de retour

Renvoie une liste d'instances de [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) qui satisfont le prédicat fourni.

### Remarques

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Voir aussi

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
