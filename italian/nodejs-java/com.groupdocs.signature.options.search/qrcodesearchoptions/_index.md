---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di ricerca astratte per le firme QR-Code."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Rappresenta le opzioni di ricerca astratte per le firme QR-Code.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori predefiniti. |
| [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Inizializza una nuova istanza della classe QRCodeSearchOptions con il valore del tipo di codifica. |
| [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori del tipo di codifica e del testo. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifica la proprietà Encode Type per cercare i QR-Code. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Specifica la proprietà Encode Type per cercare i QR-Code. |
| [getText()](#getText--) | Specifica il testo della firma QR-Code se deve essere cercato e corrisposto. |
| [setText(String value)](#setText-java.lang.String-) | Specifica il testo della firma QR-Code se deve essere cercato e corrisposto. |
| [getMatchType()](#getMatchType--) | Ottiene o imposta il tipo di corrispondenza del testo QR-Code nella ricerca. |
| [setMatchType(int value)](#setMatchType-int-) | Ottiene o imposta il tipo di corrispondenza del testo QR-Code nella ricerca. |
| [getDataEncryption()](#getDataEncryption--) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [getReturnContent()](#getReturnContent--) | Ottiene o imposta il flag per acquisire il contenuto immagine del QR-Code della firma nella pagina del documento. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Ottiene o imposta il flag per acquisire il contenuto immagine del QR-Code della firma nella pagina del documento. |
| [getReturnContentType()](#getReturnContentType--) | Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. |
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori predefiniti.

### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Inizializza una nuova istanza della classe QRCodeSearchOptions con il valore del tipo di codifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Specifica il tipo di codifica del QR-Code. |

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori del tipo di codifica e del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Specifica il tipo di codifica del QR-Code. |
| testo | java.lang.String | Imposta il testo della firma QR-Code. |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Specifica la proprietà Encode Type per cercare i QR-Code. Se questo valore non è impostato, la ricerca viene eseguita per tutti i tipi di QR-Code supportati.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Specifica la proprietà Encode Type per cercare i QR-Code. Se questo valore non è impostato, la ricerca viene eseguita per tutti i tipi di QR-Code supportati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Specifica il testo della firma QR-Code se deve essere cercato e corrisposto.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifica il testo della firma QR-Code se deve essere cercato e corrisposto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Ottiene o imposta il tipo di corrispondenza del testo QR-Code nella ricerca. Viene utilizzato solo quando la proprietà Text è impostata.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Ottiene o imposta il tipo di corrispondenza del testo QR-Code nella ricerca. Viene utilizzato solo quando la proprietà Text è impostata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Ottiene o imposta il flag per acquisire il contenuto immagine del QR-Code della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma QR-Code manterrà i dati immagine grezzi nel formato richiesto ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Per impostazione predefinita questa opzione è disabilitata.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Ottiene o imposta il flag per acquisire il contenuto immagine del QR-Code della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma QR-Code manterrà i dati immagine grezzi nel formato richiesto ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Per impostazione predefinita questa opzione è disabilitata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto immagine del QR-Code nel formato originale. Questo formato immagine è specificato in QrCodeSignature.Format (). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine del QR-Code in .png originale.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto immagine del QR-Code nel formato originale. Questo formato immagine è specificato in QrCodeSignature.Format (). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine del QR-Code in .png originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

