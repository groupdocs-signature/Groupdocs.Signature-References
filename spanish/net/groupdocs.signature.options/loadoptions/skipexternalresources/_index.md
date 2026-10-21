---
title: "SkipExternalResources"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece una bandera que impide que el documento cargue recursos externos. El valor predeterminado es true, los recursos externos no se cargan excepto aquellos que coinciden con WhitelistedResourcesgroupdocs.signature.options/loadoptions/whitelistedresources."
type: docs
weight: 50
url: /es/net/groupdocs.signature.options/loadoptions/skipexternalresources/
---
## LoadOptions.SkipExternalResources property

Obtiene o establece una bandera que impide que el documento cargue recursos externos. El valor predeterminado es true: los recursos externos no se cargan, excepto aquellos que coinciden con [`WhitelistedResources`](../whitelistedresources).

```csharp
public bool SkipExternalResources { get; set; }
```

### Observaciones

Un documento puede referirse a recursos almacenados fuera de él: imágenes vinculadas, imágenes insertadas mediante un campo INCLUDEPICTURE, imágenes vinculadas en presentaciones y hojas de cálculo, y imágenes y hojas de estilo a las que hace referencia una imagen SVG. Cargar dicho recurso hace que la biblioteca solicite su dirección. En un servidor que procesa documentos no confiables, un documento podría usar esto para hacer que el servidor envíe solicitudes a direcciones internas (falsificación de solicitudes del lado del servidor), y una ruta UNC o file:// podría hacer que Windows envíe las credenciales NTLM de la cuenta a otro host. En una instalación sin conexión o aislada, las solicitudes fallan o esperan a que se agote el tiempo de espera.

Los recursos que se omiten no se dibujan en las vistas previas de página ni en los documentos guardados como imágenes, y la búsqueda de imágenes, códigos de barras y códigos QR no los ve. Establezca esta propiedad en false solo para documentos de confianza, y prefiera permitir direcciones específicas con [`WhitelistedResources`](../whitelistedresources).

La configuración se aplica a documentos de procesamiento de texto, presentaciones, hojas de cálculo e imágenes SVG, incluidos los documentos dentro de archivos. Para imágenes SVG, las referencias que no están permitidas se eliminan de la imagen antes de que se lea, y una imagen SVG que no es XML bien formado se rechaza. La configuración no controla las verificaciones de revocación de certificados, los servidores de sellado de tiempo ni la licencia.

Esta propiedad reemplaza LoadExternalResources, que tiene el significado opuesto.

### Ver también

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
