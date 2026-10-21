---
title: "PdfDigitalSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Inicialice la firma digital PDF sin certificado."
type: docs
weight: 10
url: /es/net/groupdocs.signature.domain/pdfdigitalsignature/pdfdigitalsignature/
---
## PdfDigitalSignature() {#constructor}

Inicialice la firma digital PDF sin certificado.

```csharp
public PdfDigitalSignature()
```

### Ver también

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## PdfDigitalSignature(X509Store) {#constructor_2}

Inicialice la firma digital PDF basada en el almacén X509 especificado. Se usará el primer certificado del almacén especificado.

```csharp
public PdfDigitalSignature(X509Store store)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| almacén | X509Store | Almacén X509. |

### Ver también

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## PdfDigitalSignature(X509Store, int) {#constructor_3}

Cree una firma digital PDF basada en el almacén X509 especificado y el índice del certificado.

```csharp
public PdfDigitalSignature(X509Store store, int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| almacén | X509Store | Almacén X509. |
| índice | Int32 | Índice del certificado. |

### Ver también

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## PdfDigitalSignature(X509Certificate2) {#constructor_1}

Cree una firma digital PDF con el certificado especificado.

```csharp
public PdfDigitalSignature(X509Certificate2 certificate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificado | X509Certificate2 | Certificado X509. |

### Ver también

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
