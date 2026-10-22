---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt Suchoptionen für Bildsignaturen dar."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Stellt Suchoptionen für Bildsignaturen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | Initialisiert eine neue Instanz der Klasse ImageSearchOptions mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | Liest oder setzt das Flag, um Bildinhalt der Signatur auf der Dokumentenseite zu erfassen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Liest oder setzt das Flag, um Bildinhalt der Signatur auf der Dokumentenseite zu erfassen. |
| [getMinContentSize()](#getMinContentSize--) | Für einen von Null verschiedenen Wert gibt dieses Flag die minimale Bildgröße für Suchkriterien an. |
| [setMinContentSize(long value)](#setMinContentSize-long-) | Für einen von Null verschiedenen Wert gibt dieses Flag die minimale Bildgröße für Suchkriterien an. |
| [getMaxContentSize()](#getMaxContentSize--) | Für einen von Null verschiedenen Wert gibt dieses Flag die maximale Bildgröße für Suchkriterien an. |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | Für einen von Null verschiedenen Wert gibt dieses Flag die maximale Bildgröße für Suchkriterien an. |
| [getReturnContentType()](#getReturnContentType--) | Gibt den Dateityp des zurückgegebenen Inhalts der Bildsignatur an, wenn die Eigenschaft ReturnContent aktiviert ist. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt den Dateityp des zurückgegebenen Inhalts der Bildsignatur an, wenn die Eigenschaft ReturnContent aktiviert ist. |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Initialisiert eine neue Instanz der Klasse ImageSearchOptions mit Standardwerten.

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Liest oder setzt das Flag, um Bildinhalt der Signatur auf der Dokumentenseite zu erfassen. Wenn dieses Flag auf true gesetzt ist, behält der Bildsignaturinhalt die Rohbilddaten im erforderlichen Format ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Standardmäßig ist diese Option deaktiviert.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Liest oder setzt das Flag, um Bildinhalt der Signatur auf der Dokumentenseite zu erfassen. Wenn dieses Flag auf true gesetzt ist, behält der Bildsignaturinhalt die Rohbilddaten im erforderlichen Format ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Standardmäßig ist diese Option deaktiviert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Für einen von Null verschiedenen Wert gibt dieses Flag die minimale Bildgröße für Suchkriterien an. Standardmäßig ist dieses Flag auf Null gesetzt und beeinflusst das Suchergebnis nicht.

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Für einen von Null verschiedenen Wert gibt dieses Flag die minimale Bildgröße für Suchkriterien an. Standardmäßig ist dieses Flag auf Null gesetzt und beeinflusst das Suchergebnis nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Für einen von Null verschiedenen Wert gibt dieses Flag die maximale Bildgröße für Suchkriterien an. Standardmäßig ist dieses Flag auf Null gesetzt und beeinflusst das Suchergebnis nicht.

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Für einen von Null verschiedenen Wert gibt dieses Flag die maximale Bildgröße für Suchkriterien an. Standardmäßig ist dieses Flag auf Null gesetzt und beeinflusst das Suchergebnis nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Gibt den Dateityp des zurückgegebenen Inhalts der Bildsignatur an, wenn die Eigenschaft ReturnContent aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei ImageSignature.Format angegeben. Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der Bildinhalt im Originalformat zurückgegeben.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Gibt den Dateityp des zurückgegebenen Inhalts der Bildsignatur an, wenn die Eigenschaft ReturnContent aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei ImageSignature.Format angegeben. Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der Bildinhalt im Originalformat zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

