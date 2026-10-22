---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma QR-code."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Contiene le proprietà della firma QR-code.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Inizializza l'oggetto QrCodeSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifica il tipo di codifica del QR-code. |
| [getText()](#getText--) | Specifica il testo del QR-code. |
| [getFormat()](#getFormat--) | Specifica il formato dell'immagine della firma QR-code. |
| [getContent()](#getContent--) | Specifica il contenuto dell'immagine dati binari del QR-code di tipo Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Ottieni l'oggetto dal testo della firma QR-Code tramite deserializzazione. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Ottieni l'oggetto dal testo della firma QR-Code tramite deserializzazione. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza della firma QR-Code. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Inizializza l'oggetto QrCodeSignature con l'identificatore della firma ottenuto dopo il processo di ricerca. Questo identificatore unico è utilizzato per trovare proprietà aggiuntive per questa firma dal livello di informazioni sulla firma del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signatureId | java.lang.String | Identificatore unico della firma ottenuto tramite il metodo di firma o di ricerca. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Specifica il tipo di codifica del QR-code.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Specifica il testo del QR-code.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specifica il formato dell'immagine della firma QR-code.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specifica il contenuto dell'immagine dati binari del QR-code di tipo Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Per impostazione predefinita questa proprietà non verrà impostata. Usa la proprietà QrCodeSearchOptions.ReturnContent ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-)) per abilitare questa funzionalità.

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Ottieni l'oggetto dal testo della firma QR-Code tramite deserializzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | java.lang.Class<T> |  |

**Returns:**
T -  T : Tipo di oggetto da deserializzare dal testo QR-Code
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Ottieni l'oggetto dal testo della firma QR-Code tramite deserializzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Imposta l'implementazione di crittografia dei dati personalizzata |

T : Tipo di oggetto da deserializzare dal testo QR-Code |
| tipo | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sovrascrive il metodo Equals per confrontare le proprietà della firma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | java.lang.Object | Oggetto firma con cui confrontare. |

**Returns:**
boolean - Restituisce true se l'oggetto firma passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode

**Returns:**
int - Codice hash della firma
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza della firma QR-Code.

**Returns:**
java.lang.Object - Restituisce l'istanza clonata della firma QR-code.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| immagine | java.awt.image.BufferedImage |  |

