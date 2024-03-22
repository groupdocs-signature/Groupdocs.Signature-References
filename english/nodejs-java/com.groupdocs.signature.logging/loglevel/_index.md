---
title: LogLevel
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Specifies the available Log Level types.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Specifies the available Log Level types. This enumeration can be used as flags to set several possible values as enabled bits Example: LogLevel.Error | LogLevel.Warning or LogLevel.Error | LogLevel.Trace
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No logging limitation all information will be logged from trace, warning to errors |
| [Error](#Error) | No logging limitation all information will be logged from trace, warning to errors |
| [Warning](#Warning) | Same as All level, all messages including the Trace level will be logged |
| [Trace](#Trace) | The logging level to include messages from the Warning to Error level |
| [All](#All) | All Log level events (Error, Warning, Trace) will be included into the logging |
### None {#None}
```
public static final int None
```


No logging limitation all information will be logged from trace, warning to errors

### Error {#Error}
```
public static final int Error
```


No logging limitation all information will be logged from trace, warning to errors

### Warning {#Warning}
```
public static final int Warning
```


Same as All level, all messages including the Trace level will be logged

### Trace {#Trace}
```
public static final int Trace
```


The logging level to include messages from the Warning to Error level

### All {#All}
```
public static final int All
```


All Log level events (Error, Warning, Trace) will be included into the logging

