---
title: "LogLevel"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Especifica qué tipos de mensajes se envían al registrador configurado en SignatureSettings."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Especifica qué tipos de mensajes se pasan al registrador configurado en
SignatureSettings
.
Los valores son indicadores y pueden combinarse, por ejemplo
LogLevel.Error \| LogLevel.Warning
.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [None](#None) | No se registra nada. |
|
|  | [Error](#Error) | Errores: una operación falló. |
|
|  | [Warning](#Warning) | Advertencias: una operación tuvo éxito, pero su resultado puede no ser lo que esperas. |
|
|  | [Trace](#Trace) | Rastros: los pasos de una operación, como su inicio y su fin. |
|
|  | [All](#All) | Errores, advertencias y rastros. |
|
### None {#None}
```
public static final int None
```


No se registra nada.


### Error {#Error}
```
public static final int Error
```


Errores: una operación falló.


### Warning {#Warning}
```
public static final int Warning
```


Advertencias: una operación tuvo éxito, pero su resultado puede no ser lo que esperas.


### Trace {#Trace}
```
public static final int Trace
```


Rastros: los pasos de una operación, como su inicio y su fin.


### All {#All}
```
public static final int All
```


Errores, advertencias y rastros. Este es el predeterminado.


