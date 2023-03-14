---
title: Error
second_title: GroupDocs.Signature för .NET API-referens
description: Skriver ett felmeddelande till konsolen. Felloggmeddelanden ger information om oåterställningsbara händelser i programflödet.
type: docs
weight: 20
url: /sv/net/groupdocs.signature.logging/filelogger/error/
---
## FileLogger.Error method

Skriver ett felmeddelande till konsolen. Felloggmeddelanden ger information om oåterställningsbara händelser i programflödet.

```csharp
public void Error(string message, Exception exception)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| message | String | Felmeddelandet. |
| exception | Exception | Undantaget. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*message* är inget. |
| ArgumentNullException | Kastas när*exception* är inget. |

### Se även

* class [FileLogger](../../filelogger)
* namnutrymme [GroupDocs.Signature.Logging](../../filelogger)
* hopsättning [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->