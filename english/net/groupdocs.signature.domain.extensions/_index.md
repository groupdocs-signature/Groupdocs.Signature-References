---
title: GroupDocs.Signature.Domain.Extensions
second_title: GroupDocs.Signature for .NET API Reference
description: The namespace provides extensions for signature appearances and additional functionality.
type: docs
weight: 30
url: /net/groupdocs.signature.domain.extensions/
---
The namespace provides extensions for signature appearances and additional functionality.

## Classes

| Class | Description |
| --- | --- |
| [Address](./address) | Represents address for contact. |
| [Brush](./brush) | Represents base class for various brushes. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Represents Cryptocurrency transfer (receive or send) for QR-Code. |
| [DigitalVBA](./digitalvba) | Represents digital signature for Spreadsheets VBA projects. It provides ability to sign VBA project at specific Spreadsheets document formats like Xlsm or Xltm. If several DigitalVBA extensions are added to DigitalSignOptions.Extensions only first is involved in document signing. |
| [Email](./email) | Represents Email format for QR-Code. |
| [EPC](./epc) | Represents European Payments Council Quick Response Code. |
| [Event](./event) | Represents standard QR-Code Event details. |
| [FormatAttribute](./formatattribute) | Instructs objects serialization to serialize the member with the specified name and format |
| [HIBCLICCombinedData](./hibcliccombineddata) | Class for storing HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) combined data with primary and secondary data entities. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Class for storing HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) primary data. |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Class for storing HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) secondary and additional data. |
| [LinearGradientBrush](./lineargradientbrush) | Represents linear gradient brush. |
| [Mailmark2D](./mailmark2d) | Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark |
| [MeCard](./mecard) | Represents MeCard standard contact details. |
| [RadialGradientBrush](./radialgradientbrush) | Represents radial gradient brush. |
| [SignatureExtension](./signatureextension) | Represents base class for signatures extensions. |
| [SkipSerializationAttribute](./skipserializationattribute) | Instructs the serialization to skip the member. |
| [SMS](./sms) | Represents SMS short message service details. |
| [SolidBrush](./solidbrush) | Represents solid brush. It could be used instead background color property. |
| [SpreadsheetPosition](./spreadsheetposition) | Defines signature position for Spreadsheet documents. |
| [SwissAddress](./swissaddress) | Represents the address of the creditor or debtor. You can either set street, house number, postal code, and town (structured address type) or address line 1 and 2 (combined address elements type). |
| [SwissQR](./swissqr) | Class for encoding and decoding the text embedded in the SwissQR code. |
| [SymmetricEncryption](./symmetricencryption) | Implements standard symmetric algorithms for data encryption with single key and passphrase (salt). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Instructs instances serialization to encrypt / decrypt object serialization string. |
| [TextShadow](./textshadow) | Represents text shadow properties for text signatures. The result may vary depending on the signature type and document format. TextShadow is recommended for using with TextAsImage signature for all supported document types, also with simple TextSignature and TextSignature as watermark for Spreadsheets (.xslx) and Presentations (.pptx). Simple TextSignature for Words (.docx) is recommended too, but has limited functionality. |
| [TextureBrush](./texturebrush) | Represents texture brush. |
| [VCard](./vcard) | Represents Electronic Business Card standard contact details. |
| [WiFi](./wifi) | Represents WiFi network connection details. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IDataEncryption](./idataencryption) | Encryption interface to provide object encoding and decoding methods. |
| [IDataSerializer](./idataserializer) | Serialization interface to provide object serialization and deserialization methods. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Represents Cryptocurrency type. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | DataMatrix encoder's encoding mode, default to Auto |
| [HIBCLICDateFormat](./hibclicdateformat) | Specifies the different types of date formats for HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [Mailmark2DType](./mailmark2dtype) | 2D Mailmark Type defines size of Data Matrix barcode |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Represents symmetric encryption algorithm type. |
| [WiFiEncryptionType](./wifiencryptiontype) | Represents WiFi Encryption type. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
