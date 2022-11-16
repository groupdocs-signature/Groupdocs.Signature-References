---
title: WordProcessingSaveOptions
second_title: GroupDocs.Signature för .NET API-referens
description: Spara alternativ för WordProcessingdokument.
type: docs
weight: 1710
url: /sv/net/groupdocs.signature.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Spara alternativ för WordProcessing-dokument.

```csharp
public class WordProcessingSaveOptions : SaveOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Initierar en ny instans av WordProcessingSaveOptions-klassen med standardvärden. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(bool) | Initierar en ny instans av WordProcessingSaveOptions-klassen med angiven utdatatyp och överskrivningsflagga. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_2)(WordProcessingSaveFileFormat) | Initierar en ny instans av WordProcessingSaveOptions-klassen med specificerat utdatafilformat. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_3)(WordProcessingSaveFileFormat, bool) | Initierar en ny instans av WordProcessingSaveOptions-klassen med specificerat utdatafilformat och överskrivningsflagga. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Hämtar eller ställer in flaggan för att automatiskt lägga till tillägg när det saknades i utdatafilen path Standardvärdet är false. |
| [FileFormat](../../groupdocs.signature.options/wordprocessingsaveoptions/fileformat) { get; set; } | Hämtar eller ställer in filformat för signerat dokument. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Hämtar eller ställer in om befintlig fil ska skrivas över med ny utdatafil. Annars skapas en ny fil med nummer som suffix. Som standard är detta värde satt till true vilket betyder att filen kommer att skrivas över. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Hämtar eller ställer in lösenord för att spara signerade dokument med lösenordsskydd. Den här egenskapen stöds inte för bilddokument. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Hämtar eller ställer in om lösenord ska användas från LoadOptions för att spara signerat dokument som skyddat. Standardvärdet är sant. Den här egenskapen stöds inte för bilddokument. |

### Se även

* class [SaveOptions](../saveoptions)
* namnutrymme [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* hopsättning [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->