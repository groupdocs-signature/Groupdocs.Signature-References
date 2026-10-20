---
title: "Signer"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "Signe le document avec SignOptionsgroupdocs.signature.options/signoptions et enregistre le résultat dans un flux."
type: docs
weight: 160
url: /fr/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Signe le document avec [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux du document de sortie. |
| signOptions | SignOptions | Les options de signature. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Signe le document avec [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux avec les [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) prédéfinis.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux du document de sortie. |
| signOptions | SignOptions | Les options de signature. |
| saveOptions | SaveOptions | Les options d'enregistrement. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Signe le document avec une collection de [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux du document de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Signe le document avec une collection de [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans un flux avec les [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) prédéfinis.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux du document de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |
| saveOptions | SaveOptions | Les options d'enregistrement. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Signe le document avec [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptions | SignOptions | Les options de signature. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Signe le document avec [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié avec les [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) prédéfinis.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptions | SignOptions | Les options de signature. |
| saveOptions | SaveOptions | Les options d'enregistrement. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Signe le document avec une collection de [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Signe le document avec une collection de [`SignOptions`](../../../groupdocs.signature.options/signoptions) et enregistre le résultat dans le chemin de fichier spécifié avec les [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) prédéfinis.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier de sortie. |
| signOptionsList | List`1 | La liste des options de signature. |
| saveOptions | SaveOptions | Les options d'enregistrement. |

### Valeur de retour

Renvoie une instance de [`SignResult`](../../../groupdocs.signature.domain/signresult) avec la liste des signatures nouvellement créées.

### Remarques

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Voir aussi

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
