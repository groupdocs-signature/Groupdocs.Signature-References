---
title: ImageSearchOptions
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Repräsentiert Suchoptionen für Bildsignaturen.
type: docs
weight: 1410
url: /de/net/groupdocs.signature.options/imagesearchoptions/
---
## ImageSearchOptions class

Repräsentiert Suchoptionen für Bildsignaturen.

```csharp
public class ImageSearchOptions : SearchOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageSearchOptions](imagesearchoptions)() | Initialisiert eine neue Instanz der ImageSearchOptions-Klasse mit Standardwerten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Markierung für die Suche auf jeder Dokumentseite. Standardmäßig ist dieser Wert auf true gesetzt. |
| [MaxContentSize](../../groupdocs.signature.options/imagesearchoptions/maxcontentsize) { get; set; } | Für Werte ungleich Null gibt dieses Flag die maximale Größe von Bildern für Suchkriterien an. Standardmäßig ist dieses Flag auf Null gesetzt und wirkt sich nicht auf das Suchergebnis aus. |
| [MinContentSize](../../groupdocs.signature.options/imagesearchoptions/mincontentsize) { get; set; } | Für einen Wert ungleich Null gibt dieses Flag die Mindestgröße von Bildern für Suchkriterien an. Standardmäßig ist dieses Flag auf Null gesetzt und wirkt sich nicht auf das Suchergebnis aus. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ruft die Seitennummer des Dokuments für die Suche ab oder legt sie fest. Der Wert ist optional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Optionen zum Angeben von Seiten für die Signatursuche. |
| [ReturnContent](../../groupdocs.signature.options/imagesearchoptions/returncontent) { get; set; } | Ruft oder setzt ein Flag, um den Bildinhalt der Signatur auf der Dokumentseite zu erfassen. Wenn dieses Flag auf „true“ gesetzt ist, behält der Inhalt der Bildsignatur Rohbilddaten im erforderlichen Format bei[`ReturnContentType`](./returncontenttype) . Standardmäßig ist diese Option deaktiviert. |
| [ReturnContentType](../../groupdocs.signature.options/imagesearchoptions/returncontenttype) { get; set; } | Gibt den Dateityp des zurückgegebenen Inhalts der Bildsignatur an, wenn die ReturnContent-Eigenschaft aktiviert ist. Standardmäßig ist sie auf Null gesetzt. Das bedeutet, Bildinhalte im Originalformat zurückzugeben. Dieses Bildformat ist spezifiziert bei[`Format`](../../groupdocs.signature.domain/imagesignature/format) Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der Bildinhalt im Originalformat zurückgegeben. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag, um nur Signaturen zurückzugeben, die als IsSignature gekennzeichnet sind. Standardmäßig ist der Wert „false“, was bedeutet, dass alle Signaturen zurückgegeben werden, die den angegebenen Kriterien entsprechen. |

### Bemerkungen

**Erfahren Sie mehr**

* Grundlegende Verwendung der Suche nach elektronischer Bildunterschrift von GroupDocs.Signatur: [ So suchen Sie nach Bildsignaturen in einem Dokument](https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures)
* Erweiterte Nutzung der Sucheinstellungen für die elektronische Bildunterschrift mit GroupDocs.Signature: [Erweiterte Verwendung von eSearch-Bildsignaturen in einem Dokument und zusätzliche Einstellungen](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures)

### Siehe auch

* class [SearchOptions](../searchoptions)
* namensraum [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
