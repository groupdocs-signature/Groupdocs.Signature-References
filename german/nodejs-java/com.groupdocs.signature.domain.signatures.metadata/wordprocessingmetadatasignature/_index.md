---
title: "WordProcessingMetadataSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Textverarbeitungs-Metadaten-Signatur-Eigenschaften."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/wordprocessingmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class WordProcessingMetadataSignature extends MetadataSignature
```

Enthält Textverarbeitungs-Metadaten-Signatur-Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingMetadataSignature(String name)](#WordProcessingMetadataSignature-java.lang.String-) | Erstellt eine WordProcessing-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert. |
| [WordProcessingMetadataSignature(String name, Object value)](#WordProcessingMetadataSignature-java.lang.String-java.lang.Object-) | Erstellt eine WordProcessing-Metadaten-Signatur mit vordefinierten Werten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Klont die Metadaten-Signatur-Instanz. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Klont die Words-Metadaten-Signatur-Instanz mit dem angegebenen Wert. |
| [toString()](#toString--) | Konvertiert zu String mit überschriebenem ToString()-Methode |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Konvertiert zu String mit angegebenem Format |
### WordProcessingMetadataSignature(String name) {#WordProcessingMetadataSignature-java.lang.String-}
```
public WordProcessingMetadataSignature(String name)
```


Erstellt eine WordProcessing-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name der WordProcessing-Metadaten-Signatur. |

### WordProcessingMetadataSignature(String name, Object value) {#WordProcessingMetadataSignature-java.lang.String-java.lang.Object-}
```
public WordProcessingMetadataSignature(String name, Object value)
```


Erstellt eine WordProcessing-Metadaten-Signatur mit vordefinierten Werten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Metadaten‑Signaturobjekts. |
| Wert | java.lang.Object | Wert der Metadaten-Signatur. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klont die Metadaten-Signatur-Instanz.

**Returns:**
java.lang.Object - Gibt eine geklonte Metadata Signature-Instanz zurück
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Klont die Words-Metadaten-Signatur-Instanz mit dem angegebenen Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object | Wert für das neue geklonte Objekt. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


Konvertiert zu String mit überschriebenem ToString()-Methode

**Returns:**
java.lang.String - Gibt den Metadaten-Signaturwert als String zurück.

--------------------

Konvertiert eine boolesche Eigenschaft in "True" oder "False". Für andere Datentypen wird der Standard-Datenformatanbieter verwendet.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Konvertiert zu String mit angegebenem Format

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Format | java.lang.String | Datenformatzeichenfolge. |
|  | Anbieter | com.aspose.ms.System.IFormatProvider | Datenformatanbieter, der für Datenkonvertierungsoperationen verwendet wird. |

--------------------

Konvertiert eine boolesche Eigenschaft in "True" oder "False". |

**Returns:**
java.lang.String - Gibt den Metadaten-Signaturwert als String zurück.
