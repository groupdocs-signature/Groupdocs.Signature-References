---
title: "MetadataSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Contient les propriétés de signature des métadonnées."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Contient les propriétés de signature des métadonnées.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Spécifie un nom de métadonnées unique. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Spécifie un nom de métadonnées unique. |
|
|  | [getValue()](#getValue--) | Spécifie l'objet de métadonnées. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Spécifie l'objet de métadonnées. |
|
|  | [getType()](#getType--) | Spécifie le type de valeur des métadonnées. |
|
|  | [setType(int value)](#setType-int-) | Spécifie le type de valeur des métadonnées. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés de valeur de la signature. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés de valeur de la signature. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Obtenir l'objet à partir de la valeur de la signature de métadonnées lors de la désérialisation. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtenir l'objet à partir du texte de la signature de métadonnées lors de la désérialisation. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Remplace la méthode Equals pour comparer les propriétés de la signature |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
|  | [toBoolean()](#toBoolean--) | Convertit en booléen. |
|
|  | [toInteger()](#toInteger--) | Convertit en entier. |
|
|  | [toDouble()](#toDouble--) | Convertit en double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Convertit en double. |
|
|  | [toSingle()](#toSingle--) | Convertit en flottant. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Convertit en flottant. |
|
|  | [toDateTime()](#toDateTime--) | Convertit en DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Convertit en DateTime. |
|
|  | [toString()](#toString--) | Convertit en chaîne avec la méthode ToString() remplacée |
|
|  | [toString(String format)](#toString-java.lang.String-) | Convertit en chaîne avec le format spécifié |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Convertit en chaîne avec le format spécifié |
|
|  | [deepClone()](#deepClone--) | Cloner l'instance de la signature de métadonnées. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone l'instance de signature de métadonnées avec la valeur donnée. |
|
### getName() {#getName--}
```
public final String getName()
```


Spécifie un nom de métadonnées unique.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Spécifie un nom de métadonnées unique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Spécifie l'objet de métadonnées.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Spécifie l'objet de métadonnées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Spécifie le type de valeur des métadonnées.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Spécifie le type de valeur des métadonnées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés de valeur de la signature.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés de valeur de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Obtenir l'objet à partir de la valeur de la signature de métadonnées lors de la désérialisation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instance d'un objet T


T
: Type d'objet à désérialiser à partir de la valeur Metadata

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Obtenir l'objet à partir du texte de la signature de métadonnées lors de la désérialisation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Définir une implémentation de chiffrement des données personnalisée |


T
: Type d'objet à désérialiser à partir de la valeur Metadata
|

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Remplace la méthode Equals pour comparer les propriétés de la signature


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signature | java.lang.Object | Objet de signature à comparer. |
|

**Returns:**
boolean - Retourne true si l'objet signature passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode


**Returns:**
int - Code de hachage de la signature

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Convertit en booléen.


**Returns:**
boolean - Renvoie la valeur de la signature Metadata en tant que booléen.

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Convertit en entier.


**Returns:**
int - Renvoie la valeur de la signature Metadata en tant qu'entier.

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie.

<br />


### toDouble() {#toDouble--}
```
public double toDouble()
```


Convertit en double.


**Returns:**
double - Renvoie la valeur de la signature Metadata en tant que Double.

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés SignatureSettings : SignatureSettings.DefaultCulture

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Convertit en double.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie

<br />

|

**Returns:**
double - Renvoie la valeur de la signature Metadata en tant que Double.

### toSingle() {#toSingle--}
```
public float toSingle()
```


Convertit en flottant.


**Returns:**
float - Renvoie la valeur de la signature Metadata en tant que float.

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés SignatureSettings : SignatureSettings.DefaultCulture ()

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Convertit en flottant.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie

<br />

|

**Returns:**
float - Renvoie la valeur de la signature Metadata en tant que float.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Convertit en DateTime.


**Returns:**
java.util.Date - Renvoie la valeur de la signature Metadata en tant que DateTime.

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés SignatureSettings : SignatureSettings.DefaultCulture

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Convertit en DateTime.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

<br />

*** ** * ** ***

Lance une exception si la valeur Metadata ne peut pas être convertie

<br />

|

**Returns:**
java.util.Date - Renvoie la valeur de la signature Metadata en tant que DateTime.

### toString() {#toString--}
```
public String toString()
```


Convertit en chaîne avec la méthode ToString() remplacée


**Returns:**
java.lang.String - Renvoie la valeur de la signature Metadata en tant que String.

<br />

*** ** * ** ***

Convertit une propriété booléenne en "True" ou "False". Pour un autre type de données, le fournisseur de format de données par défaut sera utilisé.

<br />


### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Convertit en chaîne avec le format spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | format | java.lang.String | Chaîne de format de données. |

<br />

*** ** * ** ***

Convertit une propriété booléenne en "True" ou "False". Les informations de propriété de culture par défaut seront utilisées à partir des propriétés SignatureSettings : SignatureSettings.DefaultCulture

<br />

|

**Returns:**
java.lang.String - Renvoie la valeur de la signature Metadata en tant que String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Convertit en chaîne avec le format spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | format | java.lang.String | Chaîne de format de données. |
|
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

<br />

*** ** * ** ***

Convertit une propriété booléenne en "True" ou "False".

<br />

|

**Returns:**
java.lang.String - Renvoie la valeur de la signature Metadata en tant que String.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Cloner l'instance de la signature de métadonnées.


**Returns:**
java.lang.Object - Retourne l'instance clonée de la signature de métadonnées

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clone l'instance de signature de métadonnées avec la valeur donnée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.Object | Valeur pour le nouvel objet cloné. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

