---
title: WordProcessingMetadataSignature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Enthält WordProcessing Metadata SignatureEigenschaften.
type: docs
weight: 1040
url: /de/net/groupdocs.signature.domain/wordprocessingmetadatasignature/
---
## WordProcessingMetadataSignature class

Enthält WordProcessing Metadata Signature-Eigenschaften.

```csharp
public sealed class WordProcessingMetadataSignature : MetadataSignature
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor)(string) | Erstellt eine Textverarbeitungs-Metadatensignatur mit vordefiniertem Namen und leerem Wert. |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor_1)(string, object) | Erstellt eine Textverarbeitungs-Metadatensignatur mit vordefinierten Werten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signaturerstellungsdatums. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | Ruft die Implementierung von ab oder legt sie fest[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) Schnittstelle zum Codieren und Decodieren von Signaturwerteigenschaften. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Holen Sie sich das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Protokolleinträge des Dokumentverlaufs verwendet, um die Liste der gelöschten Signaturen zu führen. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Unterschrift an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Flag abrufen oder setzen, um anzugeben, ob diese Komponente eine Signatur oder ein Dokumentinhalt ist. Diese Eigenschaft wird mit der Update-Methode verwendet, um ein Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Unterschrift an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Abrufen oder Festlegen des Änderungsdatums der Signatur. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | Gibt einen eindeutigen Metadatennamen an. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt an, auf welcher Seitensignatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signaturbezeichner zum Ändern der Signatur im Dokument über die Update- oder Delete-Methoden. Diese Eigenschaft wird automatisch festgelegt, nachdem die Sign- oder Suchmethode aufgerufen wurde. Wenn diese Eigenschaft gespeichert wurde, bevor sie manuell festgelegt werden kann, um die Signatur zu bearbeiten. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Signaturtyp an. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Unterschrift an. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | Gibt das Metadatenobjekt an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Unterschrift an. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone_1)() | Instanz der Metadaten-Signatur klonen. |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone)(object) | Clone Words Metadata Signature-Instanz mit dem angegebenen Wert. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Überschreibt die Equals-Methode, um Signatureigenschaften zu vergleichen |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | Objekt aus Metadaten-Signaturwert über Deserialisierung abrufen. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | Objekt aus Metadaten-Signaturtext über Deserialisierung abrufen. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | überschreibt die GetHashCode-Methode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Konvertiert in einen booleschen Wert. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | Konvertiert in DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | Konvertiert in DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Konvertiert in Dezimalzahl. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Konvertiert in Dezimalzahl. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Konvertiert in Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Konvertiert in Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Konvertiert in Ganzzahl. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | Konvertiert in Float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | Konvertiert in Float. |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring)() | Konvertiert in String mit override ToString() method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | Konvertiert in eine Zeichenfolge mit dem angegebenen Format |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konvertiert in eine Zeichenfolge mit dem angegebenen Format |

### Siehe auch

* class [MetadataSignature](../metadatasignature)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
