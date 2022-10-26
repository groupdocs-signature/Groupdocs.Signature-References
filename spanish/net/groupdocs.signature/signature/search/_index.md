---
title: Search
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Busca firmas en un documento porSearchOptionsgroupdocs.signature.options/searchoptions lista.
type: docs
weight: 150
url: /es/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Busca firmas en un documento por[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) lista.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| searchOptionsList | List`1 | La colección de opciones de búsqueda. |

### Valor_devuelto

Devuelve instancia de[`SearchResult`](../../../groupdocs.signature.domain/searchresult) con lista de Firmas encontradas.

### Observaciones

**Aprende más**

* Más sobre buscar firmas electrónicas en documentos usando GroupDocs. Firma: [Cómo buscar firmas electrónicas dentro de un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Más información sobre la búsqueda de firmas electrónicas según el tipo de firma electrónica: [Casos de uso avanzado de búsqueda de firmas electrónicas con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Busca firmas en un documento por[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) opciones.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| searchOptions | SearchOptions | Las opciones de búsqueda. |

### Valor_devuelto

Devuelve la lista de firmas encontradas.

### Observaciones

**Aprende más**

* Más sobre buscar firmas electrónicas en documentos usando GroupDocs. Firma: [Cómo buscar firmas electrónicas dentro de un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Más información sobre la búsqueda de firmas electrónicas según el tipo de firma electrónica: [Casos de uso avanzado de búsqueda de firmas electrónicas con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Busca el tipo exacto de firmas en el documento por[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) valor.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatureType | SignatureType | El tipo de firmas a buscar. |

### Valor_devuelto

Devuelve la lista de firmas encontradas con tipo exacto.

### Observaciones

**Aprende más**

* Más sobre buscar firmas electrónicas en documentos usando GroupDocs. Firma: [Cómo buscar firmas electrónicas dentro de un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Más información sobre la búsqueda de firmas electrónicas según el tipo de firma electrónica: [Casos de uso avanzado de búsqueda de firmas electrónicas con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Busca tipos de firma especificados en el documento por[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) valor.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Uno o varios tipos de firmas a buscar. |

### Valor_devuelto

Devuelve instancia de[`SearchResult`](../../../groupdocs.signature.domain/searchresult) con lista de firmas encontradas.

### Observaciones

**Aprende más**

* Más sobre buscar firmas electrónicas en documentos usando GroupDocs. Firma: [Cómo buscar firmas electrónicas dentro de un documento usando C#](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* Más información sobre la búsqueda de firmas electrónicas según el tipo de firma electrónica: [Casos de uso avanzado de búsqueda de firmas electrónicas con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Ver también

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
