---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Il namespace fornisce estensioni per l'aspetto delle firme e funzionalità aggiuntive."
type: docs
weight: 30
url: /it/net/groupdocs.signature.domain.extensions/
---
Il namespace fornisce estensioni per l'aspetto delle firme e funzionalità aggiuntive.

## Classi

| Classe | Descrizione |
| --- | --- |
| [Address](./address) | Rappresenta l'indirizzo per il contatto. |
| [Brush](./brush) | Rappresenta la classe base per vari pennelli. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Rappresenta il trasferimento di criptovaluta (ricezione o invio) per QR-Code. |
| [DigitalVBA](./digitalvba) | Rappresenta la firma digitale per i progetti VBA di fogli di calcolo. Fornisce la possibilità di firmare il progetto VBA in formati di documento di fogli di calcolo specifici come Xlsm o Xltm. Se diverse estensioni DigitalVBA vengono aggiunte a DigitalSignOptions.Extensions, solo la prima è coinvolta nella firma del documento. |
| [Email](./email) | Rappresenta il formato Email per QR-Code. |
| [EPC](./epc) | Rappresenta il Quick Response Code del European Payments Council. |
| [Event](./event) | Rappresenta i dettagli standard dell'evento QR-Code. |
| [FormatAttribute](./formatattribute) | Istruisce la serializzazione degli oggetti a serializzare il membro con il nome e il formato specificati. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Classe per memorizzare i dati combinati HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) con entità di dati primari e secondari. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Classe per memorizzare i dati primari HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Classe per memorizzare i dati secondari e aggiuntivi HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCPASData](./hibcpasdata) | Classe per codificare e decodificare il testo incorporato nel codice HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord) | Classe per memorizzare il record HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard). |
| [LinearGradientBrush](./lineargradientbrush) | Rappresenta un pennello a gradiente lineare. |
| [Mailmark2D](./mailmark2d) | Classe per codificare e decodificare il testo incorporato nel Royal Mail 2D Mailmark. |
| [MaxiCodeMode2](./maxicodemode2) | Classe per codificare e decodificare il testo incorporato nel codice MaxiCode per le modalità. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Classe per codificare e decodificare il secondo messaggio standard per il codice a barre MaxiCode. |
| [MeCard](./mecard) | Rappresenta i dettagli di contatto standard MeCard. |
| [RadialGradientBrush](./radialgradientbrush) | Rappresenta un pennello a gradiente radiale. |
| [SignatureExtension](./signatureextension) | Rappresenta la classe base per le estensioni delle firme. |
| [SkipSerializationAttribute](./skipserializationattribute) | Indica alla serializzazione di saltare il membro. |
| [SMS](./sms) | Rappresenta i dettagli del servizio di messaggi brevi SMS. |
| [SolidBrush](./solidbrush) | Rappresenta un pennello solido. Può essere usato al posto della proprietà colore di sfondo. |
| [SpreadsheetPosition](./spreadsheetposition) | Definisce la posizione della firma per i documenti Spreadsheet. |
| [SwissAddress](./swissaddress) | Rappresenta l'indirizzo del creditore o del debitore. È possibile impostare la via, il numero civico, il codice postale e la città (tipo di indirizzo strutturato) oppure la linea indirizzo 1 e 2 (tipo di elementi di indirizzo combinati). |
| [SwissQR](./swissqr) | Classe per la codifica e decodifica del testo incorporato nel codice SwissQR. |
| [SymmetricEncryption](./symmetricencryption) | Implementa algoritmi simmetrici standard per la crittografia dei dati con chiave singola e passphrase (sale). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Indica alla serializzazione delle istanze di crittografare / decrittografare la stringa di serializzazione dell'oggetto. |
| [TextShadow](./textshadow) | Rappresenta le proprietà dell'ombra del testo per le firme di testo. Il risultato può variare a seconda del tipo di firma e del formato del documento. TextShadow è consigliato per l'uso con la firma TextAsImage per tutti i tipi di documento supportati, anche con TextSignature semplice e TextSignature come filigrana per Fogli di calcolo (.xslx) e Presentazioni (.pptx). TextSignature semplice per Word (.docx) è consigliato anch'esso, ma ha funzionalità limitate. |
| [TextureBrush](./texturebrush) | Rappresenta un pennello a trama. |
| [VCard](./vcard) | Rappresenta i dettagli di contatto standard della Business Card elettronica. |
| [WiFi](./wifi) | Rappresenta i dettagli della connessione alla rete WiFi. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IDataEncryption](./idataencryption) | Interfaccia di crittografia per fornire metodi di codifica e decodifica degli oggetti. |
| [IDataSerializer](./idataserializer) | Interfaccia di serializzazione per fornire metodi di serializzazione e deserializzazione degli oggetti. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Rappresenta il tipo di criptovaluta. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Modalità di codifica dell'encoder DataMatrix, predefinita su Auto |
| [HIBCLICDateFormat](./hibclicdateformat) | Specifica i diversi tipi di formati data per HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Specifica i tipi di posizione dei dati HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [HIBCPASDataType](./hibcpasdatatype) | Specifica i diversi tipi di dati del record HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard |
| [Mailmark2DType](./mailmark2dtype) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Rappresenta il tipo di algoritmo di crittografia simmetrica. |
| [WiFiEncryptionType](./wifiencryptiontype) | Rappresenta il tipo di crittografia WiFi. |

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
