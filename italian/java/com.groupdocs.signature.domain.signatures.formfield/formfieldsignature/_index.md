---
title: "FormFieldSignature"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contiene le proprietà della firma del campo modulo."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Contiene le proprietà della firma del campo modulo.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Specifica un nome unico per il campo modulo. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Specifica un nome unico per il campo modulo. |
|
|  | [getType()](#getType--) | Specifica il tipo di campo modulo. |
|
|  | [getValue()](#getValue--) | Specifica l'oggetto dati del campo modulo. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Specifica l'oggetto dati del campo modulo. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
|
### getName() {#getName--}
```
public final String getName()
```


Specifica un nome unico per il campo modulo.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifica un nome unico per il campo modulo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Specifica il tipo di campo modulo.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Specifica l'oggetto dati del campo modulo.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specifica l'oggetto dati del campo modulo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

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

