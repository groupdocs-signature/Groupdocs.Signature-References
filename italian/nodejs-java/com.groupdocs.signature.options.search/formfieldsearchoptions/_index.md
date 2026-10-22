---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di ricerca astratte per le firme dei campi modulo."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Rappresenta le opzioni di ricerca astratte per le firme dei campi modulo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Inizializza una nuova istanza della classe SearchFormFieldOptions con i valori predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Specifica il tipo di firma del campo modulo se deve essere cercata. |
| [setType(Integer value)](#setType-java.lang.Integer-) | Specifica il tipo di firma del campo modulo se deve essere cercata. |
| [getName()](#getName--) | Specifica il modello di espressione regolare del nome della firma del campo modulo se deve essere cercato. |
| [setName(String value)](#setName-java.lang.String-) | Specifica il modello di espressione regolare del nome della firma del campo modulo se deve essere cercato. |
| [getValue()](#getValue--) | Specifica il valore della firma del campo modulo se deve essere cercata. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Specifica il valore della firma del campo modulo se deve essere cercata. |
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Inizializza una nuova istanza della classe SearchFormFieldOptions con i valori predefiniti.

### getType() {#getType--}
```
public final Integer getType()
```


Specifica il tipo di firma del campo modulo se deve essere cercata. Il valore predefinito è null.

**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Specifica il tipo di firma del campo modulo se deve essere cercata. Il valore predefinito è null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Specifica il modello di espressione regolare del nome della firma del campo modulo se deve essere cercato. Puoi usarlo semplicemente come "text" o come espressione regolare tipo "abc\\d+". Il valore predefinito è una stringa vuota.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifica il modello di espressione regolare del nome della firma del campo modulo se deve essere cercato. Puoi usarlo semplicemente come "text" o come espressione regolare tipo "abc\\d+". Il valore predefinito è una stringa vuota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Specifica il valore della firma del campo modulo se deve essere cercata. Il valore predefinito è null.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specifica il valore della firma del campo modulo se deve essere cercata. Il valore predefinito è null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

