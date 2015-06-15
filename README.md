# dnb
German National Library's contributions to Linked Library Data Doers on Github

The examples provided have been converted from Pica+ to RDF/XML. They are available online from URIs
	http://d-nb.info/<ID>/about/lds 

The Tolkien example of "Der Herr der Ringe" and its first volume "Die Gefährten" is modelled internally according to the model of hierarchical description.  The single volume is described in a record for a part with dependent title (MARC leader position 19 "Multipart resource record level" value "c"), and the resource as a whole is described in a set record (MARC leader / 19 value "a").  Information regarding the resource as a whole is partly included into the representation of the single volume.  Both resources are linked, from the record for the part to the record for the whole ("bottom up").  Background of this hierarchical model is available in the two papers written by the German National Library for discussion at the MARBI meetings in 2007, online at
	http://www.loc.gov/marc/marbi/2007/2007-dp01.html#section25
and
	http://www.loc.gov/marc/marbi/2007/2007-06.html#p5 

The Tolkien example of "Der Hobbit" describes a single monographic resource.

Please note that the examples do not represent FRBR WEMI levels. From 1 October 2015 on the DNB will produce RDA composite description records.

The bibliographic data is modeled in accordance with the DINI-AG-KIM's title data working group's (includes representatives from German speaking community) recommendations for the RDF representation of bibliographic data:
	http://nbn-resolving.de/urn:nbn:de:kobv:11-100217673 (German only, pdf, 1.1 MB)

There are some additional elements expressed in the DNB Linked Data Service. The complete mapping of the DNB bibliographic data is available here
	http://www.dnb.de/SharedDocs/Downloads/EN/DNB/service/linkedDataModellierungTiteldaten.pdf

The model used to represent the authority data of the German Integrated Authority file (GND) is documented here:
	http://d-nb.info/standards/elementset/gnd#

Both resources are linked to authority data, namely to persons (author, translators).  From the person entities we have included into the set of examples further linked entities describing places (place of birth, place of death), professions, and personal relationships (son, grandson), if available.





