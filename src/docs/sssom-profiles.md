## SSSOM Profiles

- [Literal Mappings](#literal)

<a id="literal"></a>

### Literal Mappings

The SSSOM profile for literal mappings is a version of SSSOM that allows the dissemination and standardisation of mappings between identifers and literals.

As of 01.08.2023, the first version of this profile has been published, and it is still subject to change. We recommend to reach out on the [SSSOM issue tracker](https://github.com/mapping-commons/sssom/issues) if you are interested in using the literal profile. Note: we dont expect there to be any major breaking changes.

#### Open Annotation Data Model or Web Annotation Ontology
The W3C propose an ontology to represent annotation: Web Annotation Ontology also known as Open Annotation (OA) (https://www.w3.org/TR/annotation-vocab/#introduction). The ontology become a W3C recommendation in 2017.
An annotation is the result of adding information to a document (textual, image, ...). An annotation may have several purposes: add a note to a part of the document, add a topic in order to retrieve quicky the annotated paragraph, identify an external entity that is mentioned in the part of the text of the document ... OA identify 13 differents purposes of annotation.
in OA an annotation links a document (the target) to something else (the body). The body may be represented by an URI from an external ressource.

**Demand better docs now**: https://github.com/mapping-commons/sssom/issues

- [Slides](https://docs.google.com/presentation/d/1mBZK6KS7JgmXlEtszQiOa_Cl7SXg_Z8wRp0tZHaL57Y/edit)
- [PR](https://github.com/mapping-commons/sssom/pull/235)
- [Recording/discussion](events/mc2023.md)
