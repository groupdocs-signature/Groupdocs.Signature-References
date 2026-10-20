---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Enthält Eigenschaften der Pdf-Metadaten-Signatur."
type: docs
weight: 860
url: /de/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

Enthält Eigenschaften der Pdf-Metadaten-Signatur.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | Erstellt eine Pdf-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | Erstellt eine Pdf-Metadaten-Signatur mit vordefinierten Werten |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | Erstellt eine Pdf-Metadaten-Signatur mit vordefinierten Werten |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signatur-Erstellungsdatums. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ruft die Implementierung des [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-Interfaces ab oder legt sie fest, um die Signaturwert‑Eigenschaften zu kodieren und zu dekodieren. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ruft das Flag ab, das anzeigt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Dokumentverlauf‑Logeinträge verwendet, um die Liste gelöschter Signaturen zu behalten. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Signatur an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ruft das Flag ab oder legt es fest, um anzuzeigen, ob diese Komponente eine Signatur oder Dokumentinhalt ist. Diese Eigenschaft wird mit der Update‑Methode verwendet, um das Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ruft das Signatur‑Änderungsdatum ab oder legt es fest. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Gibt den eindeutigen Metadaten‑Namen an. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt die Seite an, auf der die Signatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signatur‑Bezeichner, um die Signatur im Dokument über Update‑ oder Delete‑Methoden zu ändern. Diese Eigenschaft wird automatisch gesetzt, nachdem die Signatur‑ oder Such‑Methode aufgerufen wurde. Wenn diese Eigenschaft vorher gespeichert wurde, kann sie manuell gesetzt werden, um die Signatur zu manipulieren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Typ der Signatur an. |
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | Das Präfix‑Tag des Pdf-Metadaten‑Signaturnamens. Standardmäßig ist diese Eigenschaft auf "xmp" gesetzt. Mögliche Werte sind |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Signatur an. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Gibt den Metadaten‑Werttyp an. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Gibt das Metadatenobjekt an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Signatur an. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | Klone Metadata Signature-Instanz. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | Klone Pdf Metadata Signature-Instanz mit dem angegebenen Wert. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Erhalte das Objekt aus dem Metadata Signature Value nach der Deserialisierung. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Erhalte das Objekt aus dem Metadata Signature Text nach der Deserialisierung. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | Überschreibt die GetHashCode-Methode. |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Konvertiert zu booleschem Wert. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Konvertiert zu DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Konvertiert zu DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Konvertiert zu Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Konvertiert zu Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Konvertiert zu Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Konvertiert zu Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Konvertiert zu Integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Konvertiert zu Float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Konvertiert zu Float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | Konvertiert zu String mit überschreibender ToString()-Methode. |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Konvertiert zu String mit angegebenem Format. |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | Konvertiert zu String mit angegebenem Format. |

### Siehe auch

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
