---
title: "SetLicense"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Licenzia il componente."
type: docs
weight: 20
url: /it/net/groupdocs.signature/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licenzia il componente.

```csharp
public void SetLicense(string licensePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licensePath | String | Il percorso della licenza. |

### Esempi

Il seguente esempio dimostra come impostare una licenza passando un percorso al file di licenza.

```csharp
string licensePath = "GroupDocs.Signature.lic";
GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
lic.SetLicense(licensePath);
```

### Vedi anche

* class [License](../../license)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenzia il componente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseStream | Stream | Il flusso della licenza. |

### Esempi

Il seguente esempio dimostra come impostare una licenza passando lo Stream del file di licenza.

```csharp
using (FileStream licenseStream = new FileStream("GroupDocs.Signature.lic", FileMode.Open))
{
    GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
    lic.SetLicense(licenseStream);
}
```

### Vedi anche

* class [License](../../license)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
