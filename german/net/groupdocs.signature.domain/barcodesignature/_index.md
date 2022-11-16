---
title: BarcodeSignature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Enthält BarcodeSignatureigenschaften.
type: docs
weight: 20
url: /de/net/groupdocs.signature.domain/barcodesignature/
---
## BarcodeSignature class

Enthält Barcode-Signatureigenschaften.

```csharp
public class BarcodeSignature : BaseSignature
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BarcodeSignature](barcodesignature)(string) | BarcodeSignature-Objekt mit Signaturkennung initialisieren, die nach dem Suchprozess erhalten wurde. Diese eindeutige Kennung wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Dokumentsignatur-Informationsschicht zu finden. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Content](../../groupdocs.signature.domain/barcodesignature/content) { get; } | Gibt den Inhalt des Barcode-Binärdatenbildtyps an[`Format`](./format) . Standardmäßig wird diese Eigenschaft nicht gesetzt. Eigenschaft verwenden[`ReturnContent`](../../groupdocs.signature.options/barcodesearchoptions/returncontent) um diese Funktion zu aktivieren. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signaturerstellungsdatums. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Holen Sie sich das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Protokolleinträge des Dokumentverlaufs verwendet, um die Liste der gelöschten Signaturen zu führen. |
| [EncodeType](../../groupdocs.signature.domain/barcodesignature/encodetype) { get; } | Gibt den Barcode-Codierungstyp an. |
| [Format](../../groupdocs.signature.domain/barcodesignature/format) { get; } | Gibt das Format des Barcode-Signaturbildes an. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Unterschrift an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Flag abrufen oder setzen, um anzugeben, ob diese Komponente eine Signatur oder ein Dokumentinhalt ist. Diese Eigenschaft wird mit der Update-Methode verwendet, um ein Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Unterschrift an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Abrufen oder Festlegen des Änderungsdatums der Signatur. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt an, auf welcher Seitensignatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signaturbezeichner zum Ändern der Signatur im Dokument über die Update- oder Delete-Methoden. Diese Eigenschaft wird automatisch festgelegt, nachdem die Sign- oder Suchmethode aufgerufen wurde. Wenn diese Eigenschaft gespeichert wurde, bevor sie manuell festgelegt werden kann, um die Signatur zu bearbeiten. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Signaturtyp an. |
| [Text](../../groupdocs.signature.domain/barcodesignature/text) { get; } | Gibt den Text des Barcodes an. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Unterschrift an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Unterschrift an. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/barcodesignature/clone)() | Instanz der Barcode-Signatur klonen. |
| override [Equals](../../groupdocs.signature.domain/barcodesignature/equals)(object) | Überschreibt die Equals-Methode, um Signatureigenschaften zu vergleichen |
| override [GetHashCode](../../groupdocs.signature.domain/barcodesignature/gethashcode)() | überschreibt die GetHashCode-Methode |

### Siehe auch

* class [BaseSignature](../basesignature)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->