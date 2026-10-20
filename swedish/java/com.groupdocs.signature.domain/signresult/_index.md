---
title: "SignResult"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Resultat av signeringsprocessen för dokumentet med nyss skapade signaturer."
type: docs
weight: 17
url: /sv/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Resultat av signeringsprocessen för dokumentet med nyss skapade signaturer.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Returnerar exekveringstiden för processen i millisekunder |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Returnerar det totala antalet bearbetade signaturer |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Returnerar källdokumentets storlek |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Returnerar destinationsdokumentets storlek |
|
|  | [getSucceeded()](#getSucceeded--) | Lista över nyss skapade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista över signaturer som misslyckades att skapas. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returnerar exekveringstiden för processen i millisekunder


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Returnerar det totala antalet bearbetade signaturer


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Returnerar källdokumentets storlek


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returnerar destinationsdokumentets storlek


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista över nyss skapade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista över signaturer som misslyckades att skapas.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
