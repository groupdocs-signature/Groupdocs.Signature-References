---
title: "Χρονική Σφραγίδα"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει δεδομένα για λήψη χρονικής σήμανσης από ιστότοπο τρίτου."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.domain.structs/timestamp/
---
**Inheritance:**
java.lang.Object
```
public class TimeStamp
```

Αντιπροσωπεύει δεδομένα για λήψη χρονικής σήμανσης από ιστότοπο τρίτου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TimeStamp()](#TimeStamp--) |  |
|  | [TimeStamp(String url, String user, String password)](#TimeStamp-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί νέα δομή χρονικής σφραγίδας. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getUrl()](#getUrl--) | Url τρίτου μέρους. |
|
|  | [setUrl(String value)](#setUrl-java.lang.String-) | Url τρίτου μέρους. |
|
|  | [getUser()](#getUser--) | Χρήστης. |
|
|  | [setUser(String value)](#setUser-java.lang.String-) | Χρήστης. |
|
|  | [getPassword()](#getPassword--) | Κωδικός πρόσβασης. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Κωδικός πρόσβασης. |
|
| [CloneTo(TimeStamp that)](#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [equals(TimeStamp obj1, TimeStamp obj2)](#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
### TimeStamp() {#TimeStamp--}
```
public TimeStamp()
```


### TimeStamp(String url, String user, String password) {#TimeStamp-java.lang.String-java.lang.String-java.lang.String-}
```
public TimeStamp(String url, String user, String password)
```


Δημιουργεί νέα δομή χρονικής σφραγίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | url | java.lang.String | Url τρίτου μέρους. |
|
|  | χρήστης | java.lang.String | Χρήστης. |
|
|  | κωδικός πρόσβασης | java.lang.String | Κωδικός πρόσβασης. |
|

### getUrl() {#getUrl--}
```
public final String getUrl()
```


Url τρίτου μέρους.


**Returns:**
java.lang.String
### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


Url τρίτου μέρους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getUser() {#getUser--}
```
public final String getUser()
```


Χρήστης.


**Returns:**
java.lang.String
### setUser(String value) {#setUser-java.lang.String-}
```
public final void setUser(String value)
```


Χρήστης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Κωδικός πρόσβασης.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Κωδικός πρόσβασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### CloneTo(TimeStamp that) {#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public void CloneTo(TimeStamp that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### Clone() {#Clone--}
```
public TimeStamp Clone()
```




**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(TimeStamp obj1, TimeStamp obj2) {#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public static boolean equals(TimeStamp obj1, TimeStamp obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |
| obj2 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

**Returns:**
boolean
