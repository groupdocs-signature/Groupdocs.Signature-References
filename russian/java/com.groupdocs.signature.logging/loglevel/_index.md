---
title: "LogLevel"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Указывает, какие типы сообщений передаются регистратору, установленному в SignatureSettings."
type: docs
weight: 12
url: /ru/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Указывает, какие типы сообщений передаются в настроенный журнал
SignatureSettings
.
Значения являются флагами и могут быть объединены, например
LogLevel.Error \| LogLevel.Warning
.

## Поля

| Поле | Описание |
| --- | --- |
|  | [None](#None) | Ничего не записывается. |
|
|  | [Error](#Error) | Ошибки: операция завершилась неудачей. |
|
|  | [Warning](#Warning) | Предупреждения: операция завершилась успешно, но её результат может отличаться от ожидаемого. |
|
|  | [Trace](#Trace) | Трассировки: шаги операции, такие как её начало и конец. |
|
|  | [All](#All) | Ошибки, предупреждения и трассировки. |
|
### None {#None}
```
public static final int None
```


Ничего не записывается.


### Error {#Error}
```
public static final int Error
```


Ошибки: операция завершилась неудачей.


### Warning {#Warning}
```
public static final int Warning
```


Предупреждения: операция завершилась успешно, но её результат может отличаться от ожидаемого.


### Trace {#Trace}
```
public static final int Trace
```


Трассировки: шаги операции, такие как её начало и конец.


### All {#All}
```
public static final int All
```


Ошибки, предупреждения и трассировки. Это значение по умолчанию.


