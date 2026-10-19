---
title: "EPC"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente le code QR du European Payments Council."
type: docs
weight: 14
url: /fr/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Représente le code QR du European Payments Council.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EPC()](#EPC--) | Instancie un nouvel objet EPC. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Obtient ou définit le nom du bénéficiaire. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom du bénéficiaire. |
|
|  | [getBIC()](#getBIC--) | Obtient ou définit le BIC du bénéficiaire avec une longueur maximale de 11 caractères. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | Obtient ou définit le BIC du bénéficiaire avec une longueur maximale de 11 caractères. |
|
|  | [getIBAN()](#getIBAN--) | Obtient ou définit le compte du bénéficiaire (IBAN). |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | Obtient ou définit le compte du bénéficiaire (IBAN). |
|
|  | [getAmount()](#getAmount--) | Obtient ou définit le montant. |
|
|  | [setAmount(double value)](#setAmount-double-) | Obtient ou définit le montant. |
|
|  | [getCode()](#getCode--) | Obtient ou définit le code d'entreprise jusqu'à 4 caractères. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | Obtient ou définit le code d'entreprise jusqu'à 4 caractères. |
|
|  | [getReference()](#getReference--) | Obtient ou définit la référence de paiement (maximum 35 caractères). |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Obtient ou définit la référence de paiement (maximum 35 caractères). |
|
|  | [getRemittance()](#getRemittance--) | Obtient ou définit les informations de remise (maximum 140 caractères). |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | Obtient ou définit les informations de remise (maximum 140 caractères). |
|
|  | [getInformation()](#getInformation--) | Obtient ou définit les informations d'indice. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | Obtient ou définit les informations d'indice. |
|
|  | [getVersion()](#getVersion--) | Implémentation de la version EPC / SEPA QR-Code. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | Implémentation de la version EPC / SEPA QR-Code. |
|
|  | [getCharset()](#getCharset--) | Implémentation du jeu de caractères EPC / SEPA QR-Code. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | Implémentation du jeu de caractères EPC / SEPA QR-Code. |
|
|  | [getIdentification()](#getIdentification--) | Identification EPC / SEPA QR-Code. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | Identification EPC / SEPA QR-Code. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés EPC |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
### EPC() {#EPC--}
```
public EPC()
```


Instancie un nouvel objet EPC.


### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom du bénéficiaire. La longueur maximale est de 70 caractères.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtient ou définit le nom du bénéficiaire. La longueur maximale est de 70 caractères.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Obtient ou définit le BIC du bénéficiaire avec une longueur maximale de 11 caractères.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Obtient ou définit le BIC du bénéficiaire avec une longueur maximale de 11 caractères.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Obtient ou définit le compte du bénéficiaire (IBAN). L'IBAN comprend jusqu'à 34 caractères alphanumériques.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Obtient ou définit le compte du bénéficiaire (IBAN). L'IBAN comprend jusqu'à 34 caractères alphanumériques.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Obtient ou définit le montant.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Obtient ou définit le montant.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Obtient ou définit le code d'entreprise jusqu'à 4 caractères.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Obtient ou définit le code d'entreprise jusqu'à 4 caractères.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Obtient ou définit la référence de paiement (maximum 35 caractères). Ce champ et le champ d'information de remise sont mutuellement exclusifs.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Obtient ou définit la référence de paiement (maximum 35 caractères). Ce champ et le champ d'information de remise sont mutuellement exclusifs.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Obtient ou définit les informations de remise (maximum 140 caractères). Ce champ et le champ de référence de paiement sont mutuellement exclusifs.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Obtient ou définit les informations de remise (maximum 140 caractères). Ce champ et le champ de référence de paiement sont mutuellement exclusifs.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Obtient ou définit les informations d'indice. Maximum 70 caractères.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Obtient ou définit les informations d'indice. Maximum 70 caractères.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Implémentation de la version EPC / SEPA QR-Code. Par défaut, cette valeur est définie à 002.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Implémentation de la version EPC / SEPA QR-Code. Par défaut, cette valeur est définie à 002.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Implémentation du jeu de caractères EPC / SEPA QR-Code. Par défaut, cette valeur est définie à 1.


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Implémentation du jeu de caractères EPC / SEPA QR-Code. Par défaut, cette valeur est définie à 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Identification EPC / SEPA QR-Code. Par défaut, cette valeur est définie à SCT.


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Identification EPC / SEPA QR-Code. Par défaut, cette valeur est définie à SCT.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Écrase la méthode Equals pour comparer les propriétés EPC


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | source | java.lang.Object | Objet EPC à comparer. |
|

**Returns:**
booléen - Retourne vrai si l'objet d'adresse passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode


**Returns:**
int - code de hachage du courriel

