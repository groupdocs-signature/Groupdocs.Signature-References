---
title: "Uppdateringsresultat"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Resultat av modifiering av signaturer i dokumentet."
type: docs
weight: 19
url: /sv/java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

Resultat av modifiering av signaturer i dokumentet.

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
|  | [getSucceeded()](#getSucceeded--) | Lista över framgångsrikt modifierade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista över signaturer som inte uppdaterades [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


Lista över framgångsrikt modifierade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista över signaturer som inte uppdaterades [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
