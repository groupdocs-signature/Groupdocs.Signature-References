---
title: "DigitalSignature"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Inicializa la firma digital con parámetros predeterminados."
type: docs
weight: 10
url: /es/net/groupdocs.signature.domain/digitalsignature/digitalsignature/
---
## DigitalSignature() {#constructor}

Inicializa la firma digital con parámetros predeterminados.

```csharp
public DigitalSignature()
```

### Ver también

* class [DigitalSignature](../../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## DigitalSignature(string) {#constructor_4}

Inicializa la firma digital con SignatureId conocido.

```csharp
public DigitalSignature(string signatureId)
```

### Ver también

* class [DigitalSignature](../../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## DigitalSignature(X509Store) {#constructor_2}

Crea una firma digital basada en el almacén X509 especificado. Se usará el primer certificado del almacén especificado.

```csharp
public DigitalSignature(X509Store store)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| almacén | X509Store | Almacén X509. |

### Ver también

* class [DigitalSignature](../../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## DigitalSignature(X509Store, int) {#constructor_3}

Crea una firma digital basada en el almacén X509 especificado y el índice del certificado.

```csharp
public DigitalSignature(X509Store store, int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| almacén | X509Store | Almacén X509. |
| índice | Int32 | Índice del certificado. |

### Ver también

* class [DigitalSignature](../../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

---

## DigitalSignature(X509Certificate2) {#constructor_1}

Crea una firma digital con el certificado especificado.

```csharp
public DigitalSignature(X509Certificate2 certificate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificado | X509Certificate2 | Certificado X509. |

### Ver también

* class [DigitalSignature](../../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
