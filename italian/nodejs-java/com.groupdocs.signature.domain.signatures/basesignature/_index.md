---
title: "BaseSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Descrive la classe base per le firme."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Descrive la classe base per le firme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSignatureType()](#getSignatureType--) | Specifica il tipo di firma. |
| [getPageNumber()](#getPageNumber--) | Specifica la pagina su cui è stata trovata la firma. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Specifica la pagina su cui è stata trovata la firma. |
| [getSignatureId()](#getSignatureId--) | Identificatore unico della firma per modificare la firma nel documento tramite i metodi Update o Delete. |
| [isSignature()](#isSignature--) | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. |
| [setSignature(boolean value)](#setSignature-boolean-) | Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. |
| [getDeleted()](#getDeleted--) | Ottieni o imposta il flag per indicare se questa firma è stata eliminata dal documento. |
| [getCreatedOn()](#getCreatedOn--) | Ottieni o imposta la data di creazione della firma. |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Ottieni o imposta la data di creazione della firma. |
| [getModifiedOn()](#getModifiedOn--) | Ottieni o imposta la data di modifica della firma. |
| [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Ottieni o imposta la data di modifica della firma. |
| [getTop()](#getTop--) | Specifica la posizione superiore della firma. |
| [setTop(int value)](#setTop-int-) | Specifica la posizione superiore della firma. |
| [getLeft()](#getLeft--) | Specifica la posizione sinistra della firma. |
| [setLeft(int value)](#setLeft-int-) | Specifica la posizione sinistra della firma. |
| [getWidth()](#getWidth--) | Specifica la larghezza della firma. |
| [setWidth(int value)](#setWidth-int-) | Specifica la larghezza della firma. |
| [getHeight()](#getHeight--) | Specifica l'altezza della firma. |
| [setHeight(int value)](#setHeight-int-) | Specifica l'altezza della firma. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
| [toString()](#toString--) |  |
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Specifica il tipo di firma. La firma digitale avrà questa proprietà.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Specifica la pagina su cui è stata trovata la firma.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Specifica la pagina su cui è stata trovata la firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Identificatore unico della firma per modificare la firma nel documento tramite i metodi Update o Delete. Questa proprietà verrà impostata automaticamente dopo la chiamata dei metodi Sign o Search. Se questa proprietà è stata salvata in precedenza, può essere impostata manualmente per manipolare la firma.

**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false).

**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Ottieni o imposta il flag per indicare se questo componente è una Firma o contenuto del documento. Questa proprietà viene utilizzata con il metodo Update per impostare l'elemento come firma (true) o elemento del documento (false).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Ottieni o imposta il flag per indicare se questa firma è stata eliminata dal documento. Questa proprietà viene utilizzata solo per i record del registro della cronologia del documento per mantenere l'elenco delle firme eliminate.

**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Ottieni o imposta la data di creazione della firma.

**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Ottieni o imposta la data di creazione della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Ottieni o imposta la data di modifica della firma.

**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Ottieni o imposta la data di modifica della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Specifica la posizione superiore della firma.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Specifica la posizione superiore della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Specifica la posizione sinistra della firma.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Specifica la posizione sinistra della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Specifica la larghezza della firma.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Specifica la larghezza della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Specifica l'altezza della firma.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Specifica l'altezza della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
