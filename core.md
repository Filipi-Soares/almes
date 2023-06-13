# Almes Core Reference Guide

| Property | Value |
| ------------- | ------------- |
| Title  | Agriculture and Livestock Metadata Elements Set (Almes Core)  |
| Creator  | C4AI AgriBio Data Managment Team  |
| Identifier  | http://purl.org/almescore |
| Latest Version | http://purl.org/almescore |
| Version History | https://github.com/Filipi-Soares/almes/blob/main/deprecatedElements.md |
| Last updated | 2023-06-13 |
| Document Status | valid |
| Description | This document contains the most up-to-date version of the Agriculture and Livestock Metadata Element Set (Almes Core), maintained by the center for Artificial Intelligence (C4AI) AgriBio Data Management Team, including classes, properties, vocabulary encoding schemes, and syntax encoding schemes.  |


# Normative namespaces
Namespaces and prefixes used in normative parts of this recommendation.
| Prefix | Namespace |
| ------------- | ------------- |
| alm | http://purl.org/almescore |
| dc  | http://purl.org/dc/elements/1.1/  |
| sdo  | https://schema.org/docs/schemas.html  |
| dcat | http://www.w3.org/ns/dcat# |
| dct | http://purl.org/dc/terms/ |
| foaf| http://xmlns.com/foaf/0.1/ |

# Index of Terms
<a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#resource">Resource (Class)</a>


<a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#title">title (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#description">description (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#publisher">publisher (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#creator">creator (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#modified">modified (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#modified">version (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#language">language (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#license">license (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#rights">rights (property)</a>.

<a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#agent">Agent (Class)</a>


<a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#name">name (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#homepage">homepage (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#e-mail">e-mail (property)</a>. 


<a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#dataset">Dataset (Class)</a>


<a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#productGroup">productGroup (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#product">product (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#theme">theme (property)</a>. <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accessURL">accessURL (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accrualPeriodicity">accrualPeriodicity (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#referenceQuantity">referenceQuantity (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#location">location (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#startDate">startDate (property)</a>. <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accessURL">accessURL (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#endDate">endDate (property)</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#statisticalMethod">statisticalMethod (property)</a>; 

[![Green Button](https://placehold.it/120x30/00ff00/000000?text=Green+Button)](https://example.com/green)
[![Blue Button](https://placehold.it/120x30/0000ff/ffffff?text=Blue+Button)](https://example.com/blue)



## Resource
| Term name | dcat:Resource |
| ------------- | ------------- |
| Type of Term  | Class  |
| URI  | https://www.w3.org/ns/dcat#Resource  |
| Definition  | Resource published or curated by a single agent.  |

### title
| Term name | dc:title |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/elements/1.1/title  |
| Definition | A name given to the resource.   |

### description
| Term name | dct:description |
| ------------- | ------------- |
| URI  | http://purl.org/dc/terms/description |
| Definition | 	Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource. |

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

### modified
| Term name | dct:modified |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/modified |
| Definition | Date on which the resource was changed. |
| Comment | Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty. |

### version
| Term name | dct:hasVersion |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/hasVersion |
| Definition | A related resource that is a version, edition, or adaptation of the described resource. |
| Comment | Changes in version imply substantive changes in content rather than differences in format. This property is intended to be used with non-literal values. This property is an inverse property of Is Version Of. |

### language
| Term name | dct:language |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/language  |
| Definition | A language of the resource. |
| Comment | Recommended practice is to use either a non-literal value representing a language from a controlled vocabulary such as ISO 639-2 or ISO 639-3, or a literal value consisting of an IETF Best Current Practice 47 <a href="https://www.rfc-editor.org/info/bcp47">(IETF-BCP47)</a> language tag. |

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

## Agent
| Term name | foaf:Agent |
| ------------- | ------------- |
| Type of Term  | Class  |
| URI  | http://xmlns.com/foaf/0.1/#term_Agent |
| Definition  | An agent (eg. person, group, software or physical artifact).  |
 
### name
| Term name | foaf:name |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://xmlns.com/foaf/0.1/#term_name |
| Definition  | A name for some thing.  |
| subproperty of | <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#creator">dc:creator</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#publisher">dc:publisher</a> | 

### homepage
| Term name | foaf:homepage |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://xmlns.com/foaf/0.1/#term_homepage |
| Definition  | A homepage for some thing.  |
| subproperty of | <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#creator">dc:creator</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#publisher">dc:publisher</a> | 

### e-mail
| Term name | foaf:mbox |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://xmlns.com/foaf/0.1/#term_mbox |
| Definition  | A personal mailbox, ie. an Internet mailbox associated with exactly one owner, the first owner of this mailbox. This is a 'static inverse functional property', in that there is (across time and change) at most one individual that ever has any particular value for foaf:mbox.  |
| subproperty of | <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#creator">dc:creator</a>; <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#publisher">dc:publisher</a> |  


## Dataset
| Term name | dcat:Dataset |
| ------------- | ------------- |
| Type of Term  | Class  |
| URI  | https://www.w3.org/ns/dcat#Dataset |
| Definition  | A collection of data, published or curated by a single agent, and available for access or download in one or more representations.  |

### productGroup

| Term name | alm:productGroup |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/productGroup  |
| Definition  | A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.  |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: grain, vegetables, meat. |
| Broader Match | <a href="https://schema.org/ProductGroup">sdo:productGroup</a> |

### product
| Term name | alm:product |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/product  |
| Definition | Name of the agricultural or livestock product type targeted by the commercial operation.                                                    |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle. |
| Broader Match | <a href="https://schema.org/Product">sdo:product</a> |

### theme
| Term name | alm:theme |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  |  http://purl.org/almescore/theme |
| Definition | Indicates the main theme investigated in the economic statistical operation. |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: agriculture, livestock, forest production, fishing, aquaculture. |
| References | https://metadados.ibge.gov.br/consulta/estatisticos/temas |
| Broader Match | <a href="http://www.w3.org/ns/dcat#theme">dcat:theme</a> |

### verbatimName
| Term name | alm:verbatimName |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/verbatimName  |
| Comment | Deprecated. Replaced by <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#title">dc:title</a>. |

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

### referenceQuantity
| Term name | sdo:referenceQuantity |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/referenceQuantity |
| Definition | The reference quantity for which a certain price applies, e.g. 1 EUR per 4 kWh of electricity. This property is a replacement for unitOfMeasurement for the advanced cases where the price does not relate to a standard unit. |

### location
| Term name | sdo:location |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/referenceQuantity |
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

### statisticalMethod
| Term name | alm:statisticalMethod |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/statisticalMethod |
| Definition | Summary of the methods used for the process of obtaining data for the production of the series. |
| Comment| Recommended best practice is to indicate the published resource URI in an open access format. |

