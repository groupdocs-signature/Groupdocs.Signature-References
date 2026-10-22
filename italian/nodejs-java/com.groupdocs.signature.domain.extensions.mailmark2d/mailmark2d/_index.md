---
title: "Mailmark2D"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Classe per codificare e decodificare il testo incorporato nel Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Classe per codificare e decodificare il testo incorporato nel Royal Mail 2D Mailmark
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | Crea i dati combinati Royal Mail Mailmark con i valori predefiniti dei dati primari e secondari. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | Identifica l'ID Paese UPU. Lunghezza massima: 4 caratteri. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifica l'ID Paese UPU. Lunghezza massima: 4 caratteri. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto. |
| [getVersionID()](#getVersionID--) | Identifica la versione del codice a barre in base a ciascun ID Tipo di Informazione. |
| [getClass_()](#getClass---) | Identifica la classe dell'elemento. |
| [setClass(String value)](#setClass-java.lang.String-) | Identifica la classe dell'elemento. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifica il gruppo unico di clienti coinvolti nella spedizione. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifica il gruppo unico di clienti coinvolti nella spedizione. |
| [getItemID()](#getItemID--) | Identifica l'elemento unico all'interno dell'ID della catena di fornitura. |
| [setItemID(int value)](#setItemID-int-) | Identifica l'elemento unico all'interno dell'ID della catena di fornitura. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. |
| [getRTSFlag()](#getRTSFlag--) | Flag che indica quale livello di servizio di Reso al Mittente è richiesto. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Flag che indica quale livello di servizio di Reso al Mittente è richiesto. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contiene il codice postale di Reso al Mittente ma senza DPS. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contiene il codice postale di Reso al Mittente ma senza DPS. |
| [getCustomerContent()](#getCustomerContent--) | Spazio opzionale per uso del cliente. |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Spazio opzionale per uso del cliente. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Modalità di codifica del codice a barre DataMatrix. |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Modalità di codifica del codice a barre DataMatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix. |
| [deepClone()](#deepClone--) | Ottiene una copia di questo oggetto. |
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Crea i dati combinati Royal Mail Mailmark con i valori predefiniti dei dati primari e secondari.

### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifica l'ID Paese UPU. Lunghezza massima: 4 caratteri.

**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifica l'ID Paese UPU. Lunghezza massima: 4 caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto.

--------------------

Valori validi: "0" - Domestico Ordinato e Non Ordinato "A" - Posta online "B" - Imbustamento "C" - Consolidamento

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifica il payload del codice a barre Royal Mail Mailmark per ogni tipo di prodotto.

--------------------

Valori validi: "0" - Domestico Ordinato e Non Ordinato "A" - Posta online "B" - Imbustamento "C" - Consolidamento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifica la versione del codice a barre in base a ciascun ID Tipo di Informazione.

--------------------

Valori validi: "1" - attualmente usato solo questo valore (predefinito) "0" e da "2" a "9" e da "A" a "Z" riservati per potenziali usi futuri.

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifica la classe dell'elemento.

--------------------

Valori validi: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deferred (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifica la classe dell'elemento.

--------------------

Valori validi: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deferred (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999.

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifica l'elemento unico all'interno dell'ID della catena di fornitura. Ogni codice a barre Mailmark deve contenere un ID in modo da poter essere identificato univocamente per almeno 90 giorni. Valore massimo: 99999999.

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifica l'elemento unico all'interno dell'ID della catena di fornitura. Ogni codice a barre Mailmark deve contenere un ID in modo da poter essere identificato univocamente per almeno 90 giorni. Valore massimo: 99999999.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido. Lunghezza massima è 9.

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono rispettare un formato PAF® valido. Lunghezza massima è 9.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Flag che indica quale livello di servizio di Reso al Mittente è richiesto. Lunghezza massima è 1.

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Flag che indica quale livello di servizio di Reso al Mittente è richiesto. Lunghezza massima è 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Contiene il codice postale di Reso al Mittente ma senza DPS. Il CP (senza DPS) deve rispettare un formato PAF®.

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Contiene il codice postale di Reso al Mittente ma senza DPS. Il CP (senza DPS) deve rispettare un formato PAF®.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Spazio opzionale per uso del cliente.

--------------------

Lunghezza massima per Tipo [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Spazio opzionale per uso del cliente.

--------------------

Lunghezza massima per Tipo [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Modalità di codifica del codice a barre DataMatrix. Valore predefinito: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Modalità di codifica del codice a barre DataMatrix. Valore predefinito: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix.

**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


Il tipo 2D Mailmark definisce la dimensione del codice a barre Data Matrix.

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
