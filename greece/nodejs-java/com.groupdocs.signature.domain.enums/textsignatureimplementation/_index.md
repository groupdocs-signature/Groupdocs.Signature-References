---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Καθορίζει τον τύπο υλοποίησης για υπογραφή κειμένου PDF."
type: docs
weight: 32
url: /el/nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Καθορίζει τον τύπο υλοποίησης για υπογραφή κειμένου PDF.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Native](#Native) | Υπογραφή κειμένου ως εγγενές αντικείμενο κειμένου στη σελίδα του εγγράφου. |
| [Image](#Image) | Υπογραφή κειμένου ως αντικείμενο εικόνας στη σελίδα του εγγράφου. |
| [Annotation](#Annotation) | Υπογραφή κειμένου ως αντικείμενο Σχόλιο κειμένου στη σελίδα PDF. |
| [Sticker](#Sticker) | Υπογραφή κειμένου ως αντικείμενο αυτοκόλλητου στη σελίδα PDF. |
| [FormField](#FormField) | Υπογραφή κειμένου ως κείμενο σε καθορισμένο πεδίο φόρμας. |
| [Watermark](#Watermark) | Υπογραφή κειμένου ως υδατογράφημα στη σελίδα του εγγράφου. |
### Native {#Native}
```
public static final int Native
```


Υπογραφή κειμένου ως εγγενές αντικείμενο κειμένου στη σελίδα του εγγράφου.

### Image {#Image}
```
public static final int Image
```


Υπογραφή κειμένου ως αντικείμενο εικόνας στη σελίδα του εγγράφου.

### Annotation {#Annotation}
```
public static final int Annotation
```


Υπογραφή κειμένου ως αντικείμενο Σχόλιο κειμένου στη σελίδα PDF. Τα σχόλια είναι ορατά μόνο στην έκδοση με άδεια.

### Sticker {#Sticker}
```
public static final int Sticker
```


Υπογραφή κειμένου ως αντικείμενο αυτοκόλλητου στη σελίδα PDF.

### FormField {#FormField}
```
public static final int FormField
```


Υπογραφή κειμένου ως κείμενο σε καθορισμένο πεδίο φόρμας. Με αυτόν τον τύπο υλοποίησης μπορούν να χρησιμοποιηθούν μόνο οι επιλογές TextSignOptions.Text, TextSignOptions.FormTextFieldType και TextSignOptions.FormTextFieldTitle.

### Watermark {#Watermark}
```
public static final int Watermark
```


Υπογραφή κειμένου ως υδατογράφημα στη σελίδα του εγγράφου.

