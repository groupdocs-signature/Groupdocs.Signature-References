---
title: Delete
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Elimina la firma pasadaBaseSignaturegroupdocs.signature.domain/basesignature del documento.
type: docs
weight: 110
url: /es/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Elimina la firma pasada[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) del documento.

```csharp
public bool Delete(BaseSignature signature)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signature | BaseSignature | Objeto de firma que se eliminará del documento. |

### Valor_devuelto

Devuelve verdadero si la operación fue exitosa.

### Observaciones

**Aprende más**

* Más sobre cómo eliminar la firma electrónica del documento en C#: [Cómo eliminar la firma electrónica del documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casos de uso avanzado de eliminación de firmas electrónicas de documentos: [Cómo eliminar diferentes tipos de firmas electrónicas del documento en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Elimina la lista aprobada de firmas[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) del documento.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatures | List`1 | Lista de firmas a eliminar del documento. |

### Valor_devuelto

Devuelve EliminarResultado[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con una lista de firmas eliminadas con éxito y fallidas.

### Observaciones

**Aprende más**

* Más sobre cómo eliminar la firma electrónica del documento en C#: [Cómo eliminar la firma electrónica del documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casos de uso avanzado de eliminación de firmas electrónicas de documentos: [Cómo eliminar diferentes tipos de firmas electrónicas del documento en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Elimina firmas de cierto tipo[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) del documento. Solo las firmas que se agregaron mediante el método Firmar y se marcaron como Firmas[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) será eliminado. Se admiten los siguientes tipos de firma: texto, imagen, digital, código de barras, código QR

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatureType | SignatureType | El tipo de firmas que se eliminarán del documento. |

### Valor_devuelto

Devuelve EliminarResultado[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con una lista de firmas eliminadas con éxito y fallidas.

### Observaciones

**Aprende más**

* Más sobre cómo eliminar la firma electrónica del documento en C#: [Cómo eliminar firmas electrónicas con un tipo específico del documento con GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Casos de uso avanzado de eliminación de firmas electrónicas de documentos: [Cómo eliminar diferentes tipos de firmas electrónicas del documento en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Elimina las firmas de la lista de ciertos tipos[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) del documento. Solo las firmas que se agregaron mediante el método Firmar y se marcaron como Firmas[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) será eliminado. Se admiten los siguientes tipos de firma: texto, imagen, digital, código de barras, código QR

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatureTypes | List`1 | La lista de tipos de firmas que se eliminarán del documento. |

### Valor_devuelto

Devuelve EliminarResultado[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con una lista de firmas eliminadas con éxito y fallidas.

### Observaciones

**Aprende más**

* Más sobre cómo eliminar la firma electrónica del documento en C#: [Cómo eliminar firmas electrónicas con un tipo específico del documento con GroupDocs.Signature](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Casos de uso avanzado de eliminación de firmas electrónicas de documentos: [Cómo eliminar diferentes tipos de firmas electrónicas del documento en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Elimina la firma por su ID de firma específico del documento.

```csharp
public bool Delete(string signatureId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatureId | String | El Id de la firma que se eliminará del documento. |

### Valor_devuelto

Devuelve verdadero si la operación fue exitosa.

### Observaciones

**Aprende más**

* Más sobre cómo eliminar la firma electrónica del documento en C#: [Cómo eliminar la firma electrónica del documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casos de uso avanzado de eliminación de firmas electrónicas de documentos: [Cómo eliminar diferentes tipos de firmas electrónicas del documento en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Elimina la lista aprobada de firmas[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) del documento.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| signatureIds | List`1 | Lista de los identificadores de las firmas a eliminar del documento. |

### Valor_devuelto

Devuelve EliminarResultado[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) con una lista de firmas eliminadas con éxito y fallidas.

### Observaciones

**Aprende más**

* Más sobre cómo eliminar la firma electrónica del documento en C#: [Cómo eliminar la firma electrónica del documento con GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Casos de uso avanzado de eliminación de firmas electrónicas de documentos: [Cómo eliminar diferentes tipos de firmas electrónicas del documento en C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ver también

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* espacio de nombres [GroupDocs.Signature](../../signature)
* asamblea [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
