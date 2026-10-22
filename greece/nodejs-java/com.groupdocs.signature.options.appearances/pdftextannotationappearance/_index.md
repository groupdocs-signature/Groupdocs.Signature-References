---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιγράφει την εμφάνιση του αντικειμένου σχολιασμού κειμένου PDF Title Subject Content."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Περιγράφει την εμφάνιση του αντικειμένου σχολιασμού κειμένου PDF (Τίτλος, Θέμα, Περιεχόμενο).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Δημιουργεί αντικείμενο εμφάνισης σχολιασμού txt υπογραφής PDF. |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί σχολιασμό txt υπογραφής PDF με καθορισμένες τιμές (title, subject, contents). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContents()](#getContents--) | Λαμβάνει ή ορίζει το περιεχόμενο του αντικειμένου σχολιασμού. |
| [setContents(String value)](#setContents-java.lang.String-) | Λαμβάνει ή ορίζει το περιεχόμενο του αντικειμένου σχολιασμού. |
| [getSubject()](#getSubject--) | Λαμβάνει ή ορίζει το Subject που αντιπροσωπεύει την περιγραφή του αντικειμένου. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Λαμβάνει ή ορίζει το Subject που αντιπροσωπεύει την περιγραφή του αντικειμένου. |
| [getTitle()](#getTitle--) | Λαμβάνει ή ορίζει έναν Τίτλο που θα εμφανίζεται στη γραμμή τίτλου του αντικειμένου σημείωσης. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Λαμβάνει ή ορίζει έναν Τίτλο που θα εμφανίζεται στη γραμμή τίτλου του αντικειμένου σημείωσης. |
| [getBorder()](#getBorder--) | Λαμβάνει ή ορίζει διαφορετικές ρυθμίσεις περιγράμματος |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Λαμβάνει ή ορίζει διαφορετικές ρυθμίσεις περιγράμματος |
| [getBorderEffect()](#getBorderEffect--) | Λαμβάνει ή ορίζει το εφέ περιγράμματος. |
| [setBorderEffect(int value)](#setBorderEffect-int-) | Λαμβάνει ή ορίζει το εφέ περιγράμματος. |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Λαμβάνει ή ορίζει την ένταση του εφέ περιγράμματος. |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Λαμβάνει ή ορίζει την ένταση του εφέ περιγράμματος. |
| [getHCornerRadius()](#getHCornerRadius--) | Λαμβάνει ή ορίζει την οριζόντια ακτίνα γωνίας. |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | Λαμβάνει ή ορίζει την οριζόντια ακτίνα γωνίας. |
| [getVCornerRadius()](#getVCornerRadius--) | Λαμβάνει ή ορίζει την κάθετη ακτίνα γωνίας. |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | Λαμβάνει ή ορίζει την κάθετη ακτίνα γωνίας. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Δημιουργεί αντικείμενο εμφάνισης σχολιασμού txt υπογραφής PDF.

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Δημιουργεί σχολιασμό txt υπογραφής PDF με καθορισμένες τιμές (title, subject, contents).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τίτλος | java.lang.String | Τίτλος. |
| θέμα | java.lang.String | Θέμα. |
| περιεχόμενα | java.lang.String | Περιεχόμενα. |

### getContents() {#getContents--}
```
public final String getContents()
```


Λαμβάνει ή ορίζει το περιεχόμενο του αντικειμένου σχολιασμού.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Λαμβάνει ή ορίζει το περιεχόμενο του αντικειμένου σχολιασμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Λαμβάνει ή ορίζει το Subject που αντιπροσωπεύει την περιγραφή του αντικειμένου.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Λαμβάνει ή ορίζει το Subject που αντιπροσωπεύει την περιγραφή του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Λαμβάνει ή ορίζει έναν Τίτλο που θα εμφανίζεται στη γραμμή τίτλου του αντικειμένου σημείωσης.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Λαμβάνει ή ορίζει έναν Τίτλο που θα εμφανίζεται στη γραμμή τίτλου του αντικειμένου σημείωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Λαμβάνει ή ορίζει διαφορετικές ρυθμίσεις περιγράμματος

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Λαμβάνει ή ορίζει διαφορετικές ρυθμίσεις περιγράμματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Λαμβάνει ή ορίζει το εφέ περιγράμματος.

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Λαμβάνει ή ορίζει το εφέ περιγράμματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Λαμβάνει ή ορίζει την ένταση του εφέ περιγράμματος. Η έγκυρη περιοχή τιμής είναι [0..2].

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Λαμβάνει ή ορίζει την ένταση του εφέ περιγράμματος. Η έγκυρη περιοχή τιμής είναι [0..2].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Λαμβάνει ή ορίζει την οριζόντια ακτίνα γωνίας.

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Λαμβάνει ή ορίζει την οριζόντια ακτίνα γωνίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Λαμβάνει ή ορίζει την κάθετη ακτίνα γωνίας.

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Λαμβάνει ή ορίζει την κάθετη ακτίνα γωνίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
