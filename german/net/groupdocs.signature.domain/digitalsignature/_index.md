---
title: "DigitalSignature"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Enthält Eigenschaften der digitalen Signatur."
type: docs
weight: 150
url: /de/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Enthält Eigenschaften der digitalen Signatur.

```csharp
public class DigitalSignature : BaseSignature
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initialisiert die digitale Signatur mit Standardparametern. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initialisiert die digitale Signatur mit bekannter SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Erstellt eine digitale Signatur mit dem angegebenen Zertifikat. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Erstellt eine digitale Signatur basierend auf dem angegebenen X509‑Store. Das erste Zertifikat aus dem angegebenen Store wird verwendet. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Erstelle digitale Signatur basierend auf dem angegebenen X509 Store und dem Index des Zertifikats. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Liest oder setzt das X509-Zertifikat. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Gibt den benutzerdefinierten Store-Namen des Zertifikats an. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Gibt den Speicherort des Zertifikats an. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Gibt den Store-Namen des Zertifikats an. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Liest oder setzt den Kommentar zum Signierzweck. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Abrufen oder Festlegen des Signatur-Erstellungsdatums. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Ruft das Flag ab, das anzeigt, ob diese Signatur aus dem Dokument gelöscht wurde. Diese Eigenschaft wird nur für Dokumentverlauf‑Logeinträge verwendet, um die Liste gelöschter Signaturen zu behalten. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Gibt die Höhe der Signatur an. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Ruft das Flag ab oder legt es fest, um anzuzeigen, ob diese Komponente eine Signatur oder Dokumentinhalt ist. Diese Eigenschaft wird mit der Update‑Methode verwendet, um das Element als Signatur (true) oder Dokumentelement (false) festzulegen. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Ist wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Gibt die linke Position der Signatur an. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Ruft das Signatur‑Änderungsdatum ab oder legt es fest. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Gibt die Seite an, auf der die Signatur gefunden wurde. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Eindeutiger Signatur‑Bezeichner, um die Signatur im Dokument über Update‑ oder Delete‑Methoden zu ändern. Diese Eigenschaft wird automatisch gesetzt, nachdem die Signatur‑ oder Such‑Methode aufgerufen wurde. Wenn diese Eigenschaft vorher gespeichert wurde, kann sie manuell gesetzt werden, um die Signatur zu manipulieren. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Gibt den Typ der Signatur an. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Liest oder setzt die Zeit, zu der das Dokument signiert wurde. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Liest den Fingerabdruck eines Zertifikats. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Gibt die obere Position der Signatur an. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Gibt die Breite der Signatur an. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES-Typ [`XAdESType`](./xadestype). Standardwert ist None (XAdES ist deaktiviert). In diesem Moment wird der XAdES-Signaturtyp nur für Tabellenkalkulationsdokumente unterstützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Klone Barcode-Signatur-Instanz. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen. |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Überschreibt die GetHashCode-Methode. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Lade digitale Signaturen aus allen System-X509-Zertifikatsstores. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Lade digitale Signaturen aus einem Zertifikatspeicher. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Lade digitale Signaturen aus einem Zertifikatspeicher. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Lade digitale Signaturen aus einem digitalen Zertifikatspeicher, der an einem bestimmten Ort abgelegt ist. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Lade digitale Signaturen aus einem digitalen Zertifikatspeicher, der an einem bestimmten Ort abgelegt ist. |

### Siehe auch

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
