---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Inizializza la firma digitale PDF senza certificato."
type: docs
weight: 10
url: /it/net/groupdocs.signature.domain/pdfdigitalsignature/pdfdigitalsignature/
---
## PdfDigitalSignature() {#constructor}

Inizializza la firma digitale PDF senza certificato.

```csharp
public PdfDigitalSignature()
```

### Vedi anche

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## PdfDigitalSignature(X509Store) {#constructor_2}

Inizializza la firma digitale PDF basata sullo store X509 specificato. Verrà utilizzato il primo certificato dallo store specificato.

```csharp
public PdfDigitalSignature(X509Store store)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| archivio | X509Store | archivio X509. |

### Vedi anche

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## PdfDigitalSignature(X509Store, int) {#constructor_3}

Crea una firma digitale PDF basata sullo store X509 specificato e sull'indice del certificato.

```csharp
public PdfDigitalSignature(X509Store store, int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| archivio | X509Store | archivio X509. |
| indice | Int32 | Indice del certificato. |

### Vedi anche

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## PdfDigitalSignature(X509Certificate2) {#constructor_1}

Crea una firma digitale PDF con il certificato specificato.

```csharp
public PdfDigitalSignature(X509Certificate2 certificate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificato | X509Certificate2 | certificato X509. |

### Vedi anche

* class [PdfDigitalSignature](../../pdfdigitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
