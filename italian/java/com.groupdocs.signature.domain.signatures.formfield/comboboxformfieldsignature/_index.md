---
title: "ComboboxFormFieldSignature"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contiene le proprietà della firma del campo modulo di input combo-box."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Contiene le proprietà della firma del campo modulo di input combo-box.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Crea ComboboxFormFieldSignature con nome predefinito. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Crea ComboboxFormFieldSignature con nome predefinito e lista di opzioni. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Crea ComboboxFormFieldSignature con nome predefinito, lista di opzioni e valore selezionato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSelected()](#getSelected--) | Ottieni o imposta il valore selezionato. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Ottieni o imposta il valore selezionato. |
|
|  | [getItems()](#getItems--) | Ottieni o imposta la lista di opzioni del combo-box. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Ottieni o imposta la lista di opzioni del combo-box. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Crea ComboboxFormFieldSignature con nome predefinito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Crea ComboboxFormFieldSignature con nome predefinito e lista di opzioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|
|  | items | java.util.List<java.lang.String> | Valori della lista del combo-box. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Crea ComboboxFormFieldSignature con nome predefinito, lista di opzioni e valore selezionato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|
|  | items | java.util.List<java.lang.String> | Valori della lista del combo-box. |
|
|  | selected | java.lang.Object | Valore selezionato. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Ottieni o imposta il valore selezionato.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Ottieni o imposta il valore selezionato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Ottieni o imposta la lista di opzioni del combo-box.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Ottieni o imposta la lista di opzioni del combo-box.


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

