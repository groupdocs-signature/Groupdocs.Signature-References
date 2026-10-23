---
title: "skip_external_resources-Eigenschaft"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Das Flag, das das Laden externer Ressourcen durch das Dokument verhindert."
type: docs
url: /de/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Das Flag, das das Laden externer Ressourcen durch das Dokument verhindert. Der Standardwert ist True; externe Ressourcen werden nicht geladen, außer denen, die mit [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) übereinstimmen.

Ein Dokument kann auf Ressourcen verweisen, die außerhalb gespeichert sind, wie verknüpfte Bilder, Bilder, die über ein INCLUDEPICTURE‑Feld eingefügt wurden, verknüpfte Bilder in Präsentationen und Tabellenkalkulationen sowie Bilder und Stylesheets, die von einem SVG‑Bild referenziert werden. Das Laden einer solchen Ressource veranlasst die Bibliothek, deren Adresse anzufordern. Auf einem Server, der nicht vertrauenswürdige Dokumente verarbeitet, könnte ein Dokument dies nutzen, um den Server Anfragen an interne Adressen senden zu lassen (Server‑Side‑Request‑Forgery), und ein UNC‑ oder `file://`‑Pfad könnte Windows veranlassen, die NTLM‑Anmeldeinformationen des Kontos an einen anderen Host zu senden. Bei einer Offline‑ oder luftisolierten Installation schlagen die Anfragen fehl oder warten auf einen Timeout.

Übersprungene Ressourcen werden nicht in Seitenvorschauen oder in als Bilder gespeicherten Dokumenten dargestellt, und die Bild‑, Barcode‑ und QR‑Code‑Suche erkennt sie nicht. Setzen Sie diese Eigenschaft nur für vertrauenswürdige Dokumente auf False und bevorzugen Sie das Zulassen bestimmter Adressen mit [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Die Einstellung gilt für Textverarbeitungsdokumente, Präsentationen, Tabellenkalkulationen und SVG‑Bilder, einschließlich Dokumenten in Archiven. Bei SVG‑Bildern werden nicht zulässige Verweise vor dem Einlesen aus dem Bild entfernt, und ein SVG‑Bild, das kein wohlgeformtes XML ist, wird abgelehnt. Die Einstellung steuert keine Zertifikatswiderrufsprüfungen, Zeitstempeldienste oder Lizenzierung.

Diese Eigenschaft ersetzt [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), die die entgegengesetzte Bedeutung hat.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Siehe auch
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
