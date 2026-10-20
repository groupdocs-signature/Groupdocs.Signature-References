---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "GroupDocs.Signature für .NET API-Referenz"
description: "Der Namensraum bietet Erweiterungen für Signaturdarstellungen und zusätzliche Funktionalität."
type: docs
weight: 30
url: /de/net/groupdocs.signature.domain.extensions/
---
Der Namensraum bietet Erweiterungen für Signaturdarstellungen und zusätzliche Funktionalität.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Address](./address) | Stellt eine Adresse für den Kontakt dar. |
| [Brush](./brush) | Stellt die Basisklasse für verschiedene Pinsel dar. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Stellt eine Kryptowährungstransaktion (Empfang oder Versand) für QR-Code dar. |
| [DigitalVBA](./digitalvba) | Stellt eine digitale Signatur für VBA-Projekte von Tabellenkalkulationen dar. Sie ermöglicht das Signieren von VBA-Projekten in bestimmten Tabellenkalkulations-Dokumentformaten wie Xlsm oder Xltm. Wenn mehrere DigitalVBA-Erweiterungen zu DigitalSignOptions.Extensions hinzugefügt werden, ist nur die erste an der Dokumentensignatur beteiligt. |
| [Email](./email) | Stellt das E‑Mail-Format für QR-Code dar. |
| [EPC](./epc) | Stellt den Quick Response Code des European Payments Council dar. |
| [Event](./event) | Stellt die Standard‑QR‑Code‑Ereignisdaten dar. |
| [FormatAttribute](./formatattribute) | Weist die Serialisierung von Objekten an, das Mitglied mit dem angegebenen Namen und Format zu serialisieren. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Klasse zum Speichern kombinierter HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-Daten mit primären und sekundären Dateneinheiten. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Klasse zum Speichern primärer HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-Daten. |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Klasse zum Speichern sekundärer und zusätzlicher HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-Daten. |
| [HIBCPASData](./hibcpasdata) | Klasse zum Kodieren und Dekodieren des in den HIBC PAS‑Code eingebetteten Textes. |
| [HIBCPASRecord](./hibcpasrecord) | Klasse zum Speichern eines HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard)-Datensatzes. |
| [LinearGradientBrush](./lineargradientbrush) | Stellt einen linearen Farbverlauf‑Pinsel dar. |
| [Mailmark2D](./mailmark2d) | Klasse zum Kodieren und Dekodieren des in den Royal Mail 2D Mailmark eingebetteten Textes. |
| [MaxiCodeMode2](./maxicodemode2) | Klasse zum Kodieren und Dekodieren des in den MaxiCode‑Code für Modi eingebetteten Textes. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Klasse zum Kodieren und Dekodieren der Standard‑Zweitnachricht für MaxiCode‑Strichcode. |
| [MeCard](./mecard) | Stellt die standardmäßigen Kontaktdaten des MeCard-Formats dar. |
| [RadialGradientBrush](./radialgradientbrush) | Stellt einen radialen Farbverlauf-Pinsel dar. |
| [SignatureExtension](./signatureextension) | Stellt die Basisklasse für Signatur-Erweiterungen dar. |
| [SkipSerializationAttribute](./skipserializationattribute) | Weist die Serialisierung an, das Mitglied zu überspringen. |
| [SMS](./sms) | Stellt Details des SMS-Kurznachrichtendienstes dar. |
| [SolidBrush](./solidbrush) | Stellt einen Vollpinsel dar. Er kann anstelle der Hintergrundfarbeigenschaft verwendet werden. |
| [SpreadsheetPosition](./spreadsheetposition) | Definiert die Signaturposition für Tabellenkalkulationsdokumente. |
| [SwissAddress](./swissaddress) | Stellt die Adresse des Gläubigers oder Schuldners dar. Sie können entweder Straße, Hausnummer, Postleitzahl und Ort (strukturierter Adresstyp) oder Adresszeile 1 und 2 (kombinierter Adresselementtyp) festlegen. |
| [SwissQR](./swissqr) | Klasse zum Kodieren und Dekodieren des in den SwissQR-Code eingebetteten Textes. |
| [SymmetricEncryption](./symmetricencryption) | Implementiert standardmäßige symmetrische Algorithmen zur Datenverschlüsselung mit einem einzelnen Schlüssel und einer Passphrase (Salt). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Weist die Serialisierung von Instanzen an, die Objekt-Serialisierungszeichenfolge zu verschlüsseln/entschlüsseln. |
| [TextShadow](./textshadow) | Stellt Eigenschaften des Textschattens für Textsignaturen dar. Das Ergebnis kann je nach Signaturtyp und Dokumentformat variieren. TextShadow wird für die Verwendung mit der TextAlsImage‑Signatur für alle unterstützten Dokumenttypen empfohlen, ebenso für einfache TextSignature und TextSignature als Wasserzeichen für Tabellen (.xslx) und Präsentationen (.pptx). Eine einfache TextSignature für Words (.docx) wird ebenfalls empfohlen, hat jedoch eingeschränkte Funktionalität. |
| [TextureBrush](./texturebrush) | Stellt einen Texturpinsel dar. |
| [VCard](./vcard) | Stellt die Kontaktdaten des Standards für elektronische Visitenkarten dar. |
| [WiFi](./wifi) | Stellt Details zur WiFi-Netzwerkverbindung dar. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDataEncryption](./idataencryption) | Verschlüsselungs‑Schnittstelle, die Methoden zum Kodieren und Dekodieren von Objekten bereitstellt. |
| [IDataSerializer](./idataserializer) | Serialisierungs‑Schnittstelle, die Methoden zur Objektserialisierung und -deserialisierung bereitstellt. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Stellt den Kryptowährungstyp dar. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Kodierungsmodus des DataMatrix‑Encoders, standardmäßig Auto |
| [HIBCLICDateFormat](./hibclicdateformat) | Gibt die verschiedenen Datumsformattypen für HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code) an. |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Gibt die HIBC PAS-Datenstandorttypen an. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [HIBCPASDataType](./hibcpasdatatype) | Gibt die verschiedenen Datentypen des HIBC PAS-Datensatzes an. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [Mailmark2DType](./mailmark2dtype) | Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Stellt den Typ eines symmetrischen Verschlüsselungsalgorithmus dar. |
| [WiFiEncryptionType](./wifiencryptiontype) | Stellt den WiFi‑Verschlüsselungstyp dar. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
