---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma del campo modulo di input testo per documento PDF"
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Contiene le proprietà della firma del campo modulo di input testo per documento PDF
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Crea PdfTextFormFieldSignature con nome predefinito. |
| [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Crea PdfTextFormFieldSignature con nome predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Ottiene o imposta il testo dell'input di testo del campo modulo. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo dell'input di testo del campo modulo. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di FormField Signature. |
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Crea PdfTextFormFieldSignature con nome predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto campo modulo. |

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Crea PdfTextFormFieldSignature con nome predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'oggetto campo modulo. |
| testo | java.lang.String | Testo dell'oggetto campo modulo. |

### getText() {#getText--}
```
public final String getText()
```


Ottiene o imposta il testo dell'input di testo del campo modulo.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ottiene o imposta il testo dell'input di testo del campo modulo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
