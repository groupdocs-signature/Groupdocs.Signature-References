---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Classe per memorizzare i dati secondari e aggiuntivi del HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Classe per memorizzare i dati secondari e aggiuntivi HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Costruttore predefinito ctor() |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifica il formato della data di scadenza. |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identifica il formato della data di scadenza. |
| [getExpiryDate()](#getExpiryDate--) | Identifica la data di scadenza. |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identifica la data di scadenza. |
| [getLotNumber()](#getLotNumber--) | Identifica il numero di lotto o batch. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifica il numero di lotto o batch. |
| [getSerialNumber()](#getSerialNumber--) | Identifica il numero di serie. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifica il numero di serie. |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifica la data di produzione. |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identifica la data di produzione. |
| [getQuantity()](#getQuantity--) | Identifica la quantità, deve essere un valore intero da 0 a 500. |
| [setQuantity(int value)](#setQuantity-int-) | Identifica la quantità, deve essere un valore intero da 0 a 500. |
| [getLinkCharacter()](#getLinkCharacter--) | Identifica il carattere di collegamento nella stringa di output. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifica il carattere di collegamento nella stringa di output. |
| [deepClone()](#deepClone--) | Ottiene una copia di questo oggetto. |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Costruttore predefinito ctor()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identifica il formato della data di scadenza.

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identifica il formato della data di scadenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None.

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli.

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identifica la data di produzione. La data di produzione può essere impostata su DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identifica la data di produzione. La data di produzione può essere impostata su DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identifica il carattere di collegamento nella stringa di output.

**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identifica il carattere di collegamento nella stringa di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Ottiene una copia di questo oggetto.

**Returns:**
java.lang.Object
