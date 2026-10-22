---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di firma QR-Code."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Rappresenta le opzioni di firma QR-Code.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QrCodeSignOptions()](#QrCodeSignOptions--) | Inizializza una nuova istanza della classe QRCodeSignOptions con valori predefiniti. |
| [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Inizializza una nuova istanza della classe QRCodeSignOptions con testo. |
| [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Ottiene o imposta il tipo di QRCode. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Ottiene o imposta il tipo di QRCode. |
| [getForeColor()](#getForeColor--) | Ottiene o imposta il colore Fore delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi con la verifica. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Ottiene o imposta il colore Fore delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi con la verifica. |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | Ottiene o imposta il colore Fore delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi con la verifica. |
| [getInnerMargins()](#getInnerMargins--) | Ottiene o imposta lo spazio tra gli elementi QRCode e i bordi dell'immagine risultante. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Ottiene o imposta lo spazio tra gli elementi QRCode e i bordi dell'immagine risultante. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Ottiene o imposta l'allineamento del testo nell'immagine QR-code risultante. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Ottiene o imposta l'allineamento del testo nell'immagine QR-code risultante. |
| [getLogoFilePath()](#getLogoFilePath--) | Ottiene o imposta il nome file dell'immagine del logo QR-code. |
| [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Ottiene o imposta il nome file dell'immagine del logo QR-code. |
| [getLogoStream()](#getLogoStream--) | Ottiene o imposta lo stream dell'immagine del logo QR-code. |
| [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Ottiene o imposta lo stream dell'immagine del logo QR-code. |
| [getData()](#getData--) | Ottiene o imposta l'oggetto personalizzato da serializzare nel contenuto QR-Code. |
| [setData(Object value)](#setData-java.lang.Object-) | Ottiene o imposta l'oggetto personalizzato da serializzare nel contenuto QR-Code. |
| [getDataEncryption()](#getDataEncryption--) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [getReturnContent()](#getReturnContent--) | Ottiene o imposta il flag per ottenere il contenuto immagine QR-Code di una firma posizionata sulla pagina del documento. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Ottiene o imposta il flag per ottenere il contenuto immagine QR-Code di una firma posizionata sulla pagina del documento. |
| [getReturnContentType()](#getReturnContentType--) | Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Inizializza una nuova istanza della classe QRCodeSignOptions con valori predefiniti.

### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Inizializza una nuova istanza della classe QRCodeSignOptions con testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo della firma. |

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Inizializza una nuova istanza della classe BarcodeSignOptions con testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo QRCode |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Tipo di codifica QRCode vedi [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Ottiene o imposta il tipo di QRCode.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Ottiene o imposta il tipo di QRCode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Ottiene o imposta il colore di primo piano delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Ottiene o imposta il colore di primo piano delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Ottiene o imposta il colore di primo piano delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Ottiene o imposta lo spazio tra gli elementi QRCode e i bordi dell'immagine risultante.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Ottiene o imposta lo spazio tra gli elementi QRCode e i bordi dell'immagine risultante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Ottiene o imposta l'allineamento del testo nell'immagine QR-code risultante. Il valore predefinito è None.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Ottiene o imposta l'allineamento del testo nell'immagine QR-code risultante. Il valore predefinito è None.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Ottiene o imposta il nome file dell'immagine logo QR-code. Questa proprietà è utilizzata solo se LogoStream non è specificato. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Ottiene o imposta il nome file dell'immagine logo QR-code. Questa proprietà è utilizzata solo se LogoStream non è specificato. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Ottiene o imposta lo stream dell'immagine logo QR-code. Se questa proprietà è specificata, viene sempre usata al posto di LogoGuid. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Ottiene o imposta lo stream dell'immagine logo QR-code. Se questa proprietà è specificata, viene sempre usata al posto di LogoGuid. L'uso di questa proprietà potrebbe causare problemi di verifica. Usala con attenzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Ottiene o imposta l'oggetto personalizzato da serializzare nel contenuto QR-Code.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Ottiene o imposta l'oggetto personalizzato da serializzare nel contenuto QR-Code.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

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


Ottiene o imposta il flag per ottenere il contenuto immagine QR-Code di una firma posizionata sulla pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma QR-Code manterrà i dati immagine grezzi nel formato richiesto ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Per impostazione predefinita questa opzione è disabilitata.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Ottiene o imposta il flag per ottenere il contenuto immagine QR-Code di una firma posizionata sulla pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma QR-Code manterrà i dati immagine grezzi nel formato richiesto ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Per impostazione predefinita questa opzione è disabilitata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto immagine QR-Code nel formato originale. Questo formato immagine è specificato in QrCodeSignature.Format ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine QR-Code in formato .png.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto immagine QR-Code nel formato originale. Questo formato immagine è specificato in QrCodeSignature.Format ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine QR-Code in formato .png.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
