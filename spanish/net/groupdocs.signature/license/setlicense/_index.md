---
title: "SetLicense"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Licencia el componente."
type: docs
weight: 20
url: /es/net/groupdocs.signature/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string licensePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licensePath | String | La ruta de la licencia. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando una ruta al archivo de licencia.

```csharp
string licensePath = "GroupDocs.Signature.lic";
GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
lic.SetLicense(licensePath);
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

---

## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseStream | Stream | El flujo de la licencia. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando el Stream del archivo de licencia.

```csharp
using (FileStream licenseStream = new FileStream("GroupDocs.Signature.lic", FileMode.Open))
{
    GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
    lic.SetLicense(licenseStream);
}
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Signature](../../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
