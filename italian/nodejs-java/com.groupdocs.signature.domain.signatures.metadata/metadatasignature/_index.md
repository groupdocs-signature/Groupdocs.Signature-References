---
title: "MetadataSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene proprietà della firma Metadata."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Contiene proprietà della firma Metadata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Specifica un nome univoco per i metadati. |
| [setName(String value)](#setName-java.lang.String-) | Specifica un nome univoco per i metadati. |
| [getValue()](#getValue--) | Specifica l'oggetto dei metadati. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Specifica l'oggetto dei metadati. |
| [getType()](#getType--) | Specifica il tipo di valore dei metadati. |
| [setType(int value)](#setType-int-) | Specifica il tipo di valore dei metadati. |
| [getDataEncryption()](#getDataEncryption--) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Value della firma. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Value della firma. |
| [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Ottieni l'oggetto da Metadata Signature Value durante la deserializzazione. |
| [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottieni l'oggetto da Metadata Signature Text durante la deserializzazione. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [toBoolean()](#toBoolean--) | Converte in booleano. |
| [toInteger()](#toInteger--) | Converte in intero. |
| [toDouble()](#toDouble--) | Converte in Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Converte in Double. |
| [toSingle()](#toSingle--) | Converte in float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Converte in float. |
| [toDateTime()](#toDateTime--) | Converte in DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Converte in DateTime. |
| [toString()](#toString--) | Converte in String con il metodo ToString() sovrascritto |
| [toString(String format)](#toString-java.lang.String-) | Converte in String con formato specificato |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Converte in String con formato specificato |
| [deepClone()](#deepClone--) | Clona l'istanza di Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona l'istanza di Metadata Signature con il valore fornito. |
### getName() {#getName--}
```
public final String getName()
```


Specifica un nome univoco per i metadati.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifica un nome univoco per i metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Specifica l'oggetto dei metadati.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specifica l'oggetto dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Specifica il tipo di valore dei metadati.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Specifica il tipo di valore dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Value della firma.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Value della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Ottieni l'oggetto da Metadata Signature Value durante la deserializzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Istanza dell'oggetto T

T : Tipo di oggetto da deserializzare dal valore Metadata
### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Ottieni l'oggetto da Metadata Signature Text durante la deserializzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Imposta l'implementazione di crittografia dei dati personalizzata |

T : Tipo di oggetto da deserializzare dal valore Metadata |

**Returns:**
T -
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
int - Codice hash della firma
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Converte in booleano.

**Returns:**
boolean - Restituisce il valore della firma Metadata come booleano.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Converte in intero.

**Returns:**
int - Restituisce il valore della Firma Metadata come intero.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Converte in Double.

**Returns:**
double - Restituisce il valore della Firma Metadata come Double.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Converte in Double.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
double - Restituisce il valore della Firma Metadata come Double.
### toSingle() {#toSingle--}
```
public float toSingle()
```


Converte in float.

**Returns:**
float - Restituisce il valore della Firma Metadata come float.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture ()
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Converte in float.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
float - Restituisce il valore della Firma Metadata come float.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Converte in DateTime.

**Returns:**
java.util.Date - Restituisce il valore della Firma Metadata come DateTime.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Converte in DateTime.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
java.util.Date - Restituisce il valore della Firma Metadata come DateTime.
### toString() {#toString--}
```
public String toString()
```


Converte in String con il metodo ToString() sovrascritto

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.

--------------------

Converte una proprietà boolean in "True" o "False". Per un altro tipo di dato verrà utilizzato il provider di formato dati predefinito.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Converte in String con formato specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | formato | java.lang.String | Stringa di formato dati. |

--------------------

Converte una proprietà boolean in "True" o "False". Verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture |

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Converte in String con formato specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | java.lang.String | Stringa di formato dati. |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Converte una proprietà boolean in "True" o "False". |

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza di Metadata Signature.

**Returns:**
java.lang.Object - Restituisce l'istanza clonata di Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clona l'istanza di Metadata Signature con il valore fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Valore per il nuovo oggetto clonato. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.
