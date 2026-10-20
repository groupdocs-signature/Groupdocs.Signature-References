---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Resultat av bearbetning av arkivdokumentets signeringsprocess för dokument med nyss skapade signaturer."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Resultat av bearbetning av arkivdokumentets signeringsprocess för dokument med nyss skapade signaturer.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFileName()](#getFileName--) | Dokumentfilnamn |
|
|  | [getProcessingTime()](#getProcessingTime--) | Returnerar exekveringstiden för processen i millisekunder |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Returnerar det totala antalet bearbetade signaturer |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Returnerar källdokumentets storlek |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Returnerar destinationsdokumentets storlek |
|
|  | [getSucceeded()](#getSucceeded--) | Lista över framgångsrikt bearbetade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista över signaturer som misslyckades under processen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | Om dokumentet bearbetades med fel kommer denna egenskap att innehålla felmeddelandet |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Dokumentfilnamn


**Returns:**
java.lang.String
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


Lista över framgångsrikt bearbetade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista över signaturer som misslyckades under processen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Om dokumentet bearbetades med fel kommer denna egenskap att innehålla felmeddelandet


**Returns:**
java.lang.String
