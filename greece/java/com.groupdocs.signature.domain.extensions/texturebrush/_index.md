---
title: "TextureBrush"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει πινέλο υφής."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Αντιπροσωπεύει πινέλο υφής.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης TextureBrush με προεπιλεγμένες τιμές. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης TextureBrush με αρχείο εικόνας. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης TextureBrush με επιλογή ροής εικόνας. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υφής. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υφής. |
|
|  | [getImageStream()](#getImageStream--) | Λαμβάνει ή ορίζει τη ροή εικόνας υφής. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Λαμβάνει ή ορίζει τη ροή εικόνας υφής. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης TextureBrush με προεπιλεγμένες τιμές.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης TextureBrush με αρχείο εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Διαδρομή αρχείου εικόνας. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης TextureBrush με επιλογή ροής εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Ροή εικόνας. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υφής.
Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Λαμβάνει ή ορίζει τη διαδρομή του αρχείου εικόνας υφής.
Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το ImageStream.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Λαμβάνει ή ορίζει τη ροή εικόνας υφής.
Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί του ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Λαμβάνει ή ορίζει τη ροή εικόνας υφής.
Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί του ImageFilePath.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.io.InputStream |  |

