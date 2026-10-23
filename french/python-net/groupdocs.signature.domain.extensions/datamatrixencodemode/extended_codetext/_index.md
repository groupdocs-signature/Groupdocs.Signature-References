---
title: "Champ EXTENDED_CODETEXT"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le mode ExtendedCodetext permet de changer manuellement les schémas d'encodage dans le code-texte."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

Le mode ExtendedCodetext permet de changer manuellement les schémas de codage dans le code-texte. Format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Les schémas de codage autorisés sont : EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Exemple de code-texte étendu : @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Tous les barres obliques inverses (\) doivent être doublés dans le texte.

### Valeur
`12`

### Voir aussi
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
