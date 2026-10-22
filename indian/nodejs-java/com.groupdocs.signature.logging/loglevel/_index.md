---
title: "LogLevel"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "उपलब्ध Log Level प्रकारों को निर्दिष्ट करता है"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

उपलब्ध लॉग लेवल प्रकारों को निर्दिष्ट करता है। इस एन्यूमरेशन को फ़्लैग के रूप में उपयोग किया जा सकता है ताकि कई संभावित मानों को सक्षम बिट्स के रूप में सेट किया जा सके। उदाहरण: LogLevel.Error | LogLevel.Warning या LogLevel.Error | LogLevel.Trace
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [None](#None) | कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी। |
| [Error](#Error) | कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी। |
| [Warning](#Warning) | सभी स्तर के समान, सभी संदेशों सहित Trace स्तर को लॉग किया जाएगा |
| [Trace](#Trace) | लॉगिंग स्तर जो Warning से Error स्तर तक के संदेशों को शामिल करता है |
| [All](#All) | सभी लॉग स्तर की घटनाएँ (Error, Warning, Trace) लॉगिंग में शामिल की जाएँगी |
### None {#None}
```
public static final int None
```


कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी।

### Error {#Error}
```
public static final int Error
```


कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी।

### Warning {#Warning}
```
public static final int Warning
```


सभी स्तर के समान, सभी संदेशों सहित Trace स्तर को लॉग किया जाएगा

### Trace {#Trace}
```
public static final int Trace
```


लॉगिंग स्तर जो Warning से Error स्तर तक के संदेशों को शामिल करता है

### All {#All}
```
public static final int All
```


सभी लॉग स्तर की घटनाएँ (Error, Warning, Trace) लॉगिंग में शामिल की जाएँगी

