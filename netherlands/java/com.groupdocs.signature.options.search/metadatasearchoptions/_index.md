---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer abstracte zoekopties voor metadatahandtekeningen."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Geeft weer abstracte zoekopties voor metadatahandtekeningen.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | Initialiseert een nieuw exemplaar van de SearchMetadataOptions‑klasse met standaardwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Specificeert de naam van de Metadata‑handtekening als deze moet worden gezocht en overeenkomen. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Specificeert de naam van de Metadata‑handtekening als deze moet worden gezocht en overeenkomen. |
|
|  | [getNameMatchType()](#getNameMatchType--) | Haalt op of stelt het zoektype voor de naam van Metadata in. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | Haalt op of stelt het zoektype voor de naam van Metadata in. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Geeft aan of ingebouwde documenteigenschappen zoals documentstatistieken, informatie enz. moeten worden opgenomen in het zoekresultaat. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Geeft aan of ingebouwde documenteigenschappen zoals documentstatistieken, informatie enz. moeten worden opgenomen in het zoekresultaat. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Initialiseert een nieuw exemplaar van de SearchMetadataOptions‑klasse met standaardwaarden.


### getName() {#getName--}
```
public final String getName()
```


Specificeert de naam van de Metadata‑handtekening als deze moet worden gezocht en overeenkomen.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specificeert de naam van de Metadata‑handtekening als deze moet worden gezocht en overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Haalt op of stelt de metadata-naam Match Type-zoekopdracht in. Wordt alleen gebruikt wanneer de eigenschap Name is ingesteld.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Haalt op of stelt de metadata-naam Match Type-zoekopdracht in. Wordt alleen gebruikt wanneer de eigenschap Name is ingesteld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Geeft aan of ingebouwde documenteigenschappen zoals documentstatistieken, informatie enz. moeten worden opgenomen in het zoekresultaat.
Deze vlag is van betekenis voor presentatie-, spreadsheet- en tekstverwerkingsdocumentbestanden.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Geeft aan of ingebouwde documenteigenschappen zoals documentstatistieken, informatie enz. moeten worden opgenomen in het zoekresultaat.
Deze vlag is van betekenis voor presentatie-, spreadsheet- en tekstverwerkingsdocumentbestanden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

