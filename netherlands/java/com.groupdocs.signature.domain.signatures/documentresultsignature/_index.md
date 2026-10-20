---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Resultaat van het verwerken van het ondertekeningsproces van een archiefdocument voor een document met nieuw aangemaakte handtekeningen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Resultaat van het verwerken van het ondertekeningsproces van een archiefdocument voor een document met nieuw aangemaakte handtekeningen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFileName()](#getFileName--) | Documentbestandsnaam |
|
|  | [getProcessingTime()](#getProcessingTime--) | Retourneert de uitvoeringstijd van het proces in milliseconden |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourneert het totale aantal verwerkte handtekeningen |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourneert de grootte van het bron‑document |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourneert de grootte van het doel‑document |
|
|  | [getSucceeded()](#getSucceeded--) | Lijst van succesvol verwerkte handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lijst van de handtekeningen die tijdens het proces zijn mislukt [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | als het document met een fout is verwerkt, zal deze eigenschap de foutmelding bevatten |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Documentbestandsnaam


**Returns:**
java.lang.String
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Retourneert de uitvoeringstijd van het proces in milliseconden


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Retourneert het totale aantal verwerkte handtekeningen


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Retourneert de grootte van het bron‑document


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Retourneert de grootte van het doel‑document


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lijst van succesvol verwerkte handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lijst van de handtekeningen die tijdens het proces zijn mislukt [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


als het document met een fout is verwerkt, zal deze eigenschap de foutmelding bevatten


**Returns:**
java.lang.String
