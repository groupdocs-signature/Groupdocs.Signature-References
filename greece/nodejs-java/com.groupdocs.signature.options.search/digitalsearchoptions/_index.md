---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις βασικές επιλογές για την αναζήτηση ψηφιακών υπογραφών"
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Αντιπροσωπεύει τις βασικές επιλογές για την αναζήτηση ψηφιακών υπογραφών
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DigitalSearchOptions()](#DigitalSearchOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης DigitalSearchOptions με προεπιλεγμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getComments()](#getComments--) | Σχόλια της ψηφιακής υπογραφής για αναζήτηση. |
| [setComments(String value)](#setComments-java.lang.String-) | Σχόλια της ψηφιακής υπογραφής για αναζήτηση. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Εύρος ημερομηνίας και ώρας της ψηφιακής υπογραφής για αναζήτηση. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Εύρος ημερομηνίας και ώρας της ψηφιακής υπογραφής για αναζήτηση. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Διάστημα ημερομηνίας και ώρας της Ψηφιακής Υπογραφής για αναζήτηση. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Διάστημα ημερομηνίας και ώρας της Ψηφιακής Υπογραφής για αναζήτηση. |
| [getSubjectName()](#getSubjectName--) | Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα υποκειμένου του πιστοποιητικού για αναζήτηση. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα υποκειμένου του πιστοποιητικού για αναζήτηση. |
| [getIssuerName()](#getIssuerName--) | Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα του εκδότη του πιστοποιητικού για αναζήτηση. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα του εκδότη του πιστοποιητικού για αναζήτηση. |
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης DigitalSearchOptions με προεπιλεγμένες τιμές.

### getComments() {#getComments--}
```
public final String getComments()
```


Σχόλια της ψηφιακής υπογραφής για αναζήτηση.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Σχόλια της ψηφιακής υπογραφής για αναζήτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Διάστημα ημερομηνίας και ώρας της Ψηφιακής υπογραφής για αναζήτηση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Διάστημα ημερομηνίας και ώρας της Ψηφιακής υπογραφής για αναζήτηση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Διάστημα ημερομηνίας και ώρας της Ψηφιακής Υπογραφής για αναζήτηση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Διάστημα ημερομηνίας και ώρας της Ψηφιακής Υπογραφής για αναζήτηση. Η τιμή που μπορεί να είναι null θα αγνοηθεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα υποκειμένου του πιστοποιητικού για αναζήτηση.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα υποκειμένου του πιστοποιητικού για αναζήτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα του εκδότη του πιστοποιητικού για αναζήτηση.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Για μη κενές τιμές καθορίζει το διακεκριμένο όνομα του εκδότη του πιστοποιητικού για αναζήτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

