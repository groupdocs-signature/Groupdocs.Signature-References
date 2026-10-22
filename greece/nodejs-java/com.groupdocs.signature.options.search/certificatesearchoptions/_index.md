---
title: "CertificateSearchOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αναπαριστά τις επιλογές αναζήτησης για υπογραφές μεταδεδομένων Πιστοποιητικού."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

Αναπαριστά τις επιλογές αναζήτησης για υπογραφές μεταδεδομένων Πιστοποιητικού.

--------------------

 **Learn more** 

 *  
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CertificateSearchOptions()](#CertificateSearchOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με προεπιλεγμένες τιμές. |
| [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με τιμή κειμένου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) | Καθορίζει το κείμενο της ιδιότητας πιστοποιητικού για αντιστοίχιση κατά την αναζήτηση. |
| [setText(String value)](#setText-java.lang.String-) | Καθορίζει το κείμενο της ιδιότητας πιστοποιητικού για αντιστοίχιση κατά την αναζήτηση. |
| [getMatchType()](#getMatchType--) | Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου στην αναζήτηση. |
| [setMatchType(int value)](#setMatchType-int-) | Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου στην αναζήτηση. |
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με προεπιλεγμένες τιμές.

### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης TextSearchOptions με τιμή κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Ορίστε το κείμενο της υπογραφής κειμένου. |

### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο της ιδιότητας πιστοποιητικού για αντιστοίχιση κατά την αναζήτηση.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Καθορίζει το κείμενο της ιδιότητας πιστοποιητικού για αντιστοίχιση κατά την αναζήτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου στην αναζήτηση.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου στην αναζήτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

