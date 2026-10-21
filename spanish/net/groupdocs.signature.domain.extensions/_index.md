---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "El espacio de nombres proporciona extensiones para la apariencia de firmas y funcionalidad adicional."
type: docs
weight: 30
url: /es/net/groupdocs.signature.domain.extensions/
---
El espacio de nombres proporciona extensiones para la apariencia de firmas y funcionalidad adicional.

## Clases

| Clase | Descripción |
| --- | --- |
| [Address](./address) | Representa la dirección para el contacto. |
| [Brush](./brush) | Representa la clase base para varios pinceles. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Representa la transferencia de criptomoneda (recepción o envío) para QR-Code. |
| [DigitalVBA](./digitalvba) | Representa la firma digital para proyectos VBA de Spreadsheets. Proporciona la capacidad de firmar el proyecto VBA en formatos específicos de documentos de Spreadsheets como Xlsm o Xltm. Si se añaden varias extensiones DigitalVBA a DigitalSignOptions.Extensions, solo la primera participa en la firma del documento. |
| [Email](./email) | Representa el formato de correo electrónico para QR-Code. |
| [EPC](./epc) | Representa el Quick Response Code del European Payments Council. |
| [Event](./event) | Representa los detalles estándar del evento QR-Code. |
| [FormatAttribute](./formatattribute) | Indica a la serialización de objetos que serialice el miembro con el nombre y formato especificados. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Clase para almacenar datos combinados HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) con entidades de datos primarias y secundarias. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Clase para almacenar datos primarios HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Clase para almacenar datos secundarios y adicionales HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCPASData](./hibcpasdata) | Clase para codificar y decodificar el texto incrustado en el código HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord) | Clase para almacenar el registro HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard). |
| [LinearGradientBrush](./lineargradientbrush) | Representa un pincel de degradado lineal. |
| [Mailmark2D](./mailmark2d) | Clase para codificar y decodificar el texto incrustado en el Royal Mail 2D Mailmark. |
| [MaxiCodeMode2](./maxicodemode2) | Clase para codificar y decodificar el texto incrustado en el código MaxiCode para modos. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Clase para codificar y decodificar el segundo mensaje estándar para el código de barras MaxiCode. |
| [MeCard](./mecard) | Representa los detalles de contacto estándar MeCard. |
| [RadialGradientBrush](./radialgradientbrush) | Representa un pincel de degradado radial. |
| [SignatureExtension](./signatureextension) | Representa la clase base para extensiones de firmas. |
| [SkipSerializationAttribute](./skipserializationattribute) | Indica a la serialización que omita el miembro. |
| [SMS](./sms) | Representa los detalles del servicio de mensajes cortos SMS. |
| [SolidBrush](./solidbrush) | Representa un pincel sólido. Podría usarse en lugar de la propiedad de color de fondo. |
| [SpreadsheetPosition](./spreadsheetposition) | Define la posición de la firma para documentos de hoja de cálculo. |
| [SwissAddress](./swissaddress) | Representa la dirección del acreedor o deudor. Puede establecer la calle, número, código postal y localidad (tipo de dirección estructurada) o la línea de dirección 1 y 2 (tipo de elementos de dirección combinados). |
| [SwissQR](./swissqr) | Clase para codificar y decodificar el texto incrustado en el código SwissQR. |
| [SymmetricEncryption](./symmetricencryption) | Implementa algoritmos simétricos estándar para el cifrado de datos con clave única y frase de paso (sal). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Indica a la serialización de instancias que cifre / descifre la cadena de serialización del objeto. |
| [TextShadow](./textshadow) | Representa las propiedades de sombra de texto para firmas de texto. El resultado puede variar según el tipo de firma y el formato del documento. Se recomienda TextShadow para usar con la firma TextAsImage en todos los tipos de documento compatibles, también con TextSignature simple y TextSignature como marca de agua para Hojas de cálculo (.xslx) y Presentaciones (.pptx). TextSignature simple para Word (.docx) también se recomienda, pero tiene funcionalidad limitada. |
| [TextureBrush](./texturebrush) | Representa un pincel de textura. |
| [VCard](./vcard) | Representa los detalles de contacto estándar de la Tarjeta de Visita Electrónica. |
| [WiFi](./wifi) | Representa los detalles de conexión de red WiFi. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IDataEncryption](./idataencryption) | Interfaz de cifrado para proporcionar métodos de codificación y decodificación de objetos. |
| [IDataSerializer](./idataserializer) | Interfaz de serialización para proporcionar métodos de serialización y deserialización de objetos. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Representa el tipo de criptomoneda. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Modo de codificación del codificador DataMatrix, por defecto Auto |
| [HIBCLICDateFormat](./hibclicdateformat) | Especifica los diferentes tipos de formatos de fecha para HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Especifica los tipos de ubicación de datos HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [HIBCPASDataType](./hibcpasdatatype) | Especifica los diferentes tipos de datos del registro HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [Mailmark2DType](./mailmark2dtype) | Tipo de Mailmark 2D define el tamaño del código de barras Data Matrix |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Representa el tipo de algoritmo de cifrado simétrico. |
| [WiFiEncryptionType](./wifiencryptiontype) | Representa el tipo de cifrado WiFi. |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
