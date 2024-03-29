---
title: TextShadow
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Repräsentiert Textschatteneigenschaften für Textsignaturen. Das Ergebnis kann je nach Signaturtyp und Dokumentformat variieren. TextShadow wird für die Verwendung mit TextAsImageSignatur für alle unterstützten Dokumenttypen empfohlen auch mit einfacher TextSignatur und TextSignatur als Wasserzeichen für Tabellenkalkulationen  .xslx und Präsentationen .pptx. Simple TextSignature for Words .docx wird ebenfalls empfohlen hat aber eingeschränkte Funktionalität.
type: docs
weight: 400
url: /de/net/groupdocs.signature.domain.extensions/textshadow/
---
## TextShadow class

Repräsentiert Textschatteneigenschaften für Textsignaturen. Das Ergebnis kann je nach Signaturtyp und Dokumentformat variieren. TextShadow wird für die Verwendung mit TextAsImage-Signatur für alle unterstützten Dokumenttypen empfohlen, auch mit einfacher TextSignatur und TextSignatur als Wasserzeichen für Tabellenkalkulationen ( .xslx) und Präsentationen (.pptx). Simple TextSignature for Words (.docx) wird ebenfalls empfohlen, hat aber eingeschränkte Funktionalität.

```csharp
public class TextShadow : SignatureExtension
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextShadow](textshadow)() | Erstellt TextShadow mit Standardoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../groupdocs.signature.domain.extensions/textshadow/angle) { get; set; } | Ermittelt oder legt den Winkel zum Platzieren des Schattens relativ zum Text fest. Der Standardwert ist 0. |
| [Blur](../../groupdocs.signature.domain.extensions/textshadow/blur) { get; set; } | Ruft die Unschärfe des Schattens ab oder legt sie fest. Der Standardwert ist 4. |
| [Color](../../groupdocs.signature.domain.extensions/textshadow/color) { get; set; } | Ruft die Farbe des Schattens ab oder legt sie fest. Der Standardwert ist Schwarz. |
| [Distance](../../groupdocs.signature.domain.extensions/textshadow/distance) { get; set; } | Ermittelt oder legt den Abstand vom Text zum Schatten fest. Der Standardwert ist 1. |
| [Transparency](../../groupdocs.signature.domain.extensions/textshadow/transparency) { get; set; } | Ruft die Transparenz des Schattens ab oder legt sie fest. Der Standardwert ist 0. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | Ruft eine Kopie dieses Objekts ab. |

### Siehe auch

* class [SignatureExtension](../signatureextension)
* namensraum [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
