---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "GroupDocs.Signature för .NET API-referens"
description: "Namnrymden tillhandahåller tillägg för signaturutseenden och ytterligare funktionalitet."
type: docs
weight: 30
url: /sv/net/groupdocs.signature.domain.extensions/
---
Namnrymden tillhandahåller tillägg för signaturutseenden och ytterligare funktionalitet.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Address](./address) | Representerar adress för kontakt. |
| [Brush](./brush) | Representerar basklass för olika penslar. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Representerar kryptovalutaöverföring (mottagning eller sändning) för QR-kod. |
| [DigitalVBA](./digitalvba) | Representerar digital signatur för kalkylblads‑VBA‑projekt. Den ger möjlighet att signera VBA‑projekt i specifika kalkylbladsdokumentformat som Xlsm eller Xltm. Om flera DigitalVBA‑tillägg läggs till i DigitalSignOptions.Extensions används endast det första vid dokumentsignering. |
| [Email](./email) | Representerar e‑postformat för QR‑kod. |
| [EPC](./epc) | Representerar European Payments Council Quick Response Code. |
| [Event](./event) | Representerar standarddetaljer för QR‑Code‑händelse. |
| [FormatAttribute](./formatattribute) | Instruktioner för objektserialisering att serialisera medlemmen med det angivna namnet och formatet. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Klass för lagring av HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) kombinerad data med primära och sekundära dataenheter. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Klass för lagring av HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) primärdata. |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Klass för lagring av HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) sekundär och ytterligare data. |
| [HIBCPASData](./hibcpasdata) | Klass för kodning och avkodning av text inbäddad i HIBC PAS‑koden. |
| [HIBCPASRecord](./hibcpasrecord) | Klass för lagring av HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard)-post. |
| [LinearGradientBrush](./lineargradientbrush) | Representerar linjär gradientpensel. |
| [Mailmark2D](./mailmark2d) | Klass för kodning och avkodning av text inbäddad i Royal Mail 2D Mailmark. |
| [MaxiCodeMode2](./maxicodemode2) | Klass för kodning och avkodning av text inbäddad i MaxiCode‑koden för lägen. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Klass för kodning och avkodning av standard andra meddelandet för MaxiCode‑streckkod. |
| [MeCard](./mecard) | Representerar MeCard‑standardkontaktuppgifter. |
| [RadialGradientBrush](./radialgradientbrush) | Representerar en radialgradientpensel. |
| [SignatureExtension](./signatureextension) | Representerar basklass för signaturförlängningar. |
| [SkipSerializationAttribute](./skipserializationattribute) | Instruktion till serialiseringen att hoppa över medlemmen. |
| [SMS](./sms) | Representerar detaljer för SMS-kortmeddelandetjänsten. |
| [SolidBrush](./solidbrush) | Representerar en solid pensel. Den kan användas istället för egenskapen bakgrundsfärg. |
| [SpreadsheetPosition](./spreadsheetposition) | Definierar signaturposition för kalkylbladsdokument. |
| [SwissAddress](./swissaddress) | Representerar adressen för borgenären eller gäldenären. Du kan antingen ange gata, husnummer, postnummer och ort (strukturerad adresstyp) eller adressrad 1 och 2 (kombinerad adresselementtyp). |
| [SwissQR](./swissqr) | Klass för kodning och avkodning av text som är inbäddad i SwissQR-koden. |
| [SymmetricEncryption](./symmetricencryption) | Implementerar standardalgoritmer för symmetrisk kryptering av data med en enda nyckel och lösenfras (salt). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Instruktion till instansernas serialisering att kryptera / dekryptera objektserialiseringssträngen. |
| [TextShadow](./textshadow) | Representerar egenskaper för textskugga för textsignaturer. Resultatet kan variera beroende på signaturtyp och dokumentformat. TextShadow rekommenderas för användning med TextAsImage-signatur för alla stödda dokumenttyper, även med enkel TextSignature och TextSignature som vattenstämpel för kalkylblad (.xslx) och presentationer (.pptx). Enkel TextSignature för Word (.docx) rekommenderas också, men har begränsad funktionalitet. |
| [TextureBrush](./texturebrush) | Representerar en texturpensel. |
| [VCard](./vcard) | Representerar kontaktuppgifter enligt standarden för elektroniska visitkort. |
| [WiFi](./wifi) | Representerar detaljer för WiFi-nätverksanslutning. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDataEncryption](./idataencryption) | Krypteringsgränssnitt för att tillhandahålla metoder för objektkodning och avkodning. |
| [IDataSerializer](./idataserializer) | Serialiseringsgränssnitt för att tillhandahålla metoder för objektserialisering och deserialisering. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Representerar kryptovalutatyp. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | DataMatrix-kodares kodningsläge, standard är Auto. |
| [HIBCLICDateFormat](./hibclicdateformat) | Anger de olika typerna av datumformat för HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Anger HIBC PAS-dataplaceringstyper. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [HIBCPASDataType](./hibcpasdatatype) | Anger de olika datatyperna för HIBC PAS-posten. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [Mailmark2DType](./mailmark2dtype) | 2D Mailmark-typ definierar storleken på Data Matrix-streckkoden. |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Representerar typ av symmetrisk krypteringsalgoritm. |
| [WiFiEncryptionType](./wifiencryptiontype) | Representerar typ av WiFi-kryptering. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
