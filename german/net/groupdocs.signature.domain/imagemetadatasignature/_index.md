---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Enthält Eigenschaften der Bild-Metadaten-Signatur."
type: docs
weight: 740
url: /de/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Enthält Eigenschaften der Bild-Metadaten-Signatur.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Erstellt Image Metadata Signature mit Id und Wert |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signatur-Erstellungsdatums. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ruft die Implementierung des [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)-Interfaces ab oder legt sie fest, um die Signaturwert‑Eigenschaften zu kodieren und zu dekodieren. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ruft das Flag ab, das anzeigt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Dokumentverlauf‑Logeinträge verwendet, um die Liste gelöschter Signaturen zu behalten. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Nur-Lese-Wert, um die Beschreibung für die Standard-Image-Metadata-Signatur zu erhalten |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Signatur an. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Der Bezeichner der Image Metadata Signatur. Siehe die Klasse ImageMetadataSignatures, die die Standard-Signatur mit vordefiniertem Id-Wert enthält. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ruft das Flag ab oder legt es fest, um anzuzeigen, ob diese Komponente eine Signatur oder Dokumentinhalt ist. Diese Eigenschaft wird mit der Update‑Methode verwendet, um das Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ruft das Signatur‑Änderungsdatum ab oder legt es fest. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Gibt den eindeutigen Metadaten‑Namen an. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt die Seite an, auf der die Signatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signatur‑Bezeichner, um die Signatur im Dokument über Update‑ oder Delete‑Methoden zu ändern. Diese Eigenschaft wird automatisch gesetzt, nachdem die Signatur‑ oder Such‑Methode aufgerufen wurde. Wenn diese Eigenschaft vorher gespeichert wurde, kann sie manuell gesetzt werden, um die Signatur zu manipulieren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Typ der Signatur an. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Nur-Lese-Wert, um die Größe des Metadatenwerts zu erhalten |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Signatur an. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Gibt den Metadaten‑Werttyp an. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Gibt das Metadatenobjekt an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Signatur an. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Klone Metadata Signature-Instanz. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Klont Image Metadata Signature-Instanz mit dem angegebenen Wert. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Erhalte das Objekt aus dem Metadata Signature Value nach der Deserialisierung. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Erhalte das Objekt aus dem Metadata Signature Text nach der Deserialisierung. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | Überschreibt die GetHashCode-Methode. |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Konvertiert zu booleschem Wert. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Konvertiert zu DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konvertiert zu DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Konvertiert zu Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konvertiert zu Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Konvertiert zu Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Konvertiert zu Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Konvertiert zu Integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Konvertiert zu long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Konvertiert zu Float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konvertiert zu Float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Konvertiert zu String mit überschreibender ToString()-Methode. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Konvertiert zu String mit angegebenem Format. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konvertiert zu String mit angegebenem Format. |

### Siehe auch

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
