---
title: "DigitalSearchOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le opzioni di base per la ricerca di firme digitali"
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Rappresenta le opzioni di base per la ricerca di firme digitali

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Inizializza una nuova istanza della classe DigitalSearchOptions con i valori predefiniti. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getComments()](#getComments--) | Commenti della firma digitale da cercare. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Commenti della firma digitale da cercare. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Intervallo di data e ora della firma digitale da cercare. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Intervallo di data e ora della firma digitale da cercare. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Intervallo di data e ora della Firma Digitale da cercare. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Intervallo di data e ora della Firma Digitale da cercare. |
|
|  | [getSubjectName()](#getSubjectName--) | Per valori non vuoti specifica il nome distintivo del soggetto del certificato da cercare. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Per valori non vuoti specifica il nome distintivo del soggetto del certificato da cercare. |
|
|  | [getIssuerName()](#getIssuerName--) | Per valori non vuoti specifica il nome distinto dell'emittente del certificato da cercare. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Per valori non vuoti specifica il nome distinto dell'emittente del certificato da cercare. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Inizializza una nuova istanza della classe DigitalSearchOptions con i valori predefiniti.


### getComments() {#getComments--}
```
public final String getComments()
```


Commenti della firma digitale da cercare.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Commenti della firma digitale da cercare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Intervallo di data e ora della firma digitale da cercare. Il valore nullable verrà ignorato.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Intervallo di data e ora della firma digitale da cercare. Il valore nullable verrà ignorato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Intervallo di data e ora della Firma Digitale da cercare. Il valore nullable verrà ignorato.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Intervallo di data e ora della Firma Digitale da cercare. Il valore nullable verrà ignorato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Per valori non vuoti specifica il nome distintivo del soggetto del certificato da cercare.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Per valori non vuoti specifica il nome distintivo del soggetto del certificato da cercare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Per valori non vuoti specifica il nome distinto dell'emittente del certificato da cercare.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Per valori non vuoti specifica il nome distinto dell'emittente del certificato da cercare.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

