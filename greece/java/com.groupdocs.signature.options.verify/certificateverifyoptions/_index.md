---
title: "CertificateVerifyOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Διατηρεί επιλογές για επαλήθευση εγγράφων πιστοποιητικού."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Διατηρεί επιλογές για επαλήθευση εγγράφων πιστοποιητικού.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της CertificateVerifyOptions με το θέμα προς επαλήθευση. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Καθορίστε τον Εκδότη Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Καθορίστε τον Εκδότη Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Καθορίστε τον Αριθμό Σειράς Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Καθορίστε τον Αριθμό Σειράς Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [getSubject()](#getSubject--) | Καθορίστε το θέμα του Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Καθορίστε το θέμα του Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [getThumbprint()](#getThumbprint--) | Καθορίστε το Αποτύπωμα Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Καθορίστε το Αποτύπωμα Πιστοποιητικού εάν πρέπει να επαληθευτεί. |
|
|  | [getMatchType()](#getMatchType--) | Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου. |
|
|  | [getExpired()](#getExpired--) | Δείχνει εάν το πιστοποιητικό έχει λήξει λόγω του αποτελέσματος επαλήθευσης. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Δείχνει εάν το πιστοποιητικό έχει λήξει λόγω του αποτελέσματος επαλήθευσης. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Λάβετε ή ορίστε εάν η διαδικασία επαλήθευσης πρέπει να παρέχει επικύρωση αλυσίδας X.509 χρησιμοποιώντας βασική πολιτική επαλήθευσης. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Λάβετε ή ορίστε εάν η διαδικασία επαλήθευσης πρέπει να παρέχει επικύρωση αλυσίδας X.509 χρησιμοποιώντας βασική πολιτική επαλήθευσης. |
|
|  | [toString()](#toString--) | Αντικαθιστά τη μετατροπή σε συμβολοσειρά. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο του TextVerifyOptions με προεπιλεγμένες τιμές.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Αρχικοποιεί ένα νέο αντικείμενο της CertificateVerifyOptions με το θέμα προς επαλήθευση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | θέμα | java.lang.String | Θέμα προς επαλήθευση |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Καθορίστε τον Εκδότη Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Καθορίστε τον Εκδότη Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Καθορίστε τον Αριθμό Σειράς Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Καθορίστε τον Αριθμό Σειράς Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Καθορίστε το θέμα του Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Καθορίστε το θέμα του Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Καθορίστε το Αποτύπωμα Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Καθορίστε το Αποτύπωμα Πιστοποιητικού εάν πρέπει να επαληθευτεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Λαμβάνει ή ορίζει την επαλήθευση τύπου αντιστοίχισης κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Δείχνει εάν το πιστοποιητικό έχει λήξει λόγω του αποτελέσματος επαλήθευσης.
Η ιδιότητα είναι μόνο για ανάγνωση.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Δείχνει εάν το πιστοποιητικό έχει λήξει λόγω του αποτελέσματος επαλήθευσης.
Η ιδιότητα είναι μόνο για ανάγνωση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Λάβετε ή ορίστε εάν η διαδικασία επαλήθευσης πρέπει να παρέχει επικύρωση αλυσίδας X.509 χρησιμοποιώντας βασική πολιτική επαλήθευσης.
Από προεπιλογή αυτή η τιμή είναι true.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Λάβετε ή ορίστε εάν η διαδικασία επαλήθευσης πρέπει να παρέχει επικύρωση αλυσίδας X.509 χρησιμοποιώντας βασική πολιτική επαλήθευσης.
Από προεπιλογή αυτή η τιμή είναι true.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Αντικαθιστά τη μετατροπή σε συμβολοσειρά.


**Returns:**
java.lang.String - 
