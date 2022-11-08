---
title: StampTypes
second_title: GroupDocs.Signature for Java API Reference
description: Stamp types container.
type: docs
weight: 16
url: /java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Stamp types container.
## Constructors

| Constructor | Description |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Round](#Round) | Round stamp type object. |
| [Square](#Square) | Square stamp type object. |
## Methods

| Method | Description |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | All stamp types. |
| [parse(String parsingType)](#parse-java.lang.String-) | Returns stamp type with pasringType name. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Returns stamp type with pasringType name. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Round stamp type object.

### Square {#Square}
```
public static final StampType Square
```


Square stamp type object.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


All stamp types.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Returns stamp type with pasringType name. When name of stamp is unknown - exception is thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Source string of stamp type name. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Returns stamp type with pasringType name. When name of stamp is unknown - no exception is thrown and method returns null value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Source string of stamp type name. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
