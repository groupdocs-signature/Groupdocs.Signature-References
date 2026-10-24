---
title: "skip_external_resources‑eigenschap"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De vlag die voorkomt dat het document externe bronnen laadt."
type: docs
url: /nl/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

De vlag die voorkomt dat het document externe bronnen laadt. De standaardwaarde is True; externe bronnen worden niet geladen behalve die die overeenkomen met [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Een document kan verwijzen naar bronnen die buiten het document zijn opgeslagen, zoals gekoppelde afbeeldingen, afbeeldingen ingevoegd via een INCLUDEPICTURE‑veld, gekoppelde afbeeldingen in presentaties en spreadsheets, en afbeeldingen en stijlbladen die worden verwezen door een SVG‑afbeelding. Het laden van zo’n bron zorgt ervoor dat de bibliotheek het adres opvraagt. Op een server die onbetrouwbare documenten verwerkt, kan een document dit gebruiken om de server verzoeken naar interne adressen te laten sturen (server‑side request forgery), en een UNC‑ of `file://`‑pad kan ervoor zorgen dat Windows de NTLM‑referenties van het account naar een andere host stuurt. Bij een offline of lucht‑gescheiden installatie falen de verzoeken of wachten ze op een time‑out.

Bronnen die worden overgeslagen, worden niet weergegeven in paginavoorbeelden of in documenten die als afbeeldingen zijn opgeslagen, en afbeelding‑, barcode‑ en QR‑code‑zoekopdrachten zien ze niet. Stel deze eigenschap alleen op False in voor vertrouwde documenten, en geef de voorkeur aan het toestaan van specifieke adressen met [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

De instelling is van toepassing op tekstverwerkingsdocumenten, presentaties, spreadsheets en SVG‑afbeeldingen, inclusief documenten in archieven. Voor SVG‑afbeeldingen worden niet‑toegestane verwijzingen verwijderd uit de afbeelding voordat deze wordt gelezen, en een SVG‑afbeelding die geen goed gevormde XML is, wordt afgewezen. De instelling regelt geen controle op certificaatintrekking, tijdstempel‑servers of licenties.

Deze eigenschap vervangt [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), die de tegenovergestelde betekenis heeft.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Zie ook
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
