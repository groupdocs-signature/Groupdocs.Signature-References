---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "DataMatrix एन्कोडर का एन्कोडिंग मोड डिफ़ॉल्ट रूप से Auto"
type: docs
weight: 13
url: /hi/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

DataMatrix एन्कोडर का एन्कोडिंग मोड, डिफ़ॉल्ट ऑटो

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Auto](#Auto) | DataMatrix एन्कोडिंग के लिए स्वचालित रूप से सबसे अच्छा एन्कोड मोड चुनें |
|
|  | [ASCII](#ASCII) | प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षर एन्कोड करता है |
|
|  | [Full](#Full) | 8 बिट मान एन्कोड करें |
|
|  | [Custom](#Custom) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding में निर्दिष्ट एन्कोडिंग के साथ एन्कोड करें |
|
|  | [C40](#C40) | C40 एन्कोडिंग का उपयोग करता है। |
|
|  | [Text](#Text) | टेक्स्ट एन्कोडिंग का उपयोग करता है। |
|
|  | [EDIFACT](#EDIFACT) | EDIFACT एन्कोडिंग का उपयोग करता है। |
|
|  | [ANSIX12](#ANSIX12) | ANSI X12 एन्कोडिंग का उपयोग करता है। |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext मोड कोड-टेक्स्ट में एन्कोडिंग स्कीम को मैन्युअल रूप से स्विच करने की अनुमति देता है। |
|
### Auto {#Auto}
```
public static final int Auto
```


DataMatrix एन्कोडिंग के लिए स्वचालित रूप से सबसे अच्छा एन्कोड मोड चुनें


### ASCII {#ASCII}
```
public static final int ASCII
```


प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षर एन्कोड करता है


### Full {#Full}
```
public static final int Full
```


8 बिट मान एन्कोड करें


### Custom {#Custom}
```
public static final int Custom
```


BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding में निर्दिष्ट एन्कोडिंग के साथ एन्कोड करें


### C40 {#C40}
```
public static final int C40
```


C40 एन्कोडिंग का उपयोग करता है। अपर केस अल्फ़ान्यूमेरिक, लोअर केस और विशेष अक्षरों को एन्कोड करता है


### Text {#Text}
```
public static final int Text
```


टेक्स्ट एन्कोडिंग का उपयोग करता है। लोअर केस अल्फ़ान्यूमेरिक, अपर केस और विशेष अक्षरों को एन्कोड करता है।


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


EDIFACT एन्कोडिंग का उपयोग करता है। प्रत्येक अक्षर के लिए छह बिट्स उपयोग करता है, अंकों को एन्कोड करता है,
अपर केस अक्षर, और कई विराम चिह्न, लेकिन लोअर केस अक्षरों का समर्थन नहीं करता।


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


ANSI X12 एन्कोडिंग का उपयोग करता है।


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext मोड कोड-टेक्स्ट में एन्कोडिंग स्कीम को मैन्युअल रूप से स्विच करने की अनुमति देता है।
फ़ॉर्मेट : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
अनुमत एन्कोडिंग स्कीम हैं: EDIFACT, ANSIX12, ASCII, C40, Text, Auto।
Extended code-text उदाहरण: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
डबल्ड\\edifact:EdifactEncodedText\"
सभी बैकस्लैश (\\) को टेक्स्ट में डबल्ड होना चाहिए।


