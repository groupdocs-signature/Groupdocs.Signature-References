---
title: "HIBCLICPrimaryData"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Classe per memorizzare i dati principali del codice di identificazione con licenza HIBC Healthcare Industry Bar Code Council LIC."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Classe per memorizzare i dati primari HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Default ctor() |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifica la data del codice di identificazione dell'etichettatore. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifica la data del codice di identificazione dell'etichettatore. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifica il numero di prodotto o di catalogo. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifica il numero di prodotto o di catalogo. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifica l'ID dell'unità di misura. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifica l'ID dell'unità di misura. |
|
|  | [deepClone()](#deepClone--) | Ottiene una copia di questo oggetto. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Default ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Identifica la data del codice di identificazione del confezionatore. Il codice di identificazione del confezionatore deve essere
una stringa alfanumerica di 4 simboli, con il primo carattere sempre alfabetico.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifica la data del codice di identificazione del confezionatore. Il codice di identificazione del confezionatore deve essere
una stringa alfanumerica di 4 simboli, con il primo carattere sempre alfabetico.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifica il numero di prodotto o di catalogo. Il numero di prodotto o di catalogo deve essere alfanumerico
stringa con una lunghezza fino a 18 simboli.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifica il numero di prodotto o di catalogo. Il numero di prodotto o di catalogo deve essere alfanumerico
stringa con una lunghezza fino a 18 simboli.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifica l'ID dell'unità di misura. L'ID dell'unità di misura deve essere un valore intero da 0 a 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifica l'ID dell'unità di misura. L'ID dell'unità di misura deve essere un valore intero da 0 a 9.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Ottiene una copia di questo oggetto.


**Returns:**
java.lang.Object
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
