---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Enthält Eigenschaften der Pdf-Digitalen Signatur."
type: docs
weight: 840
url: /de/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Enthält Eigenschaften der Pdf-Digitalen Signatur.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initialisiere Pdf Digital Signature ohne Zertifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Erstelle Pdf Digital signature mit angegebenem Zertifikat. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialisiere Pdf Digital Signature basierend auf dem angegebenen X509-Store. Das erste Zertifikat aus dem angegebenen Store wird verwendet. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Erstelle Pdf Digital signature basierend auf dem angegebenen X509-Store und dem Index des Zertifikats. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Liest oder setzt das X509-Zertifikat. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Gibt den benutzerdefinierten Store-Namen des Zertifikats an. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Gibt den Speicherort des Zertifikats an. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Gibt den Store-Namen des Zertifikats an. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Liest oder setzt den Kommentar zum Signierzweck. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Informationen, die vom Unterzeichner bereitgestellt werden, damit ein Empfänger den Unterzeichner kontaktieren kann, um die Signatur zu überprüfen, z. B. eine Telefonnummer. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signatur-Erstellungsdatums. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ruft das Flag ab, das anzeigt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Dokumentverlauf‑Logeinträge verwendet, um die Liste gelöschter Signaturen zu behalten. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Signatur an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ruft das Flag ab oder legt es fest, um anzuzeigen, ob diese Komponente eine Signatur oder Dokumentinhalt ist. Diese Eigenschaft wird mit der Update‑Methode verwendet, um das Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Ist wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | Der CPU-Hostname oder der physische Ort der Signatur. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ruft das Signatur‑Änderungsdatum ab oder legt es fest. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt die Seite an, auf der die Signatur gefunden wurde. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | Der Grund für die Signatur, zum Beispiel (I agreeРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Erzwinge das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties wahr ist, hat das Signaturfeld ein vordefiniertes Anzeigeformat: Digital signiert von {[`ContactInfo`](./contactinfo)} Datum: {Date} Grund: {[`Reason`](./reason)} Ort: {[`Location`](./location)} ShowProperties ist standardmäßig wahr. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signatur‑Bezeichner, um die Signatur im Dokument über Update‑ oder Delete‑Methoden zu ändern. Diese Eigenschaft wird automatisch gesetzt, nachdem die Signatur‑ oder Such‑Methode aufgerufen wurde. Wenn diese Eigenschaft vorher gespeichert wurde, kann sie manuell gesetzt werden, um die Signatur zu manipulieren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Typ der Signatur an. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Liest oder setzt die Zeit, zu der das Dokument signiert wurde. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Liest den Fingerabdruck eines Zertifikats. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Zeitstempel für Pdf digitale Signatur. Standardwert ist null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Signatur an. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Typ der Pdf digitalen Signatur. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Signatur an. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-Typ [`XAdESType`](../digitalsignature/xadestype). Standardwert ist None (XAdES ist deaktiviert). Derzeit wird der XAdES-Signaturtyp nur für Tabellenkalkulationsdokumente unterstützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Klone Barcode-Signatur-Instanz. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Überschreibt die GetHashCode-Methode. |

### Siehe auch

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
