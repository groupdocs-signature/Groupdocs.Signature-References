---
title: DigitalSignOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Representa las opciones de firma digital.
type: docs
weight: 1260
url: /es/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Representa las opciones de firma digital.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Inicializa una nueva instancia de la clase DigitalSignOptions con valores predeterminados. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Inicializa una nueva instancia de la clase DigitalSignOptions con flujo de certificado. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Inicializa una nueva instancia de la clase DigitalSignOptions con archivo de certificado. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Inicializa una nueva instancia de la clase DigitalSignOptions con flujo de certificado y flujo de imagen. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Inicializa una nueva instancia de la clase DigitalSignOptions con flujo de certificado y archivo de imagen. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Inicializa una nueva instancia de la clase DigitalSignOptions con un archivo de certificado y un flujo de imágenes. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Inicializa una nueva instancia de la clase DigitalSignOptions con archivo de certificado y archivo de imagen. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Poner firma en todas las páginas del documento. Esta propiedad solo se puede utilizar para formatos de imagen de varios fotogramas (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspecto de firma adicional. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Especificar configuración de borde |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Obtiene o establece la ruta del archivo del certificado digital. Esta propiedad se usa solo si no se especifica CertificateStream. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Obtiene o establece el flujo de certificado digital. Si se especifica esta propiedad, siempre se usa en su lugar CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Obtiene o establece la firma del contacto. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Obtener o establecer el tipo de documento de las opciones de firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Extensiones de firma. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altura de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) TamañoMedidaTipo). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Alineación horizontal de la firma en la página del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Obtiene o establece la ruta del archivo de imagen de la firma. Esta propiedad se usa solo si no se especifica ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Obtiene o establece el flujo de imagen de firma. Si se especifica esta propiedad, siempre se usa en su lugar ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posición X izquierda de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si no se especifica la alineación horizontal). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Obtiene o establece la ubicación de la firma. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Izquierda y Superior. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Obtiene o establece el espacio entre los bordes del Signo y del Documento. (funciona SOLO si se especifica la alineación horizontal o vertical). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Obtiene o establece el tipo de medida (píxeles, porcentajes o milímetros) para Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para firmar. El valor mínimo y predeterminado es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opciones para especificar páginas a firmar. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Obtiene o establece la contraseña del certificado digital. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Obtiene o establece el motivo de la firma. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectángulo de área para colocar la imagen en el documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Ángulo de rotación de la firma en la página del documento (sentido horario). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Obtiene o establece las propiedades de la firma digital del documento. Para firmar documentos PDF, es posible establecer propiedades avanzadas utilizando una instancia de[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Obtener el tipo de firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo de medida (píxeles, porcentajes o milímetros) para las propiedades Ancho y Alto. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modo de extensión en la página del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posición Y superior de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros, consulte[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funciona si no se especifica la alineación vertical). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Obtiene o establece la transparencia de la firma (valor de 0,0 (opaco) a 1,0 (transparente)). El valor predeterminado es 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Alineación vertical de la firma en la página del documento. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Obtiene o establece la visibilidad de la firma. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ancho de la firma en la página del documento en valores de medida (píxeles, porcentajes o milímetros)[`MeasureType`](../../groupdocs.signature.domain/measuretype) TamañoMedidaTipo). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | tipo XAdES[`XAdESType`](./xadestype) . El valor predeterminado es Ninguno (XAdES está desactivado). En este momento, el tipo de firma XAdES solo se admite para documentos de hoja de cálculo. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Obtiene o establece la posición de orden Z de la firma de texto. Determina el orden de visualización de las firmas superpuestas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Borra los recursos internos |

### Observaciones

**Aprende más**

* Uso básico de creación de firma electrónica digital por GroupDocs. Firma: [Cómo firmar un documento con firma digital](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Uso avanzado de configuración de Firma electrónica digital con GroupDocs.Firma: [Uso avanzado para firmar documentos electrónicos con firma digital y configuraciones adicionales](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Ver también

* class [ImageSignOptions](../imagesignoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
