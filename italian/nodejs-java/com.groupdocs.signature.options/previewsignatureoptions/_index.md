---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di anteprima della firma."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Rappresenta le opzioni di anteprima della firma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Inizializza l'oggetto PreviewSignatureOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSignatureId()](#getSignatureId--) | Valore univoco per distinguere la firma. |
| [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Valore univoco per distinguere la firma. |
| [getSignOptions()](#getSignOptions--) | Opzioni firma per generare l'anteprima. |
| [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Opzioni firma per generare l'anteprima. |
| [getPreviewFormat()](#getPreviewFormat--) | Ottiene o imposta il formato delle immagini di anteprima. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Ottiene o imposta il formato delle immagini di anteprima. |
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Inizializza l'oggetto PreviewSignatureOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Le opzioni firma per le quali generare l'anteprima. |
| pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Interfaccia che definisce il metodo per creare lo stream di anteprima della pagina di output. |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Valore univoco per distinguere la firma. Usa SignatureId per identificare le opzioni di anteprima.

**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Valore univoco per distinguere la firma. Usa SignatureId per identificare le opzioni di anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Opzioni firma per generare l'anteprima.

**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Opzioni firma per generare l'anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Ottiene o imposta il formato delle immagini di anteprima. Il valore predefinito è PNG

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Ottiene o imposta il formato delle immagini di anteprima. Il valore predefinito è PNG

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

