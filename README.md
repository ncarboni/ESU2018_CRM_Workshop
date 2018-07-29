## Workshop



Material of the Workshop "**Integrating Human Science Data using CIDOC-CRM as Formal Ontology: a practical approach**" held in collaboration with [Leo Zorc](https://github.com/bitno) at the 9th European Summer University in Digital Humanities Culture & Technology, organised by the University of Leipzig (Germany) 17.-27.07.2018



### Workshop Abstract

Human Science is a multifaceted field which sometimes struggles to find a common language to discuss as well as integrate the results of its research. This issue is fairly well represented in the technological solutions that each of the diverse disciplines is producing and on the body of data which gets released to the public. What can we do to harmonise and integrate the product of researchers coming from so many domains? Is there a way to build up a corpus of knowledge able to combine such a variegated set of information? Linked Data, a way of constructing data which uses explicit semantics, could be the solution we are searching for.

How does data become Linked Data? What are the steps one should take to exploit this methodology and which tools are needed to transform existing datasets into semantic ones?

In this workshop we will introduce the participants to the concept of linked data and to a selection of data curation tools that can be employed for re-using and integrating data from across data silos, giving a practical insight in how we have been doing exactly that. Existing data usually needs some care and work, in order to be ready for the transformation. Not only are we going to demonstrate how this can be done, but we will emphasize how much value this important step can add to each project.

The overall proposed workflow for mapping, transforming and generating linked data will be based on two main software solutions, which will be discussed and demonstrated: 3M and Karma.

We will begin the workshop with a brief but comprehensive introduction to formal ontologies, specifically focusing on CIDOC-CRM, which not only has a long history, but has had a huge uptick in recent months with many actual implementations.

Even though we will use two different photographic archives as our main datasets for this workshop, we encourage all participants to bring their own data, as lots of hand-on exercises will enable each and everyone to reproduce all the necessary steps on their own. Should it not be possible to supply own datasets, we will have alternatives from several disciplines available.



## Workshop Material

### Slides & Files

The slides can be found under the folder slides/

The [3M](3M/) workshop material include:

* A sample mapping in [X3ML](3M/example_mapping.x3ml)
* The generator policy used for [3M](3M/example_generator-policy.xml)
* A modified version of [CRMext4SKOSandLabel](3M/CRMext4SKOSandLabel_v1.38.rdf) which include:
  * Mapping with [WGS84 Ontology](https://www.w3.org/2003/01/geo/)
  * Possibility to add owl:sameas statements for each CRM Entity
  * Possibility to add rdfs:label for each CRM Entity



All the material is freely available and reusable.



### Resource links

 

[3M](http://139.91.183.3/3M): Mapping Editor developed by the FORTH institute 

[X3ML](https://github.com/isl/x3ml): Java Application developed by FORTH institute for mapping XML files to CRM and trasform them in RDF/TTL/N3

[Mr Data Converter](https://shancarter.github.io/mr-data-converter/): Free CSV to XML Converter online

[ResearchSpace](http://researchspace.org): ResearchSpace is a collaborative Semantic Web environment used to connects information about people, places, periods, things and concepts from different sources without losing their original context, and allows the community to enrich information as a collaborative activity

[RDF2RDF](http://www.l3s.de/~minack/rdf2rdf/): Free Java application for converting RDF files





## References

#### Ontology & Semantic Web

Allemang, D., & Hendler, J. A. (2011). *Semantic Web for the Working Ontologist - Effective Modeling in RDFS and OWL*, Second Edition. (2nd ed.). Morgan Kaufmann. 

Hoekstra, R. (2009). *Ontology Representation - Design Patterns and Ontologies that Make Sense*. IOS Press, Amsterdam. 

Antoniou, G., Groth, P., van Harmelen, F., Hoekstra, R. (2012). *A Semantic Web Primer* (3rd ed.). The MIT Press.

#### Heritage & CIDOC-CRM

*CIDOC Conceptual Reference Model*. (2015). *CIDOC Conceptual Reference Model* (6 ed.)

Bruseker, G., Carboni, N., & Guillem, A. (2017). Cultural Heritage Data Management: The Role of Formal Ontology and CIDOC CRM. In M. L. Vincent, V. M. Lopez-Menchero, M. Ioannides, & T. E. Levy (Eds.), *Heritage and Archaeology in the DigitalAge* (pp. 93–131). Springer, Cham. http://doi.org/10.1007/978-3-319-65370-9_6 

Oldman, D., & Doerr, M. (2014). *The CIDOC Conceptual Reference Model (CIDOC-CRM): PRIMER* (1st ed.). 

Doerr, M. (2002). The CIDOC CRM: an ontological approach to semantic interoperability of metadata. AI Magazine. 

Doerr, M., & Hiebel, G. (2013). *CRMgeo: Linking the CIDOC CRM to GeoSPARQL through a Spatiotemporal Refinement* (No. ICS-FORTH/TR-435). ICS-FORTH. 

Paveprime Ltd. (2014). *CRMinf: the Argumentation Model An Extension of CIDOC-CRM to support argumentation*. 

Doerr, M., & Theodoridou, M. (2014). *CRMdig An Extension of CIDOC-CRM to support provenance metadata* (3rd ed.). 







