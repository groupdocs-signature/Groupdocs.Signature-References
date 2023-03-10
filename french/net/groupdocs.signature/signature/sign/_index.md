---
title: Sign
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: signe le document avecSignOptionsgroupdocs.signature.options/signoptions et enregistre le résultat dans un flux.
type: docs
weight: 160
url: /fr/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

signe le document avec[`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux de documents de sortie. |
| signOptions | SignOptions | Les options de signature. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

signe le document avec[`SignOptions`](../../../groupdocs.signature.options/signoptions)et enregistre le résultat dans un flux avec des paramètres prédéfinis[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux de documents de sortie. |
| signOptions | SignOptions | Les options de signature. |
| saveOptions | SaveOptions | Les options de sauvegarde. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* En savoir plus sur la manière d'enregistrer des documents signés électroniquement et de personnaliser le processus d'enregistrement : [Comment personnaliser des documents signés électroniquement lors de l'enregistrement à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signe un document avec une collection de[`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux de documents de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signe un document avec une collection de[`SignOptions`](../../../groupdocs.signature.options/signoptions)et enregistre le résultat dans un flux avec des paramètres prédéfinis[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux de documents de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |
| saveOptions | SaveOptions | Les options de sauvegarde. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* En savoir plus sur la manière d'enregistrer des documents signés électroniquement et de personnaliser le processus d'enregistrement : [Comment personnaliser des documents signés électroniquement lors de l'enregistrement à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

signe le document avec[`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptions | SignOptions | Les options de signature. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

signe le document avec[`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié avec prédéfini[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptions | SignOptions | Les options de signature. |
| saveOptions | SaveOptions | Les options de sauvegarde. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* En savoir plus sur la manière d'enregistrer des documents signés électroniquement et de personnaliser le processus d'enregistrement : [Comment personnaliser des documents signés électroniquement lors de l'enregistrement à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signe un document avec une collection de[`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signe un document avec une collection de[`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié avec prédéfini[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |
| saveOptions | SaveOptions | Les options de sauvegarde. |

### Return_Value

Renvoie une instance de[`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de signature électronique pris en charge par GroupDocs.Signature : [Types de signature électronique pris en charge par GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* En savoir plus sur la signature électronique des documents en C# : [Comment signer électroniquement des documents à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* En savoir plus sur la manière d'enregistrer des documents signés électroniquement et de personnaliser le processus d'enregistrement : [Comment personnaliser des documents signés électroniquement lors de l'enregistrement à l'aide de GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir également

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
