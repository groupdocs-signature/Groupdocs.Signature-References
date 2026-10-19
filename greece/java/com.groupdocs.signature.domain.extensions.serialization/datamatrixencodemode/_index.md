---
title: "DataMatrixEncodeMode"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Η λειτουργία κωδικοποίησης των κωδικοποιητών DataMatrix είναι προεπιλεγμένη σε Auto"
type: docs
weight: 13
url: /el/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
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
|  | [Auto](#Auto) | Αυτόματη επιλογή της καλύτερης λειτουργίας κωδικοποίησης για την κωδικοποίηση DataMatrix |
|
|  | [ASCII](#ASCII) | Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte |
|
|  | [Full](#Full) | Κωδικοποίηση τιμών 8 bit |
|
|  | [Custom](#Custom) | Κωδικοποίηση με την κωδικοποίηση που καθορίζεται στο BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Χρησιμοποιεί κωδικοποίηση C40. |
|
|  | [Text](#Text) | Χρησιμοποιεί κωδικοποίηση Text. |
|
|  | [EDIFACT](#EDIFACT) | Χρησιμοποιεί κωδικοποίηση EDIFACT. |
|
|  | [ANSIX12](#ANSIX12) | Χρησιμοποιεί κωδικοποίηση ANSI X12. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή των σχημάτων κωδικοποίησης στο code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Αυτόματη επιλογή της καλύτερης λειτουργίας κωδικοποίησης για την κωδικοποίηση DataMatrix


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


Χρησιμοποιεί κωδικοποίηση Text. Κωδικοποιεί αλφαριθμητικούς πεζούς, κεφαλαίους και ειδικούς χαρακτήρες.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Χρησιμοποιεί κωδικοποίηση EDIFACT. Χρησιμοποιεί έξι bits ανά χαρακτήρα, κωδικοποιεί ψηφία,
κεφαλαίους χαρακτήρες, και πολλά σημεία στίξης, αλλά δεν υποστηρίζει πεζούς χαρακτήρες.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Χρησιμοποιεί κωδικοποίηση ANSI X12.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή των σχημάτων κωδικοποίησης στο code-text.
Μορφή : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Τα επιτρεπόμενα σχήματα κωδικοποίησης είναι: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Παράδειγμα επεκταμένου code-text: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
διπλασιασμένο\\edifact:EdifactEncodedText"
Όλες οι ανάποδες καθέτους (\\) πρέπει να διπλασιαστούν στο κείμενο.


