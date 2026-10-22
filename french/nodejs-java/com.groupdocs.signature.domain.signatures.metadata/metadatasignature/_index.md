---
title: "MetadataSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de signature des métadonnées."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
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
| [getName()](#getName--) | Spécifie un nom de métadonnée unique. |
| [setName(String value)](#setName-java.lang.String-) | Spécifie un nom de métadonnée unique. |
| [getValue()](#getValue--) | Spécifie l'objet de métadonnées. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Spécifie l'objet de métadonnées. |
| [getType()](#getType--) | Spécifie le type de valeur de métadonnées. |
| [setType(int value)](#setType-int-) | Spécifie le type de valeur de métadonnées. |
| [getDataEncryption()](#getDataEncryption--) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés de valeur de la signature. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtient ou définit l'implémentation de l'interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) pour encoder et décoder les propriétés de valeur de la signature. |
| [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Obtenir l'objet à partir de la valeur de la signature de métadonnées lors de la désérialisation. |
| [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtenir l'objet à partir du texte de la signature de métadonnées lors de la désérialisation. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [toBoolean()](#toBoolean--) | Convertit en booléen. |
| [toInteger()](#toInteger--) | Convertit en entier. |
| [toDouble()](#toDouble--) | Convertit en Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Convertit en Double. |
| [toSingle()](#toSingle--) | Convertit en float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Convertit en float. |
| [toDateTime()](#toDateTime--) | Convertit en DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Convertit en DateTime. |
| [toString()](#toString--) | Convertit en String avec la méthode ToString() surchargée |
| [toString(String format)](#toString-java.lang.String-) | Convertit en String avec le format spécifié |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Convertit en String avec le format spécifié |
| [deepClone()](#deepClone--) | Clone l'instance de Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone l'instance de la signature de métadonnées avec la valeur donnée. |
### getName() {#getName--}
```
public final String getName()
```


Spécifie un nom de métadonnée unique.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Spécifie un nom de métadonnée unique.

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


Spécifie le type de valeur de métadonnées.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Spécifie le type de valeur de métadonnées.

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

T : Type d'objet à désérialiser à partir de la valeur des métadonnées
### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Obtenir l'objet à partir du texte de la signature de métadonnées lors de la désérialisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Définir une implémentation de chiffrement de données personnalisée |

T : Type d'objet à désérialiser à partir de la valeur des métadonnées |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Écrase la méthode Equals pour comparer les propriétés de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Objet de signature à comparer. |

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
boolean - Retourne la valeur de la signature des métadonnées en tant que booléen.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Convertit en entier.

**Returns:**
int - Retourne la valeur de la signature des métadonnées en tant qu'entier.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Convertit en Double.

**Returns:**
double - Retourne la valeur de la signature des métadonnées en tant que Double.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Convertit en Double.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
double - Retourne la valeur de la signature des métadonnées en tant que Double.
### toSingle() {#toSingle--}
```
public float toSingle()
```


Convertit en float.

**Returns:**
float - Retourne la valeur de la signature des métadonnées en tant que float.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture ()
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Convertit en float.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
float - Retourne la valeur de la signature des métadonnées en tant que float.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Convertit en DateTime.

**Returns:**
java.util.Date - Retourne la valeur de la signature des métadonnées en tant que DateTime.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Convertit en DateTime.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
java.util.Date - Retourne la valeur de la signature des métadonnées en tant que DateTime.
### toString() {#toString--}
```
public String toString()
```


Convertit en String avec la méthode ToString() surchargée

**Returns:**
java.lang.String - Retourne la valeur de la signature des métadonnées en tant que String.

--------------------

Convertit une propriété booléenne en "True" ou "False". Pour un autre type de données, le fournisseur de format de données par défaut sera utilisé.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Convertit en String avec le format spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | format | java.lang.String | Chaîne de format de données. |

--------------------

Convertit une propriété booléenne en "True" ou "False". Les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture  |

**Returns:**
java.lang.String - Retourne la valeur de la signature des métadonnées en tant que String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Convertit en String avec le format spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Chaîne de format de données. |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Convertit une propriété booléenne en "True" ou "False". |

**Returns:**
java.lang.String - Retourne la valeur de la signature des métadonnées en tant que String.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone l'instance de Metadata Signature.

**Returns:**
java.lang.Object - Renvoie l'instance clonée de Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clone l'instance de la signature de métadonnées avec la valeur donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | Valeur pour le nouvel objet cloné. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.
