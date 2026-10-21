---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "GroupDocs.Signature for .NET API-referentie"
description: "De naamruimte biedt extensies voor handtekeningweergaven en extra functionaliteit."
type: docs
weight: 30
url: /nl/net/groupdocs.signature.domain.extensions/
---
De naamruimte biedt extensies voor handtekeningweergaven en extra functionaliteit.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Address](./address) | Stelt een adres voor contact weer. |
| [Brush](./brush) | Stelt de basisklasse voor verschillende penselen voor. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Stelt een cryptovaluta-overdracht (ontvangen of verzenden) voor QR-code weer. |
| [DigitalVBA](./digitalvba) | Stelt een digitale handtekening voor Spreadsheets VBA-projecten weer. Het biedt de mogelijkheid om een VBA-project te ondertekenen in specifieke Spreadsheets-documentformaten zoals Xlsm of Xltm. Als meerdere DigitalVBA-extensies worden toegevoegd aan DigitalSignOptions.Extensions, wordt alleen de eerste gebruikt bij het ondertekenen van het document. |
| [Email](./email) | Stelt een e-mailformaat voor QR-code weer. |
| [EPC](./epc) | Stelt de European Payments Council Quick Response Code weer. |
| [Event](./event) | Stelt standaard QR-code‑evenementdetails weer. |
| [FormatAttribute](./formatattribute) | Instrueert de serialisatie van objecten om het lid met de opgegeven naam en indeling te serialiseren. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Klasse voor het opslaan van gecombineerde HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-gegevens met primaire en secundaire data‑entiteiten. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Klasse voor het opslaan van primaire HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-gegevens. |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Klasse voor het opslaan van secundaire en aanvullende HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-gegevens. |
| [HIBCPASData](./hibcpasdata) | Klasse voor het coderen en decoderen van de in de HIBC PAS-code ingebedde tekst. |
| [HIBCPASRecord](./hibcpasrecord) | Klasse voor het opslaan van een HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard)-record. |
| [LinearGradientBrush](./lineargradientbrush) | Stelt een lineaire gradiëntpenseel voor. |
| [Mailmark2D](./mailmark2d) | Klasse voor het coderen en decoderen van de in de Royal Mail 2D Mailmark ingebedde tekst. |
| [MaxiCodeMode2](./maxicodemode2) | Klasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst voor modi. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Klasse voor het coderen en decoderen van het standaard tweede bericht voor MaxiCode-barcode. |
| [MeCard](./mecard) | Stelt de MeCard-standaardcontactgegevens weer. |
| [RadialGradientBrush](./radialgradientbrush) | Stelt een radiale gradientkwast voor. |
| [SignatureExtension](./signatureextension) | Stelt de basisklasse voor handtekeningextensies voor. |
| [SkipSerializationAttribute](./skipserializationattribute) | Instrueert de serialisatie om het lid over te slaan. |
| [SMS](./sms) | Stelt de details van de SMS-kortberichtendienst voor. |
| [SolidBrush](./solidbrush) | Stelt een effen kwast voor. Het kan in plaats van de eigenschap achtergrondkleur worden gebruikt. |
| [SpreadsheetPosition](./spreadsheetposition) | Definieert de handtekeningpositie voor Spreadsheet-documenten. |
| [SwissAddress](./swissaddress) | Stelt het adres van de crediteur of schuldenaar voor. U kunt ofwel straat, huisnummer, postcode en plaats (gestructureerd adrestype) instellen, of adresregel 1 en 2 (gecombineerd adreselementtype). |
| [SwissQR](./swissqr) | Klasse voor het coderen en decoderen van de in de SwissQR-code ingebedde tekst. |
| [SymmetricEncryption](./symmetricencryption) | Implementeert standaard symmetrische algoritmen voor gegevensversleuteling met één sleutel en wachtwoordzin (zout). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Instrueert de serialisatie van instanties om de objectserialisatiestring te versleutelen / ontsleutelen. |
| [TextShadow](./textshadow) | Stelt de eigenschappen van tekstschaduw voor teksthandtekeningen voor. Het resultaat kan variëren afhankelijk van het type handtekening en het documentformaat. TextShadow wordt aanbevolen voor gebruik met TextAsImage-handtekening voor alle ondersteunde documenttypen, ook met eenvoudige TextSignature en TextSignature als watermerk voor Spreadsheets (.xslx) en Presentaties (.pptx). Een eenvoudige TextSignature voor Words (.docx) wordt ook aanbevolen, maar heeft beperkte functionaliteit. |
| [TextureBrush](./texturebrush) | Stelt een textuurkwast voor. |
| [VCard](./vcard) | Stelt de contactgegevens van de standaard Electronic Business Card voor. |
| [WiFi](./wifi) | Stelt de details van de WiFi-netwerkverbinding voor. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IDataEncryption](./idataencryption) | Versleutelingsinterface om methoden voor objectcodering en -decodering te bieden. |
| [IDataSerializer](./idataserializer) | Serialisatie‑interface om methoden voor objectserialisatie en -deserialisatie te bieden. |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Stelt het type cryptocurrency voor. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Coderingsmodus van de DataMatrix-encoder, standaard op Auto. |
| [HIBCLICDateFormat](./hibclicdateformat) | Specificeert de verschillende typen datumformaten voor HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Specificeert HIBC PAS-gegevenslocatietypen. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [HIBCPASDataType](./hibcpasdatatype) | Specificeert de verschillende gegevenstypen van een HIBC PAS-record. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [Mailmark2DType](./mailmark2dtype) | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Stelt het type symmetrisch versleutelingsalgoritme voor. |
| [WiFiEncryptionType](./wifiencryptiontype) | Stelt het type WiFi-versleuteling voor. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
