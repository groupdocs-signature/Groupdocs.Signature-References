---
title: ImageMetadataSignature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Enthält BildmetadatenSignatureigenschaften.
type: docs
weight: 570
url: /de/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

Enthält Bildmetadaten-Signatureigenschaften.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Erstellt Bildmetadaten-Signatur mit ID und Wert |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signaturerstellungsdatums. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ruft die Implementierung von ab oder legt sie fest[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) Schnittstelle zum Codieren und Decodieren von Signaturwerteigenschaften. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Holen Sie sich das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Protokolleinträge des Dokumentverlaufs verwendet, um die Liste der gelöschten Signaturen zu führen. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | Schreibgeschützter Wert zum Abrufen einer Beschreibung für die Standardbild-Metadatensignatur |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Unterschrift an. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Die Kennung der Bild-Metadaten-Signatur. SieheImageMetadataSignatures Klasse, die eine Standardsignatur mit vordefiniertem ID-Wert enthält. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Flag abrufen oder setzen, um anzugeben, ob diese Komponente eine Signatur oder ein Dokumentinhalt ist. Diese Eigenschaft wird mit der Update-Methode verwendet, um ein Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Abrufen oder Festlegen des Änderungsdatums der Signatur. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Gibt einen eindeutigen Metadatennamen an. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt an, auf welcher Seitensignatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signaturbezeichner zum Ändern der Signatur im Dokument über die Update- oder Delete-Methoden. Diese Eigenschaft wird automatisch festgelegt, nachdem die Sign- oder Suchmethode aufgerufen wurde. Wenn diese Eigenschaft gespeichert wurde, bevor sie manuell festgelegt werden kann, um die Signatur zu bearbeiten. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Signaturtyp an. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Schreibgeschützter Wert zum Abrufen der Größe des Metadatenwerts |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Unterschrift an. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | Gibt den Typ des Metadatenwerts an. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Gibt das Metadatenobjekt an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Unterschrift an. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Instanz der Metadaten-Signatur klonen. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | Instanz der Image-Metadaten-Signatur mit dem angegebenen Wert klonen. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | Überschreibt die Equals-Methode, um Signatureigenschaften zu vergleichen |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Objekt aus Metadaten-Signaturwert über Deserialisierung abrufen. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Objekt aus Metadaten-Signaturtext über Deserialisierung abrufen. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | überschreibt die GetHashCode-Methode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | Konvertiert in einen booleschen Wert. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | Konvertiert in DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konvertiert in DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Konvertiert in Dezimalzahl. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konvertiert in Dezimalzahl. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Konvertiert in Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Konvertiert in Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | Konvertiert in Ganzzahl. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | Konvertiert in lang. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | Konvertiert in Float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konvertiert in Float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | Konvertiert in String mit override ToString() method |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | Konvertiert in eine Zeichenfolge mit dem angegebenen Format |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konvertiert in eine Zeichenfolge mit dem angegebenen Format |

### Siehe auch

* class [MetadataSignature](../metadatasignature)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
