---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Η λειτουργία κωδικοποίησης των κωδικοποιητών DataMatrix είναι προεπιλεγμένη σε Auto"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Λειτουργία κωδικοποίησης του κωδικοποιητή DataMatrix, προεπιλογή Auto.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Auto](#Auto) | Αυτόματα επιλέξτε τη βέλτιστη λειτουργία κωδικοποίησης για την κωδικοποίηση DataMatrix |
| [ASCII](#ASCII) | Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte |
| [Full](#Full) | Κωδικοποίηση τιμών 8 bit |
| [Custom](#Custom) | Κωδικοποίηση με την κωδικοποίηση που καθορίζεται στο BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](#C40) | Χρησιμοποιεί κωδικοποίηση C40. |
| [Text](#Text) | Χρησιμοποιεί κωδικοποίηση κειμένου. |
| [EDIFACT](#EDIFACT) | Χρησιμοποιεί κωδικοποίηση EDIFACT. |
| [ANSIX12](#ANSIX12) | Χρησιμοποιεί κωδικοποίηση ANSI X12. |
| [ExtendedCodetext](#ExtendedCodetext) | Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή σχήματος κωδικοποίησης στο code-text. |
### Auto {#Auto}
```
public static final int Auto
```


Αυτόματα επιλέξτε τη βέλτιστη λειτουργία κωδικοποίησης για την κωδικοποίηση DataMatrix

### ASCII {#ASCII}
```
public static final int ASCII
```


Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte

### Full {#Full}
```
public static final int Full
```


Κωδικοποίηση τιμών 8 bit

### Custom {#Custom}
```
public static final int Custom
```


Κωδικοποίηση με την κωδικοποίηση που καθορίζεται στο BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding

### C40 {#C40}
```
public static final int C40
```


Χρησιμοποιεί κωδικοποίηση C40. Κωδικοποιεί αλφαριθμητικούς κεφαλαίους, πεζούς και ειδικούς χαρακτήρες

### Text {#Text}
```
public static final int Text
```


Χρησιμοποιεί κωδικοποίηση κειμένου. Κωδικοποιεί αλφαριθμητικούς πεζούς, κεφαλαίους και ειδικούς χαρακτήρες.

### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Χρησιμοποιεί κωδικοποίηση EDIFACT. Χρησιμοποιεί έξι bits ανά χαρακτήρα, κωδικοποιεί ψηφία, κεφαλαίους γράμματα και πολλά σημεία στίξης, αλλά δεν υποστηρίζει πεζά γράμματα.

### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Χρησιμοποιεί κωδικοποίηση ANSI X12.

### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή σχήματος κωδικοποίησης στο code-text. Μορφή : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Τα επιτρεπόμενα σχήματα κωδικοποίησης είναι: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Παράδειγμα εκτεταμένου code-text: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" Όλα τα backslashes (\\) πρέπει να διπλασιαστούν στο κείμενο.

