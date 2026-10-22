---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Präsentations-Metadaten-Signatur-Eigenschaften."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Enthält Präsentations-Metadaten-Signatur-Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | Erstellt eine Präsentations-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert |
| [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | Erstellt eine Präsentations-Metadaten-Signatur mit vordefinierten Werten |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Klont die Metadaten-Signatur-Instanz. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Klont Slides-Metadaten-Signatur-Instanz mit dem angegebenen Wert. |
| [toString()](#toString--) | Konvertiert zu String mit überschriebenem ToString()-Methode |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Konvertiert zu String mit angegebenem Format |
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


Erstellt eine Präsentations-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name der Präsentations-Metadaten-Signatur |

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


Erstellt eine Präsentations-Metadaten-Signatur mit vordefinierten Werten

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Metadaten‑Signaturobjekts |
| Wert | java.lang.Object | Wert der Metadaten‑Signatur |

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


Klont Slides-Metadaten-Signatur-Instanz mit dem angegebenen Wert.

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
