---
title: "Verificar"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Verifica las firmas del documento con los datos de VerifyOptions proporcionados."
type: docs
weight: 180
url: /es/net/groupdocs.signature/signature/verify/
---
## Verify(VerifyOptions) {#verify}

Verifica las firmas del documento con los datos de VerifyOptions proporcionados.

```csharp
public VerificationResult Verify(VerifyOptions verifyOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Las opciones de verificación de la firma. |

### Valor de retorno

Devuelve una instancia de [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). La propiedad VerificationResult.IsValid devuelve true si el proceso de verificación fue exitoso.

### Observaciones

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ver también

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(VerifyOptions, Func&lt;BaseSignature, bool&gt;) {#verify_2}

Verifica las firmas del documento usando las opciones de verificación proporcionadas y filtra los resultados según el predicado especificado. Este método primero busca firmas que coincidan con las opciones de verificación, las filtra usando el predicado y luego verifica solo esas firmas filtradas.

```csharp
public List<BaseSignature> Verify(VerifyOptions verifyOptions, Func<BaseSignature, bool> predicate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| verifyOptions | VerifyOptions | Las opciones de verificación de la firma. |
| predicate | Func`2 | El predicado de filtro para determinar qué firmas deben verificarse. |

### Valor de retorno

Devuelve una lista de instancias de [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) que cumplen el predicado proporcionado.

### Observaciones

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ver también

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;) {#verify_1}

Verifica las firmas del documento con una lista de datos de VerifyOptions.

```csharp
public VerificationResult Verify(List<VerifyOptions> verifyOptionsList)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| verifyOptionsList | List`1 | La colección de opciones de verificación de la firma. Instancia de VerifyOptionsCollection. |

### Valor de retorno

Devuelve una instancia de [`VerificationResult`](../../../groupdocs.signature.domain/verificationresult). La propiedad VerificationResult.IsValid devuelve true si el proceso de verificación fue exitoso.

### Observaciones

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ver también

* class [VerificationResult](../../../groupdocs.signature.domain/verificationresult)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Verify(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) {#verify_3}

Verifica las firmas del documento usando todas las opciones de verificación disponibles y filtra los resultados según el predicado especificado. Este método primero busca firmas que coincidan con las opciones de verificación, las filtra usando el predicado y luego verifica solo esas firmas filtradas.

```csharp
public List<BaseSignature> Verify(List<VerifyOptions> verifyOptionsList, 
    Func<BaseSignature, bool> predicate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| verifyOptionsList | List`1 | La colección de opciones de verificación de la firma. Instancia de VerifyOptionsCollection. |
| predicate | Func`2 | El predicado de filtro para determinar qué firmas deben verificarse. |

### Valor de retorno

Devuelve una lista de instancias de [`BaseSignature`](../../../groupdocs.signature.domain/basesignature) que cumplen el predicado proporcionado.

### Observaciones

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

### Ver también

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [VerifyOptions](../../../groupdocs.signature.options/verifyoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
