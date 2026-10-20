---
title: "CheckboxFormFieldSignature"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contiene le proprietà della firma del campo modulo di input check-box."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Contiene le proprietà della firma del campo modulo di input check-box.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Crea PdfCheckboxFormFieldSignature con nome predefinito. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Crea PdfCheckboxFormFieldSignature con nome predefinito e valore |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getChecked()](#getChecked--) | Ottiene o imposta il valore selezionato dell'input del campo modulo casella di controllo. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | Ottiene o imposta il valore selezionato dell'input del campo modulo casella di controllo. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Crea PdfCheckboxFormFieldSignature con nome predefinito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Crea PdfCheckboxFormFieldSignature con nome predefinito e valore


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Nome dell'oggetto campo modulo. |
|
|  | isChecked | boolean | Valore se la casella di controllo è selezionata |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Ottiene o imposta il valore selezionato dell'input del campo modulo casella di controllo.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Ottiene o imposta il valore selezionato dell'input del campo modulo casella di controllo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

