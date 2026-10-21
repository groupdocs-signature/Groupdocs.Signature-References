---
title: "Firmar"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Firma el documento con SignOptionsgroupdocs.signature.options/signoptions y guarda el resultado en un flujo."
type: docs
weight: 160
url: /es/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Firma el documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo de salida del documento. |
| signOptions | SignOptions | Las opciones de la firma. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Firma el documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo con [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefinidos.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo de salida del documento. |
| signOptions | SignOptions | Las opciones de la firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Firma el documento con una colección de [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo de salida del documento. |
| signOptionsList | List`1 | La lista de opciones de firma. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Firma el documento con una colección de [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en un flujo con [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefinidos.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo de salida del documento. |
| signOptionsList | List`1 | La lista de opciones de firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Firma el documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptions | SignOptions | Las opciones de la firma. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Firma el documento con [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefinidos.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptions | SignOptions | Las opciones de la firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Firma el documento con una colección de [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptionsList | List`1 | La lista de opciones de firma. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Firma el documento con una colección de [`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con [`SaveOptions`](../../../groupdocs.signature.options/saveoptions) predefinidos.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptionsList | List`1 | La lista de opciones de firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor de retorno

Devuelve una instancia de [`SignResult`](../../../groupdocs.signature.domain/signresult) con una lista de firmas recién creadas.

### Observaciones

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* More about how eSign documents in C#: [How to eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
