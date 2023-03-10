---
title: Sign
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Firma documento conSignOptionsgroupdocs.signature.options/signoptions y guarda el resultado en un stream.
type: docs
weight: 160
url: /es/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

Firma documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en un stream.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo de documentos de salida. |
| signOptions | SignOptions | Las opciones de firma. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

Firma documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) guarda el resultado en una secuencia con predefinido[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo de documentos de salida. |
| signOptions | SignOptions | Las opciones de firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Más información sobre cómo guardar documentos firmados electrónicamente y personalizar el proceso de guardado: [Cómo personalizar documentos firmados electrónicamente al guardarlos usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Firma documento con cobro de[`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en un stream.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo de documentos de salida. |
| signOptionsList | List`1 | La lista de opciones de firma. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Firma documento con cobro de[`SignOptions`](../../../groupdocs.signature.options/signoptions) guarda el resultado en una secuencia con predefinido[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo de documentos de salida. |
| signOptionsList | List`1 | La lista de opciones de firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Más información sobre cómo guardar documentos firmados electrónicamente y personalizar el proceso de guardado: [Cómo personalizar documentos firmados electrónicamente al guardarlos usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

Firma documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptions | SignOptions | Las opciones de firma. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

Firma documento con[`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con predefinido[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptions | SignOptions | Las opciones de firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Más información sobre cómo guardar documentos firmados electrónicamente y personalizar el proceso de guardado: [Cómo personalizar documentos firmados electrónicamente al guardarlos usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Firma documento con cobro de[`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptionsList | List`1 | La lista de opciones de firma. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Firma documento con cobro de[`SignOptions`](../../../groupdocs.signature.options/signoptions) y guarda el resultado en la ruta de archivo especificada con predefinido[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo de salida. |
| signOptionsList | List`1 | La lista de opciones de firma. |
| saveOptions | SaveOptions | Las opciones de guardado. |

### Valor_devuelto

Devuelve instancia de[`SignResult`](../../../groupdocs.signature.domain/signresult) con lista de firmas recién creadas.

### Observaciones

**Aprende más**

* Más información sobre los tipos de firma electrónica admitidos por GroupDocs. Firma: [Tipos de firma electrónica compatibles con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* Más información sobre cómo firmar documentos en C#: [Cómo firmar documentos electrónicamente usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Signing)
* Más información sobre cómo guardar documentos firmados electrónicamente y personalizar el proceso de guardado: [Cómo personalizar documentos firmados electrónicamente al guardarlos usando GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ver también

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
