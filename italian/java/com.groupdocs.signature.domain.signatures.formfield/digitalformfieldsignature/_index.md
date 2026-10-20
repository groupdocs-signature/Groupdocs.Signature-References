---
title: "DigitalFormFieldSignature"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contiene le proprietà della firma digitale del campo modulo di input per documenti PDF."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Contiene le proprietà della firma digitale del campo modulo di input per documenti PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Crea PdfDigitalFormFieldSignature con nome predefinito. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSigned()](#getSigned--) | Proprietà di sola lettura che indica se Form-field Signature è stata firmata con certificato digitale. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Crea PdfDigitalFormFieldSignature con nome predefinito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Proprietà di sola lettura che indica se Form-field Signature è stata firmata con certificato digitale.


**Returns:**
boolean
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sovrascrive il metodo Equals per confrontare le proprietà della firma


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | firma | java.lang.Object | Oggetto Signature da confrontare. |
|

**Returns:**
boolean - Restituisce true se l'oggetto signature passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode


**Returns:**
int - Codice hash della Signature

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza di FormField Signature.


**Returns:**
java.lang.Object - Restituisce l'istanza clonata di FormField Signature.

