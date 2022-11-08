---
title: Search
second_title: Référence de l'API GroupDocs.Signature pour .NET
description: Recherche les signatures dans un document parSearchOptionsgroupdocs.signature.options/searchoptions liste.
type: docs
weight: 150
url: /fr/net/groupdocs.signature/signature/search/
---
## Search(List&lt;SearchOptions&gt;) {#search_1}

Recherche les signatures dans un document par[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) liste.

```csharp
public SearchResult Search(List<SearchOptions> searchOptionsList)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| searchOptionsList | List`1 | La collection d'options de recherche. |

### Return_Value

Renvoie une instance de[`SearchResult`](../../../groupdocs.signature.domain/searchresult) avec la liste des signatures trouvées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la recherche de signatures électroniques dans un document à l'aide de GroupDocs.Signature : [Comment rechercher des signatures électroniques dans un document à l'aide de C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* En savoir plus sur la recherche de signatures électroniques en fonction du type de signature électronique : [Cas d'utilisation avancés de la recherche de signatures électroniques avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir également

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SearchOptions) {#search_3}

Recherche les signatures dans un document par[`SearchOptions`](../../../groupdocs.signature.options/searchoptions) options.

```csharp
public List<T> Search<T>(SearchOptions searchOptions)
    where T : BaseSignature
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| searchOptions | SearchOptions | Les possibilités de recherche. |

### Return_Value

Renvoie la liste des signatures trouvées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la recherche de signatures électroniques dans un document à l'aide de GroupDocs.Signature : [Comment rechercher des signatures électroniques dans un document à l'aide de C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* En savoir plus sur la recherche de signatures électroniques en fonction du type de signature électronique : [Cas d'utilisation avancés de la recherche de signatures électroniques avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir également

* class [SearchOptions](../../../groupdocs.signature.options/searchoptions)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Search&lt;T&gt;(SignatureType) {#search_2}

Recherche le type exact de signatures dans le document par[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) valeur.

```csharp
public List<T> Search<T>(SignatureType signatureType)
    where T : BaseSignature
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatureType | SignatureType | Le type de signatures à rechercher. |

### Return_Value

Renvoie la liste des signatures trouvées avec le type exact.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la recherche de signatures électroniques dans un document à l'aide de GroupDocs.Signature : [Comment rechercher des signatures électroniques dans un document à l'aide de C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* En savoir plus sur la recherche de signatures électroniques en fonction du type de signature électronique : [Cas d'utilisation avancés de la recherche de signatures électroniques avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir également

* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

---

## Search(params SignatureType[]) {#search}

Recherche les types de signature spécifiés dans le document en[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) valeur.

```csharp
public SearchResult Search(params SignatureType[] signatureTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| signatureTypes | SignatureType[] | Un ou plusieurs types de signatures à rechercher. |

### Return_Value

Renvoie une instance de[`SearchResult`](../../../groupdocs.signature.domain/searchresult) avec liste des signatures trouvées.

### Remarques

**Apprendre encore plus**

* En savoir plus sur la recherche de signatures électroniques dans un document à l'aide de GroupDocs.Signature : [Comment rechercher des signatures électroniques dans un document à l'aide de C #](https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document)
* En savoir plus sur la recherche de signatures électroniques en fonction du type de signature électronique : [Cas d'utilisation avancés de la recherche de signatures électroniques avec GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Searching)

### Voir également

* class [SearchResult](../../../groupdocs.signature.domain/searchresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* espace de noms [GroupDocs.Signature](../../signature)
* Assemblée [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
