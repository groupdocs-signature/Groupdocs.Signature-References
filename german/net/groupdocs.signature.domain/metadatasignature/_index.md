---
title: MetadataSignature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Enthält MetadatenSignatureigenschaften.
type: docs
weight: 590
url: /de/net/groupdocs.signature.domain/metadatasignature/
---
## MetadataSignature class

Enthält Metadaten-Signatureigenschaften.

```csharp
public abstract class MetadataSignature : BaseSignature
```

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
| override [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone_1)() | Instanz der Metadaten-Signatur klonen. |
| virtual [Clone](../../groupdocs.signature.domain/metadatasignature/clone#clone)(object) | Instanz der Metadaten-Signatur mit dem angegebenen Wert klonen. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | Überschreibt die Equals-Methode, um Signatureigenschaften zu vergleichen |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata)() | Objekt aus Metadaten-Signaturwert über Deserialisierung abrufen. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata#getdata_1)(IDataEncryption) | Objekt aus Metadaten-Signaturtext über Deserialisierung abrufen. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | überschreibt die GetHashCode-Methode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | Konvertiert in einen booleschen Wert. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime)() | Konvertiert in DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime#todatetime_1)(IFormatProvider) | Konvertiert in DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal)() | Konvertiert in Dezimalzahl. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal#todecimal_1)(IFormatProvider) | Konvertiert in Dezimalzahl. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble)() | Konvertiert in Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble#todouble_1)(IFormatProvider) | Konvertiert in Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | Konvertiert in Ganzzahl. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle)() | Konvertiert in Float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle#tosingle_1)(IFormatProvider) | Konvertiert in Float. |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring)() | Konvertiert in String mit override ToString() method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_1)(string) | Konvertiert in eine Zeichenfolge mit dem angegebenen Format |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring#tostring_2)(string, IFormatProvider) | Konvertiert in eine Zeichenfolge mit dem angegebenen Format |

### Siehe auch

* class [BaseSignature](../basesignature)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
