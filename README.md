# Almes Core Reference Guide
Preliminary repository for the Almes Core vocabulary
| Property | Value |
| ------------- | ------------- |
| Title  | Agriculture and Livestock Metadata Elements Set (Almes Core)  |
| Creator  | C4AI AgriBio Data Managment Team  |
| Identifier  | http://purl.org/almescore |
| Latest Version | http://purl.org/almescore |
| Version History | uri here |
| Document Status | draft |
| Description | Este documento é a versão mais atualizada da especificação de todos os termos de metadados mantidos pelo C4AI AgriBio Data Managment Team, incluindo classes, propriedades, esquemas de codificação de vocabulário, e esquemas de codificação de sintaxe |
| Namespace | http://purl.org/almescore |
| Prefix | alm: |

# Normative namespaces
Namespaces and prefixes used in normative parts of this recommendation are shown in the following table.
| Prefix | Namespace |
| ------------- | ------------- |
| alm | http://purl.org/almescore |
| dc  | http://purl.org/dc/elements/1.1/  |
| sdo  | https://schema.org/docs/schemas.html  |
| dcat | http://www.w3.org/ns/dcat# |
| dct | http://purl.org/dc/terms/ |

# Index of Terms


##Resource
##Dataset
##Agent


### productGroup

| Term name | alm:productGroup |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/productGroup  |
| Definition  | A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.  |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: grain, vegetables, meat. |
| Broader Match | <a href="https://schema.org/ProductGroup">sdo:productGroup</a> |

### theme
| Term name | alm:theme |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  |  http://purl.org/almescore/theme |
| Definition | Indicates the main theme investigated in the economic statistical operation. |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: agriculture, livestock, forest production, fishing, aquaculture. |
| References | https://metadados.ibge.gov.br/consulta/estatisticos/temas |
| Broader Match | <a href="http://www.w3.org/ns/dcat#theme">dcat:theme</a> |

### product
| Term name | alm:product |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/product  |
| Definition | Name of the agricultural or livestock product targeted by the commercial operation.                                                    |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle. |
| Broader Match | <a href="https://schema.org/Product">sdo:product</a> |

### verbatimName
| Term name | alm:verbatimName |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/verbatimName  |
| Comment | Deprecated. Replaced by <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#title">dc:title</a>. |

### title
| Term name | dc:title |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/elements/1.1/title  |
| Definition | A name given to the resource.   |

### language
| Term name | dct:language |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/language  |
| Definition | A language of the resource. |
| Comment | Recommended practice is to use either a non-literal value representing a language from a controlled vocabulary such as ISO 639-2 or ISO 639-3, or a literal value consisting of an IETF Best Current Practice 47 <a href="https://www.rfc-editor.org/info/bcp47">(IETF-BCP47)</a> language tag. |

### publisher
| Term name | dc:publisher |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/elements/1.1/publisher  |
| Definition | An entity responsible for making the resource available. |
| Comment | Examples of a Publisher include a person, an organization, or a service. Typically, the name of a Publisher should be used to indicate the entity. |

### creator
| Term name | dc:creator |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/elements/1.1/creator  |
| Definition | 	An entity primarily responsible for making the resource. |
| Comments| Examples of a Creator include a person, an organization, or a service. Typically, the name of a Creator should be used to indicate the entity. |

### references
| Term name | dct:references |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/references |
| Comment | Deprecated in Almes Core schema (still in use in Dublin Core). Replaced by <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accessURL">dcat:accessURL</a>. |

### accessURL
| Term name | dcat:accessURL |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://www.w3.org/ns/dcat#accessURL |
| Definition | A URL of the resource that gives access to a distribution of the dataset. E.g. landing page, feed, SPARQL endpoint. |

### description
| Term name | dcat:description |
| URI  | http://purl.org/dc/terms/description |
| Definition | 	Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource. |

### dataType
| Term name | sdo:dataType |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/DataType |
| Comment | Deprecated in Almes Core schema (still in use in Schema.org). |

### frequency
| Term name | sdo:frequency |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/frequency |
| Comment | Deprecated in Almes Core schema (still in use in Schema.org). Replaced by <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accrualPeriodicity">dct:accrualPeriodicity</a>. |

### accrualPeriodicity
| Term name | dct:accrualPeriodicity |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/accrualPeriodicity |
| Definition | The frequency with which items are added to a collection. |
| Comment | Recommended practice is to use a value from the Collection Description Frequency Vocabulary <a href="https://www.dublincore.org/specifications/dublin-core/collection-description/frequency/">(DCMI-COLLFREQ)</a>. 

### location
| Term name | sdo:location |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/location |
| Definition | The location of, for example, where an event is happening, where an organization is located, or where an action takes place. |
| Comment | Recommended practice is to use a value from a controlled vocabulary such as <a href="https://www.geonames.org/">Geonames.org</a>. 

### startDate
| Term name | sdo:startDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/startDate |
| Definition | The start date and time of the item (in ISO 8601 date format). |

### endDate
| Term name | sdo:endDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/endDate |
| Definition | The end date and time of the item (in ISO 8601 date format). |

### modified
| Term name | dct:modified |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/modified |
| Definition | Date on which the resource was changed. |
| Comment | Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty. |

### license
| Term name | dct:license |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/license |
| Definition | A legal document giving official permission to do something with the resource. |
| Comment | Recommended practice is to identify the license document with a URI. If this is not possible or feasible, a literal value that identifies the license may be provided. |

### rights
| Term name | dct:rights |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/elements/1.1/rights |
| Definition | Information about rights held in and over the resource. |
| Comment | Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights. |

### statisticalMethod
| Term name | alm:statisticalMethod |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/statisticalMethod |
| Definition | Summary of the methods used for the process of obtaining data for the production of the series. |
| Comment| Recommended best practice is to indicate the published resource URI in an open access format. |


