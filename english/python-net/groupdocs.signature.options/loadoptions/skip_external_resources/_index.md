---
title: skip_external_resources property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that stops the document from loading external resources."
type: docs
url: /python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

The flag that stops the document from loading external resources. The default value is True; external resources are not loaded except those that match [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

A document can refer to resources stored outside it, such as linked images, pictures inserted by an INCLUDEPICTURE field, linked pictures in presentations and spreadsheets, and images and style sheets referenced by an SVG image. Loading such a resource makes the library request its address. On a server that processes untrusted documents, a document could use this to make the server send requests to internal addresses (server‑side request forgery), and a UNC or `file://` path could cause Windows to send the account's NTLM credentials to another host. On an offline or air‑gapped installation, the requests fail or wait for a timeout.

Resources that are skipped are not drawn in page previews or in documents saved as images, and image, barcode, and QR‑code search does not see them. Set this property to False only for trusted documents, and prefer allowing specific addresses with [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

The setting applies to word processing documents, presentations, spreadsheets, and SVG images, including documents inside archives. For SVG images, references that are not allowed are removed from the image before it is read, and an SVG image that is not well‑formed XML is rejected. The setting does not control certificate revocation checks, time‑stamp servers, or licensing.

This property replaces [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), which has the opposite meaning.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### See Also
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
