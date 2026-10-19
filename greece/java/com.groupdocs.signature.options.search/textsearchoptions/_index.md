---
title: "TextSearchOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά επιλογές αναζήτησης για υπογραφές κειμένου."
type: docs
weight: 18
url: /el/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Αναπαριστά επιλογές αναζήτησης για υπογραφές κειμένου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης TextSearchOptions με προεπιλεγμένες τιμές. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης TextSearchOptions με τιμή κειμένου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Καθορίζει το κείμενο υπογραφής για αντιστοίχιση κατά την αναζήτηση. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Καθορίζει το κείμενο υπογραφής για αντιστοίχιση κατά την αναζήτηση. |
|
|  | [getMatchType()](#getMatchType--) | Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου στην αναζήτηση. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου στην αναζήτηση. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Καθορίζει την υλοποίηση της κειμενικής υπογραφής για την αναζήτηση. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Καθορίζει την υλοποίηση της κειμενικής υπογραφής για την αναζήτηση. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης TextSearchOptions με προεπιλεγμένες τιμές.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης TextSearchOptions με τιμή κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Ορίστε το κείμενο της υπογραφής κειμένου. |
|

### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο υπογραφής για αντιστοίχιση κατά την αναζήτηση.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Καθορίζει το κείμενο υπογραφής για αντιστοίχιση κατά την αναζήτηση.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Καθορίζει την υλοποίηση της κειμενικής υπογραφής για την αναζήτηση.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Καθορίζει την υλοποίηση της κειμενικής υπογραφής για την αναζήτηση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

