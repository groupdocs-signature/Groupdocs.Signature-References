---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Это пространство имён предоставляет расширения для внешнего вида подписей и дополнительного функционала."
type: docs
weight: 30
url: /ru/net/groupdocs.signature.domain.extensions/
---
Это пространство имён предоставляет расширения для внешнего вида подписей и дополнительного функционала.

## Классы

| Класс | Описание |
| --- | --- |
| [Address](./address) | Представляет адрес контакта. |
| [Brush](./brush) | Представляет базовый класс для различных кистей. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Представляет перевод криптовалюты (получение или отправка) для QR‑кода. |
| [DigitalVBA](./digitalvba) | Представляет цифровую подпись для проектов VBA в Spreadsheets. Обеспечивает возможность подписать проект VBA в конкретных форматах документов Spreadsheets, таких как Xlsm или Xltm. Если к DigitalSignOptions.Extensions добавлено несколько расширений DigitalVBA, только первое участвует в подписании документа. |
| [Email](./email) | Представляет формат Email для QR‑кода. |
| [EPC](./epc) | Представляет Quick Response Code Совета европейских платежей (European Payments Council). |
| [Event](./event) | Представляет стандартные детали события QR‑кода. |
| [FormatAttribute](./formatattribute) | Указывает сериализацию объектов, чтобы сериализовать член с указанным именем и форматом. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Класс для хранения комбинированных данных HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) с первичными и вторичными сущностями данных. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Класс для хранения первичных данных HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Класс для хранения вторичных и дополнительных данных HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCPASData](./hibcpasdata) | Класс для кодирования и декодирования текста, встроенного в код HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord) | Класс для хранения записи HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard). |
| [LinearGradientBrush](./lineargradientbrush) | Представляет линейную градиентную кисть. |
| [Mailmark2D](./mailmark2d) | Класс для кодирования и декодирования текста, встроенного в 2D Mailmark Royal Mail. |
| [MaxiCodeMode2](./maxicodemode2) | Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Класс для кодирования и декодирования стандартного второго сообщения для штрих‑кода MaxiCode. |
| [MeCard](./mecard) | Представляет стандартные контактные данные MeCard. |
| [RadialGradientBrush](./radialgradientbrush) | Представляет радиальную градиентную кисть. |
| [SignatureExtension](./signatureextension) | Представляет базовый класс для расширений подписей. |
| [SkipSerializationAttribute](./skipserializationattribute) | Указывает сериализации пропустить член. |
| [SMS](./sms) | Представляет детали службы коротких SMS‑сообщений. |
| [SolidBrush](./solidbrush) | Представляет сплошную кисть. Может использоваться вместо свойства цвета фона. |
| [SpreadsheetPosition](./spreadsheetposition) | Определяет позицию подписи для документов электронных таблиц. |
| [SwissAddress](./swissaddress) | Представляет адрес кредитора или должника. Вы можете задать либо улицу, номер дома, почтовый индекс и город (структурированный тип адреса), либо строки адреса 1 и 2 (объединённый тип элементов адреса). |
| [SwissQR](./swissqr) | Класс для кодирования и декодирования текста, встроенного в код SwissQR. |
| [SymmetricEncryption](./symmetricencryption) | Реализует стандартные симметричные алгоритмы для шифрования данных с использованием единого ключа и парольной фразы (соль). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Указывает сериализации экземпляров шифровать/расшифровывать строку сериализации объекта. |
| [TextShadow](./textshadow) | Представляет свойства теней текста для текстовых подписей. Результат может различаться в зависимости от типа подписи и формата документа. Рекомендуется использовать TextShadow вместе с подписью TextAsImage для всех поддерживаемых типов документов, а также с простой TextSignature и TextSignature в качестве водяного знака для электронных таблиц (.xslx) и презентаций (.pptx). Простая TextSignature для Word (.docx) также рекомендуется, но имеет ограниченную функциональность. |
| [TextureBrush](./texturebrush) | Представляет текстурную кисть. |
| [VCard](./vcard) | Представляет стандартные контактные данные электронной визитной карточки. |
| [WiFi](./wifi) | Представляет детали подключения к сети WiFi. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IDataEncryption](./idataencryption) | Интерфейс шифрования, предоставляющий методы кодирования и декодирования объектов. |
| [IDataSerializer](./idataserializer) | Интерфейс сериализации, предоставляющий методы сериализации и десериализации объектов. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Представляет тип криптовалюты. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Режим кодирования кодировщика DataMatrix, по умолчанию Auto |
| [HIBCLICDateFormat](./hibclicdateformat) | Указывает различные типы форматов дат для HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Указывает типы расположения данных HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [HIBCPASDataType](./hibcpasdatatype) | Указывает различные типы данных записи HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [Mailmark2DType](./mailmark2dtype) | Тип 2D Mailmark определяет размер штрих‑кода Data Matrix |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Представляет тип симметричного алгоритма шифрования. |
| [WiFiEncryptionType](./wifiencryptiontype) | Представляет тип шифрования WiFi. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
