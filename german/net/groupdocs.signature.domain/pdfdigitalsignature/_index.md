---
title: PdfDigitalSignature
second_title: GroupDocs.Signature für .NET-API-Referenz
description: Enthält Eigenschaften der digitalen PdfSignatur.
type: docs
weight: 660
url: /de/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Enthält Eigenschaften der digitalen Pdf-Signatur.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Digitale PDF-Signatur ohne Zertifikat initialisieren. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Erstellen Sie eine digitale Pdf-Signatur mit dem angegebenen Zertifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialisiert die digitale Pdf-Signatur basierend auf dem angegebenen X509-Speicher. Das erste Zertifikat aus dem angegebenen Speicher wird verwendet. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Erstellen Sie eine digitale Pdf-Signatur basierend auf dem angegebenen X509-Speicher und dem Index des Zertifikats. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Ruft das X509-Zertifikat ab oder legt es fest. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Gibt den Speicherort des Zertifikats an |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Gibt den Speichernamen des Zertifikats an. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Ruft den Kommentar zum Signierungszweck ab oder legt ihn fest. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Vom Unterzeichner bereitgestellte Informationen, damit ein Empfänger den Unterzeichner kontaktieren kann, um die Signatur zu überprüfen, z. B. eine Telefonnummer. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signaturerstellungsdatums. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Holen Sie sich das Flag, das angibt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Protokolleinträge des Dokumentverlaufs verwendet, um die Liste der gelöschten Signaturen zu führen. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Unterschrift an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Flag abrufen oder setzen, um anzugeben, ob diese Komponente eine Signatur oder ein Dokumentinhalt ist. Diese Eigenschaft wird mit der Update-Methode verwendet, um ein Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Bleibt wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Der CPU-Hostname oder der physische Standort der Signatur. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Abrufen oder Festlegen des Änderungsdatums der Signatur. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt an, auf welcher Seitensignatur gefunden wurde. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Der Grund für die Unterzeichnung, z. B. (Ich stimme zuРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Ein-/Ausblenden von Signatureigenschaften erzwingen. Falls ShowProperties wahr ist, hat das Feld signature ein vordefiniertes Darstellungsformat Digital signiert von {[`ContactInfo`](./contactinfo)} Datum: {Datum} Grund: {[`Reason`](./reason)} Standort: {[`Location`](./location) } ShowProperties ist standardmäßig wahr. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signaturbezeichner zum Ändern der Signatur im Dokument über die Update- oder Delete-Methoden. Diese Eigenschaft wird automatisch festgelegt, nachdem die Sign- oder Suchmethode aufgerufen wurde. Wenn diese Eigenschaft gespeichert wurde, bevor sie manuell festgelegt werden kann, um die Signatur zu bearbeiten. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Signaturtyp an. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Ruft die Uhrzeit ab, zu der das Dokument signiert wurde, oder legt sie fest. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Ruft den Fingerabdruck eines Zertifikats ab. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Zeitstempel für digitale PDF-Signatur. Standardwert ist null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Unterschrift an. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Art der digitalen PDF-Signatur. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Unterschrift an. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-Typ[`XAdESType`](../digitalsignature/xadestype) . Der Standardwert ist „None“ (XAdES ist deaktiviert). Derzeit wird der XAdES-Signaturtyp nur für Spreadsheet-Dokumente unterstützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Instanz der Barcode-Signatur klonen. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Überschreibt die Equals-Methode, um Signatureigenschaften zu vergleichen |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | überschreibt die GetHashCode-Methode |

### Siehe auch

* class [DigitalSignature](../digitalsignature)
* namensraum [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* Montage [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
