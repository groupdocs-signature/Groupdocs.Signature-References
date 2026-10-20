---
title: "SwissQR"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice SwissQR."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Classe per la codifica e decodifica del testo incorporato nel codice SwissQR.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Crea un'istanza di SwissQR. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAmount()](#getAmount--) | Ottiene o imposta l'importo del pagamento. |
|
|  | [setAmount(double value)](#setAmount-double-) | Ottiene o imposta l'importo del pagamento. |
|
|  | [getCurrency()](#getCurrency--) | Ottiene o imposta la valuta del pagamento. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Ottiene o imposta la valuta del pagamento. |
|
|  | [getAccount()](#getAccount--) | Ottiene o imposta il numero di conto del creditore. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Ottiene o imposta il numero di conto del creditore. |
|
|  | [getCreditor()](#getCreditor--) | Ottiene o imposta l'indirizzo del creditore. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Ottiene o imposta l'indirizzo del creditore. |
|
|  | [getReference()](#getReference--) | Ottiene o imposta il riferimento di pagamento del creditore. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Ottiene o imposta il riferimento di pagamento del creditore. |
|
|  | [getDebtor()](#getDebtor--) | Ottiene o imposta l'indirizzo del debitore. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Ottiene o imposta l'indirizzo del debitore. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Ottiene o imposta il messaggio non strutturato aggiuntivo. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Ottiene o imposta il messaggio non strutturato aggiuntivo. |
|
|  | [getBillInformation()](#getBillInformation--) | Ottiene o imposta le informazioni aggiuntive della fattura strutturata. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Ottiene o imposta le informazioni aggiuntive della fattura strutturata. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Crea un'istanza di SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Ottiene o imposta l'importo del pagamento.
I valori validi sono compresi tra 0,01 e 999.999.999,99.
Valore: L'importo del pagamento.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Ottiene o imposta l'importo del pagamento.
I valori validi sono compresi tra 0,01 e 999.999.999,99.
Valore: L'importo del pagamento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Ottiene o imposta la valuta del pagamento.
I valori validi sono "CHF" e "EUR".
Valore: La valuta del pagamento.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Ottiene o imposta la valuta del pagamento.
I valori validi sono "CHF" e "EUR".
Valore: La valuta del pagamento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Ottiene o imposta il numero di conto del creditore.
I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein.
Gli spazi sono consentiti nel numero di conto.
Valore: Il numero di conto del creditore.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Ottiene o imposta il numero di conto del creditore.
I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein.
Gli spazi sono consentiti nel numero di conto.
Valore: Il numero di conto del creditore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Ottiene o imposta l'indirizzo del creditore.
Valore: L'indirizzo del creditore.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Ottiene o imposta l'indirizzo del creditore.
Valore: L'indirizzo del creditore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Ottiene o imposta il riferimento di pagamento del creditore.
Il riferimento è obbligatorio per gli IBAN SwissQR, cioè IBAN nell'intervallo CHxx30000xxxxxx
fino a CHxx31999xxxxx.
Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente
al modulo di riferimento ISR) o un riferimento creditore valido secondo ISO 11649 ("RFxxxx").
Entrambi possono contenere spazi per la formattazione.
Valore: Il riferimento di pagamento del creditore.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Ottiene o imposta il riferimento di pagamento del creditore.
Il riferimento è obbligatorio per gli IBAN SwissQR, cioè IBAN nell'intervallo CHxx30000xxxxxx
fino a CHxx31999xxxxx.
Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente
al modulo di riferimento ISR) o un riferimento creditore valido secondo ISO 11649 ("RFxxxx").
Entrambi possono contenere spazi per la formattazione.
Valore: Il riferimento di pagamento del creditore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Ottiene o imposta l'indirizzo del debitore.
Il debitore è opzionale. Se omesso, sia impostare questo campo a null o
impostare un indirizzo con tutti i valori null o vuoti è accettabile.
Valore: L'indirizzo del debitore.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Ottiene o imposta l'indirizzo del debitore.
Il debitore è opzionale. Se omesso, sia impostare questo campo a null o
impostare un indirizzo con tutti i valori null o vuoti è accettabile.
Valore: L'indirizzo del debitore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Ottiene o imposta il messaggio non strutturato aggiuntivo.
Valore: Il messaggio non strutturato.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Ottiene o imposta il messaggio non strutturato aggiuntivo.
Valore: Il messaggio non strutturato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Ottiene o imposta le informazioni aggiuntive della fattura strutturata.
Valore: Le informazioni della fattura strutturata.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Ottiene o imposta le informazioni aggiuntive della fattura strutturata.
Valore: Le informazioni della fattura strutturata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

