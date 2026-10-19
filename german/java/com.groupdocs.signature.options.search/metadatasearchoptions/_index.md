---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt abstrakte Suchoptionen für Metadaten‑Signaturen dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Stellt abstrakte Suchoptionen für Metadaten‑Signaturen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | Initialisiert eine neue Instanz der Klasse SearchMetadataOptions mit Standardwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Gibt den Namen der Metadaten‑Signatur an, falls diese gesucht und abgeglichen werden soll. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Gibt den Namen der Metadaten‑Signatur an, falls diese gesucht und abgeglichen werden soll. |
|
|  | [getNameMatchType()](#getNameMatchType--) | Liest oder setzt den Suchtyp für die Übereinstimmung des Metadaten‑Namens. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | Liest oder setzt den Suchtyp für die Übereinstimmung des Metadaten‑Namens. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Gibt an, ob integrierte Dokumenteigenschaften wie Dokumentstatistiken, Informationen usw. in das Suchergebnis einbezogen werden sollen. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Gibt an, ob integrierte Dokumenteigenschaften wie Dokumentstatistiken, Informationen usw. in das Suchergebnis einbezogen werden sollen. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Initialisiert eine neue Instanz der Klasse SearchMetadataOptions mit Standardwerten.


### getName() {#getName--}
```
public final String getName()
```


Gibt den Namen der Metadaten‑Signatur an, falls diese gesucht und abgeglichen werden soll.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gibt den Namen der Metadaten‑Signatur an, falls diese gesucht und abgeglichen werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Liest oder setzt den Suchtyp für die Übereinstimmung des Metadaten‑Namens. Er wird nur verwendet, wenn die Name‑Eigenschaft gesetzt ist.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Liest oder setzt den Suchtyp für die Übereinstimmung des Metadaten‑Namens. Er wird nur verwendet, wenn die Name‑Eigenschaft gesetzt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Gibt an, ob integrierte Dokumenteigenschaften wie Dokumentstatistiken, Informationen usw. in das Suchergebnis einbezogen werden sollen.
Dieses Flag ist für Präsentations‑, Tabellenkalkulations‑ und Textverarbeitungs‑Dokumentdateitypen sinnvoll.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Gibt an, ob integrierte Dokumenteigenschaften wie Dokumentstatistiken, Informationen usw. in das Suchergebnis einbezogen werden sollen.
Dieses Flag ist für Präsentations‑, Tabellenkalkulations‑ und Textverarbeitungs‑Dokumentdateitypen sinnvoll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

