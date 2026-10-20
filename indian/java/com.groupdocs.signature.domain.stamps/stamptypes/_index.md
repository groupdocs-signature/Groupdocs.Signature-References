---
title: "StampTypes"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "स्टैम्प प्रकार कंटेनर।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

स्टैम्प प्रकार कंटेनर।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Round](#Round) | राउंड स्टैम्प प्रकार ऑब्जेक्ट। |
|
|  | [Square](#Square) | स्क्वायर स्टैम्प प्रकार ऑब्जेक्ट। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | सभी स्टैम्प प्रकार। |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


राउंड स्टैम्प प्रकार ऑब्जेक्ट।


### Square {#Square}
```
public static final StampType Square
```


स्क्वायर स्टैम्प प्रकार ऑब्जेक्ट।


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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | parsingType | java.lang.String | स्टैम्प प्रकार नाम की स्रोत स्ट्रिंग। |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


pasringType नाम के साथ स्टैम्प प्रकार लौटाता है। जब स्टैम्प का नाम अज्ञात हो - कोई अपवाद नहीं फेंका जाता और मेथड null मान लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | parsingType | java.lang.String | स्टैम्प प्रकार नाम की स्रोत स्ट्रिंग। |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

