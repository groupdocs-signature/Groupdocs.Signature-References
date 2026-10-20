---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt handtekeningvoorbeeldopties voor."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Stelt handtekeningvoorbeeldopties voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Initialiseert PreviewSignatureOptions-object. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Unieke waarde om de handtekening te onderscheiden. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Unieke waarde om de handtekening te onderscheiden. |
|
|  | [getSignOptions()](#getSignOptions--) | Handtekeningopties om een voorbeeld te genereren. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Handtekeningopties om een voorbeeld te genereren. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Haalt op of stelt het formaat van voorbeeldafbeeldingen in. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Haalt op of stelt het formaat van voorbeeldafbeeldingen in. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Initialiseert PreviewSignatureOptions-object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | De handtekeningopties om een voorbeeld te genereren. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Interface die de methode definieert om een uitvoer-pagina-voorbeeld-stream te maken. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Unieke waarde om de handtekening te onderscheiden.
Gebruik SignatureId om de voorbeeldopties te identificeren.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Unieke waarde om de handtekening te onderscheiden.
Gebruik SignatureId om de voorbeeldopties te identificeren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Handtekeningopties om een voorbeeld te genereren.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Handtekeningopties om een voorbeeld te genereren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Haalt op of stelt het formaat van voorbeeldafbeeldingen in.
Standaardwaarde is PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Haalt op of stelt het formaat van voorbeeldafbeeldingen in.
Standaardwaarde is PNG


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

