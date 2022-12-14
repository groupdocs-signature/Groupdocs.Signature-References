---
title: PreviewOptions
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Initialisiert das PreviewOptionsObjekt.
type: docs
weight: 10
url: /de/net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, params int[]) {#constructor_1}

Initialisiert das PreviewOptions-Objekt.

```csharp
public PreviewOptions(CreatePageStream createPageStream, params int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Delegat, der die Methode zum Erstellen des Ausgabeseitenvorschau-Streams definiert. |
| pageNumbers | Int32[] | Gewünschte Seitenzahlen |

### Siehe auch

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Signature.Options](../../previewoptions)
* Montage [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, params int[]) {#constructor}

Initialisiert das PreviewOptions-Objekt.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    params int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Delegat, der die Methode zum Erstellen des Ausgabeseitenvorschau-Streams definiert. |
| releasePageStream | ReleasePageStream | Delegat, der die Methode zum Freigeben des Ausgabeseiten-Vorschaustreams definiert. |
| pageNumbers | Int32[] | Gewünschte Seitenzahlen |

### Siehe auch

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Signature.Options](../../previewoptions)
* Montage [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
