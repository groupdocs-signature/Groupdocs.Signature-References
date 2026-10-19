---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält PDF-Metadaten-Signatur-Eigenschaften."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Enthält PDF-Metadaten-Signatur-Eigenschaften.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Erstellt eine Pdf-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Erstellt eine Pdf-Metadaten-Signatur mit vordefinierten Werten |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Erstellt eine Pdf-Metadaten-Signatur mit vordefinierten Werten |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Das Präfix-Tag des Pdf-Metadaten-Signaturnamens. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Das Präfix-Tag des Pdf-Metadaten-Signaturnamens. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Klont die Metadaten-Signatur-Instanz. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klont die Pdf-Metadaten-Signatur-Instanz mit dem angegebenen Wert. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Erstellt eine Pdf-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Pdf-Metadaten-Signaturname |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Erstellt eine Pdf-Metadaten-Signatur mit vordefinierten Werten


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Metadata‑Signatur‑Objekts |
|
|  | Wert | java.lang.Object | Wert der Metadata‑Signatur |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Erstellt eine Pdf-Metadaten-Signatur mit vordefinierten Werten


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Metadata‑Signatur‑Objekts |
|
|  | Wert | java.lang.Object | Wert der Metadata‑Signatur |
|
|  | tag | java.lang.String | Präfix‑Tag der Metadata‑Signatur |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Das Präfix-Tag des Pdf-Metadaten-Signaturnamens. Standardmäßig ist diese Eigenschaft auf "xmp" gesetzt.
Mögliche Werte sind


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Das Präfix-Tag des Pdf-Metadaten-Signaturnamens. Standardmäßig ist diese Eigenschaft auf "xmp" gesetzt.
Mögliche Werte sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Signatur | java.lang.Object | Signaturobjekt zum Vergleich. |
|

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signaturobjekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode


**Returns:**
int - Signatur-Hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klont die Metadaten-Signatur-Instanz.


**Returns:**
java.lang.Object - Gibt die geklonte Metadaten-Signatur-Instanz zurück

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Klont die Pdf-Metadaten-Signatur-Instanz mit dem angegebenen Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.Object | Wert für das neue geklonte Objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

