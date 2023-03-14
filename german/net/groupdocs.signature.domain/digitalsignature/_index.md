---
title: DigitalSignature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Enthält Eigenschaften der digitalen Signatur.
type: docs
weight: 150
url: /de/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Enthält Eigenschaften der digitalen Signatur.

```csharp
public class DigitalSignature : BaseSignature
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Digitale Signatur mit Standardparametern initialisieren. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Digitale Signatur mit bekannter SignatureId initialisieren. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Erstellen Sie eine digitale Signatur mit dem angegebenen Zertifikat. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Digitale Signatur basierend auf dem angegebenen X509-Speicher erstellen. Das erste Zertifikat aus dem angegebenen Speicher wird verwendet. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Erstellen Sie eine digitale Signatur basierend auf dem angegebenen X509-Speicher und dem Index des Zertifikats. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Ruft das X509-Zertifikat ab oder legt es fest. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Gibt den Speicherort des Zertifikats an |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Gibt den Speichernamen des Zertifikats an. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Ruft den Kommentar zum Signierungszweck ab oder legt ihn fest. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signaturerstellungsdatums. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Holen Sie sich das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Protokolleinträge des Dokumentverlaufs verwendet, um die Liste der gelöschten Signaturen zu führen. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Unterschrift an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Flag abrufen oder setzen, um anzugeben, ob diese Komponente eine Signatur oder ein Dokumentinhalt ist. Diese Eigenschaft wird mit der Update-Methode verwendet, um ein Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Bleibt wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Abrufen oder Festlegen des Änderungsdatums der Signatur. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt an, auf welcher Seitensignatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signaturbezeichner zum Ändern der Signatur im Dokument über die Update- oder Delete-Methoden. Diese Eigenschaft wird automatisch festgelegt, nachdem die Sign- oder Suchmethode aufgerufen wurde. Wenn diese Eigenschaft gespeichert wurde, bevor sie manuell festgelegt werden kann, um die Signatur zu bearbeiten. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Signaturtyp an. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Ruft die Uhrzeit ab, zu der das Dokument signiert wurde, oder legt sie fest. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Ruft den Fingerabdruck eines Zertifikats ab. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Unterschrift an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Unterschrift an. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-Typ[`XAdESType`](./xadestype) . Der Standardwert ist „None“ (XAdES ist deaktiviert). Derzeit wird der XAdES-Signaturtyp nur für Spreadsheet-Dokumente unterstützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Instanz der Barcode-Signatur klonen. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Überschreibt die Equals-Methode, um Signatureigenschaften zu vergleichen |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | überschreibt die GetHashCode-Methode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Digitale Signatur aus allen X509-Zertifikatspeichern des Systems laden. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Laden Sie die digitale Signatur aus dem Speicher für übergebene X509-Zertifikate. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Laden Sie die digitale Signatur aus dem Speicher für übergebene X509-Zertifikate. |

### Siehe auch

* class [BaseSignature](../basesignature)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
