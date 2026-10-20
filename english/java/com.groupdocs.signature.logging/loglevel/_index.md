---
title: LogLevel
second_title: GroupDocs.Signature for Java API Reference
description: Specifies which kinds of messages are passed to the logger set in SignatureSettings.
type: docs
weight: 12
url: /java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Specifies which kinds of messages are passed to the logger set in 
SignatureSettings
.
The values are flags and can be combined, for example 
LogLevel.Error \| LogLevel.Warning
.

## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Nothing is logged.
 |
| [Error](#Error) | Errors: an operation failed.
 |
| [Warning](#Warning) | Warnings: an operation succeeded, but its result may not be what you expect.
 |
| [Trace](#Trace) | Traces: the steps of an operation, such as its start and its end.
 |
| [All](#All) | Errors, warnings and traces.
 |
### None {#None}
```
public static final int None
```


Nothing is logged.


### Error {#Error}
```
public static final int Error
```


Errors: an operation failed.


### Warning {#Warning}
```
public static final int Warning
```


Warnings: an operation succeeded, but its result may not be what you expect.


### Trace {#Trace}
```
public static final int Trace
```


Traces: the steps of an operation, such as its start and its end.


### All {#All}
```
public static final int All
```


Errors, warnings and traces. This is the default.


