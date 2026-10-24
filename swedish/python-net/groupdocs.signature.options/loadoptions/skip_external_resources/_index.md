---
title: "skip_external_resources‑egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Flaggan som hindrar dokumentet från att ladda externa resurser."
type: docs
url: /sv/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Flaggan som hindrar dokumentet från att ladda externa resurser. Standardvärdet är True; externa resurser laddas inte förutom de som matchar [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Ett dokument kan referera till resurser som lagras utanför det, såsom länkade bilder, bilder som infogas via ett INCLUDEPICTURE‑fält, länkade bilder i presentationer och kalkylblad, samt bilder och stilmallar som refereras av en SVG‑bild. Att ladda en sådan resurs får biblioteket att begära dess adress. På en server som behandlar opålitliga dokument kan ett dokument använda detta för att få servern att skicka förfrågningar till interna adresser (server‑side request forgery), och en UNC‑ eller `file://`‑sökväg kan få Windows att skicka kontots NTLM‑referenser till en annan värd. På en offline‑ eller luftgap‑installation misslyckas förfrågningarna eller väntar på en timeout.

Resurser som hoppas över ritas inte i sidoförhandsvisningar eller i dokument som sparas som bilder, och bild‑, streckkod‑ och QR‑kod‑sökning ser dem inte. Sätt denna egenskap till False endast för betrodda dokument, och föredra att använda specifika adresser med [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Inställningen gäller ordbehandlingsdokument, presentationer, kalkylblad och SVG‑bilder, inklusive dokument i arkiv. För SVG‑bilder tas referenser som inte är tillåtna bort från bilden innan den läses, och en SVG‑bild som inte är välformad XML avvisas. Inställningen styr inte certifikatåterkallningskontroller, tidsstämpelservrar eller licensiering.

Denna egenskap ersätter [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), som har motsatt betydelse.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Se även
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
