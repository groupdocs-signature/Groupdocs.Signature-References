---
title: "TextureBrush"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta il pennello a trama."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Rappresenta il pennello a trama.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | Inizializza una nuova istanza della classe TextureBrush con valori predefiniti. |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Inizializza una nuova istanza della classe TextureBrush con file immagine. |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Inizializza una nuova istanza della classe TextureBrush con opzione di flusso immagine. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Ottiene o imposta il percorso del file immagine della texture. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Ottiene o imposta il percorso del file immagine della texture. |
| [getImageStream()](#getImageStream--) | Ottiene o imposta il flusso immagine della texture. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Ottiene o imposta il flusso immagine della texture. |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Inizializza una nuova istanza della classe TextureBrush con valori predefiniti.

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Inizializza una nuova istanza della classe TextureBrush con file immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFilePath | java.lang.String | Percorso del file immagine. |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Inizializza una nuova istanza della classe TextureBrush con opzione di flusso immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageStream | java.io.InputStream | Flusso immagine. |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Ottiene o imposta il percorso del file immagine della texture. Questa proprietà è utilizzata solo se ImageStream non è specificato.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Ottiene o imposta il percorso del file immagine della texture. Questa proprietà è utilizzata solo se ImageStream non è specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Ottiene o imposta il flusso immagine della texture. Se questa proprietà è specificata, viene sempre utilizzata al posto di ImageFilePath.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Ottiene o imposta il flusso immagine della texture. Se questa proprietà è specificata, viene sempre utilizzata al posto di ImageFilePath.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.InputStream |  |

