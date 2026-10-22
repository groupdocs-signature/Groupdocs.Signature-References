---
title: "TextSignOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di firma testo."
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Rappresenta le opzioni di firma testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextSignOptions()](#TextSignOptions--) | Inizializza una nuova istanza della classe SignTextOptions con valori predefiniti. |
| [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Inizializza una nuova istanza della classe SignTextOptions con testo. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLeft()](#getLeft--) | Posizione X sinistra della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Posizione X sinistra della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getTop()](#getTop--) | Posizione Y superiore della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Posizione Y superiore della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getWidth()](#getWidth--) | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getHeight()](#getHeight--) | Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getLocationMeasureType()](#getLocationMeasureType--) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| [getSizeMeasureType()](#getSizeMeasureType--) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [getStretch()](#getStretch--) | Modalità di stretching sulla pagina del documento. |
| [setStretch(int value)](#setStretch-int-) | Modalità di stretching sulla pagina del documento. |
| [getRotationAngle()](#getRotationAngle--) | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Allineamento orizzontale della firma sulla pagina del documento. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Allineamento orizzontale della firma sulla pagina del documento. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Allineamento verticale della firma sulla pagina del documento. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Allineamento verticale della firma sulla pagina del documento. |
| [getMargin()](#getMargin--) | Ottiene o imposta lo spazio tra la firma e i bordi del documento. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Ottiene o imposta lo spazio tra la firma e i bordi del documento. |
| [getMarginMeasureType()](#getMarginMeasureType--) | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). |
| [setTransparency(double value)](#setTransparency-double-) | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). |
| [getText()](#getText--) | Ottiene o imposta il testo della firma. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo della firma. |
| [getFont()](#getFont--) | Ottiene o imposta il carattere della firma. |
| [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Ottiene o imposta il carattere della firma. |
| [getForeColor()](#getForeColor--) | Ottiene o imposta il colore di primo piano della firma. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Ottiene o imposta il colore di primo piano della firma. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Ottiene o imposta il tipo di implementazione della firma testuale. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Ottiene o imposta il tipo di implementazione della firma testuale. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Allineamento orizzontale del testo all'interno di una firma. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Allineamento orizzontale del testo all'interno di una firma. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Allineamento verticale del testo all'interno di una firma. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Allineamento verticale del testo all'interno di una firma. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Ottiene o imposta il titolo del campo modulo di testo in cui inserire la firma di testo. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Ottiene o imposta il titolo del campo modulo di testo in cui inserire la firma di testo. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Ottiene o imposta il tipo di campo modulo in cui inserire la firma di testo. |
| [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Ottiene o imposta il tipo di campo modulo in cui inserire la firma di testo. |
| [getShapeType()](#getShapeType--) | Ottiene o imposta il tipo di forma per inserire il testo. |
| [setShapeType(int value)](#setShapeType-int-) | Ottiene o imposta il tipo di forma per inserire il testo. |
| [getSignatureID()](#getSignatureID--) | Ottiene o imposta l'ID univoco della firma. |
| [setSignatureID(int value)](#setSignatureID-int-) | Ottiene o imposta l'ID univoco della firma. |
| [getBorder()](#getBorder--) | Specifica le impostazioni del bordo |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Specifica le impostazioni del bordo |
| [getBackground()](#getBackground--) | Ottiene o imposta le impostazioni dello sfondo della firma. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Ottiene o imposta le impostazioni dello sfondo della firma. |
| [getNative()](#getNative--) | Ottiene o imposta l'attributo nativo. |
| [setNative(boolean value)](#setNative-boolean-) | Ottiene o imposta l'attributo nativo. |
| [getShapePosition()](#getShapePosition--) | Definisce dove la forma deve essere presentata nel layout del documento |
| [setShapePosition(int value)](#setShapePosition-int-) | Definisce dove la forma deve essere presentata nel layout del documento |
| [validate()](#validate--) | Metodo interno per convalidare i parametri delle opzioni. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Inizializza una nuova istanza della classe SignTextOptions con valori predefiniti.

### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Inizializza una nuova istanza della classe SignTextOptions con testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String | Testo della firma. |

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Posizione X sinistra della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Posizione X sinistra della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Posizione Y superiore della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento verticale non è specificato).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Posizione Y superiore della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento verticale non è specificato).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere la proprietà [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Modalità di stretching sulla pagina del documento.

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Modalità di stretching sulla pagina del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Angolo di rotazione della firma sulla pagina del documento (in senso orario).

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Angolo di rotazione della firma sulla pagina del documento (in senso orario).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Allineamento orizzontale della firma sulla pagina del documento.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Allineamento orizzontale della firma sulla pagina del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Allineamento verticale della firma sulla pagina del documento.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Allineamento verticale della firma sulla pagina del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Ottiene o imposta lo spazio tra la firma e i bordi del documento. (funziona SOLO se l'allineamento orizzontale o verticale è specificato).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Ottiene o imposta lo spazio tra la firma e i bordi del documento. (funziona SOLO se l'allineamento orizzontale o verticale è specificato).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getText() {#getText--}
```
public final String getText()
```


Ottiene o imposta il testo della firma.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ottiene o imposta il testo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Ottiene o imposta il carattere della firma.

**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Ottiene o imposta il carattere della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Ottiene o imposta il colore di primo piano della firma.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Ottiene o imposta il colore di primo piano della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Ottiene o imposta il tipo di implementazione della firma testuale.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Ottiene o imposta il tipo di implementazione della firma testuale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Allineamento orizzontale del testo all'interno di una firma. Questa funzionalità è supportata solo per le implementazioni di firma Immagine e Annotazione (vedi [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) proprietà SignatureImplementation).

**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Allineamento orizzontale del testo all'interno di una firma. Questa funzionalità è supportata solo per le implementazioni di firma Immagine e Annotazione (vedi [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) proprietà SignatureImplementation).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Allineamento verticale del testo all'interno di una firma. Questa funzionalità è supportata solo per l'implementazione di firma Immagine (vedi [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) proprietà SignatureImplementation).

**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Allineamento verticale del testo all'interno di una firma. Questa funzionalità è supportata solo per l'implementazione di firma Immagine (vedi [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) proprietà SignatureImplementation).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Ottiene o imposta il titolo del campo modulo di testo in cui inserire la firma di testo. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Ottiene o imposta il titolo del campo modulo di testo in cui inserire la firma di testo. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Ottiene o imposta il tipo di campo modulo in cui inserire la firma di testo. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField. Il valore predefinito è AllTextTypes.

**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Ottiene o imposta il tipo di campo modulo in cui inserire la firma di testo. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField. Il valore predefinito è AllTextTypes.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Ottiene o imposta il tipo di forma per inserire il testo. Questa proprietà può essere usata solo con SignatureImplementation = TextStamp. Il valore predefinito è Rectangle.

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Ottiene o imposta il tipo di forma per inserire il testo. Questa proprietà può essere usata solo con SignatureImplementation = TextStamp. Il valore predefinito è Rectangle.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Ottiene o imposta l'ID univoco della firma. Può essere usato nelle opzioni di verifica della firma. La proprietà è supportata solo per i documenti Pdf.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Ottiene o imposta l'ID univoco della firma. Può essere usato nelle opzioni di verifica della firma. La proprietà è supportata solo per i documenti Pdf.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Specifica le impostazioni del bordo

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Specifica le impostazioni del bordo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Ottiene o imposta le impostazioni dello sfondo della firma.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Ottiene o imposta le impostazioni dello sfondo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Ottiene o imposta l'attributo nativo. Se impostato, possono essere usate firme specifiche del documento. Il watermark di testo nativo per i documenti WordProcessing è diverso da quello normale, ad esempio.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Ottiene o imposta l'attributo nativo. Se impostato, possono essere usate firme specifiche del documento. Il watermark di testo nativo per i documenti WordProcessing è diverso da quello normale, ad esempio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Definisce dove la forma deve essere presentata nel layout del documento

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Definisce dove la forma deve essere presentata nel layout del documento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### validate() {#validate--}
```
public void validate()
```


Metodo interno per convalidare i parametri delle opzioni.

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
