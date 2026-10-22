---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma del campo modulo di input casella di controllo."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Contiene le proprietà della firma del campo modulo di input casella di controllo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Crea PdfCheckboxFormFieldSignature con nome predefinito. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Crea PdfCheckboxFormFieldSignature con nome e valore predefiniti |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChecked()](#getChecked--) | Ottiene o imposta il valore selezionato dell'input casella di controllo del campo modulo. |
| [setChecked(boolean value)](#setChecked-boolean-) | Ottiene o imposta il valore selezionato dell'input casella di controllo del campo modulo. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Crea PdfCheckboxFormFieldSignature con nome predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto campo modulo. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Crea PdfCheckboxFormFieldSignature con nome e valore predefiniti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto campo modulo. |
| isChecked | boolean | Valore se la casella di controllo è selezionata |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Ottiene o imposta il valore selezionato dell'input casella di controllo del campo modulo.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Ottiene o imposta il valore selezionato dell'input casella di controllo del campo modulo.

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
| firma | java.lang.Object | Oggetto firma con cui confrontare. |

**Returns:**
boolean - Restituisce true se l'oggetto firma passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode

**Returns:**
int - Codice hash della firma
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza di FormField Signature.

**Returns:**
java.lang.Object - Restituisce un'istanza clonata di FormField Signature.
