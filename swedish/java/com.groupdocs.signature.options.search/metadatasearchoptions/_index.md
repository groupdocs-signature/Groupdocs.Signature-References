---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar abstrakta sökalternativ för metadata‑signaturer."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Representerar abstrakta sökalternativ för metadata‑signaturer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | Initierar en ny instans av klassen SearchMetadataOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Anger namn för Metadata-signatur om det ska sökas och matchas. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger namn för Metadata-signatur om det ska sökas och matchas. |
|
|  | [getNameMatchType()](#getNameMatchType--) | Hämtar eller anger söktyp för matchning av Metadata-namn. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | Hämtar eller anger söktyp för matchning av Metadata-namn. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Anger om inbyggda dokumentegenskaper som dokumentstatistik, information etc. ska inkluderas i sökresultatet. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Anger om inbyggda dokumentegenskaper som dokumentstatistik, information etc. ska inkluderas i sökresultatet. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Initierar en ny instans av klassen SearchMetadataOptions med standardvärden.


### getName() {#getName--}
```
public final String getName()
```


Anger namn för Metadata-signatur om det ska sökas och matchas.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Anger namn för Metadata-signatur om det ska sökas och matchas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Hämtar eller anger söktyp för matchning av Metadata-namn. Den används endast när egenskapen Name är angiven.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Hämtar eller anger söktyp för matchning av Metadata-namn. Den används endast när egenskapen Name är angiven.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Anger om inbyggda dokumentegenskaper som dokumentstatistik, information etc. ska inkluderas i sökresultatet.
Denna flagga är relevant för presentationer, kalkylblad och ordbehandlingsdokumenttyper.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Anger om inbyggda dokumentegenskaper som dokumentstatistik, information etc. ska inkluderas i sökresultatet.
Denna flagga är relevant för presentationer, kalkylblad och ordbehandlingsdokumenttyper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

