---
title: "RadioButtonFormFieldSignature"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contiene le proprietà della firma del campo modulo di input radio-button."
type: docs
weight: 14
url: /it/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Contiene le proprietà della firma del campo modulo di input radio-button.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Crea RadioButtonFieldSignature con nome predefinito. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Crea RadioButtonFieldSignature con nome predefinito e elenco di elementi. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Crea RadioButtonFieldSignature con nome predefinito, elenco di elementi e valore selezionato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSelected()](#getSelected--) | Contiene il valore selezionato. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Contiene il valore selezionato. |
|
|  | [getItems()](#getItems--) | Ottieni o imposta l'elenco delle opzioni dei pulsanti radio. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Ottieni o imposta l'elenco delle opzioni dei pulsanti radio. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Crea RadioButtonFieldSignature con nome predefinito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Crea RadioButtonFieldSignature con nome predefinito e elenco di elementi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|
|  | items | java.util.List<java.lang.String> | Valori dell'elenco dei pulsanti radio. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Crea RadioButtonFieldSignature con nome predefinito, elenco di elementi e valore selezionato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|
|  | items | java.util.List<java.lang.String> | Valori dell'elenco dei pulsanti radio. |
|
|  | selected | java.lang.Object | Valore selezionato. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Contiene il valore selezionato.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Contiene il valore selezionato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Ottieni o imposta l'elenco delle opzioni dei pulsanti radio.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Ottieni o imposta l'elenco delle opzioni dei pulsanti radio.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<java.lang.String> |  |

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

