---
title: "DeleteResult"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Resultat av signaturers borttagning från dokumentet."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Resultat av borttagning av signatur(er) från dokumentet.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Returnerar processens exekveringstid i millisekunder. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Returnerar det totala antalet bearbetade signaturer. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Returnerar källdokumentets storlek. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Returnerar den uppdaterade dokumentstorleken. |
|
|  | [getSucceeded()](#getSucceeded--) | Lista över framgångsrikt borttagna signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista över signaturer som inte togs bort [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returnerar processens exekveringstid i millisekunder.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Returnerar det totala antalet bearbetade signaturer.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Returnerar källdokumentets storlek.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returnerar den uppdaterade dokumentstorleken.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista över framgångsrikt borttagna signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista över signaturer som inte togs bort [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
