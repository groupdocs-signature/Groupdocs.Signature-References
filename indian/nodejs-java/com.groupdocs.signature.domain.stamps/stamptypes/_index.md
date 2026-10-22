---
title: "StampTypes"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "स्टैंप प्रकारों का कंटेनर।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

स्टैंप प्रकारों का कंटेनर।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Round](#Round) | गोल स्टैम्प प्रकार वस्तु। |
| [Square](#Square) | वर्गाकार स्टैम्प प्रकार वस्तु। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | सभी स्टैम्प प्रकार। |
| [parse(String parsingType)](#parse-java.lang.String-) | pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


गोल स्टैम्प प्रकार वस्तु।

### Square {#Square}
```
public static final StampType Square
```


वर्गाकार स्टैम्प प्रकार वस्तु।

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


सभी स्टैम्प प्रकार।

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। जब स्टैम्प का नाम अज्ञात हो - अपवाद फेंका जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | स्टैम्प प्रकार नाम की स्रोत स्ट्रिंग। |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। जब स्टैम्प का नाम अज्ञात हो - कोई अपवाद नहीं फेंका जाता और विधि null मान लौटाती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | स्टैम्प प्रकार नाम की स्रोत स्ट्रिंग। |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
