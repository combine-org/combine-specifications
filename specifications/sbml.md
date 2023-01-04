# Systems Biology Markup Language
<img src="./files/sbml.png" alt="SBML logo" height="70"/>

[The Systems Biology Markup Language (SBML)](https://sbml.org) is a computer-readable XML format for representing models of biological processes. SBML is suitable for, but not limited to, models using a process description approach.

## Normative definitions
SBML is defined in a set of specification documents that describe the elements of the language, its syntax, and provide validation rules. SBML Levels are intended to coexist. For example, SBML Level 3 does not render Level 2 obsolete, and Level 2-compatible models and software tools still continue to be used. Within each Level, the latest Version should be used.

The latest specifications are:

* [SBML Level 3 Version 2 Core Release 2](https://identifiers.org/combine.specifications:sbml.level-3.version-2.core)
* SBML Level 3 Hierarchical Model Composition Package Version 1 Release 3
* SBML Level 3 Distributions Package Version 1 Release 1
* SBML Level 3 Flux Balance Constraints Package Version 2 Release 1
* SBML Level 3 Groups Package Version 1 Release 1
* SBML Level 3 Layout Package Version 1 Release 1
* SBML Level 3 Multistate Multicomponent Model Package Version 1 Release 2
* SBML Level 3 Qualitative Model Package Version 1 Release 1
* SBML Level 3 Render Package Version 1 Release 1
* SBML Level 3 Spatial Package Version 1 Release 1
* SBML Level 2 Version 5 release 1
* SBML Level 1 Version 2

## Governance
SBML development is coordinated by an [editorial board](https://sbml.org/SBML.org:About#The_SBML_Editors_and_the_Chair) elected by the community and a [team of developers](https://sbml.org/SBML.org:About#The_SBML_Team).

## Communication
SBML development is discussed on the mailing list [sbml-discuss@googlemail.com](https://groups.google.com/g/sbml-discuss).

## Software support
Many [data resources and software](https://sbml.org/SBML_Software_Guide) support SBML. This includes [APIs and converters](https://sbml.org/Downloads).

## Contact
For information about SBML itself, contact [sbml-discuss@googlemail.com](https://groups.google.com/g/sbml-discuss). For information about SBML development and governance, contact [sbml-editors@caltech.edu](mailto:sbml-editors@caltech.edu)

## How to cite SBML
Keating SM, Waltemath D, König M, Zhang F, Dräger A, Chaouiya C, Bergmann FT, Finney A, Gillespie CS, Helikar T, Hoops S, Malik-Sheriff RS, Moodie SL, Moraru II, Myers CJ, Naldi A, Olivier BG, Sahle S, Schaff JC, Smith LP, Swat MJ, Thieffry D, Watanabe L, Wilkinson DJ, Blinov ML, Begley K, Faeder JR, Gómez HF, Hamm TM, Inagaki Y, Liebermeister W, Lister AL, Lucio D, Mjolsness E, Proctor CJ, Raman K, Rodriguez N, Shaffer CA, Shapiro BE, Stelling J, Swainston N, Tanimura N, Wagner J, Meier-Schellersheim M, Sauro HM, Palsson B, Bolouri H, Kitano H, Funahashi A, Hermjakob H, Doyle JC, Hucka M; SBML Level 3 Community members. SBML Level 3: an extensible format for the exchange and reuse of biological models. Mol Syst Biol. 2020 Aug;16(8):e9110. doi: [10.15252/msb.20199110](https://doi.org/10.15252/msb.20199110). PMID: [32845085](https://identifiers.org/pubmed/32845085); PMCID: PMC8411907.

Hucka M., Bolouri H., Finney A., Sauro H.M., Doyle J.C., Kitano H., and the rest of the Systems Biology Software Developer's Forum: Arkin A.P., Bornstein B.J., Bray D., Cornish-Bowden A., Cuellar A.A., Dronov S., Ginkel M., Gor V., Goryanin I.I., Hedley W.J., Hodgman T.C., Hunter P.J., Juty N.S., Kasberger J.L., Kremling A., Kummer U., Le Novère N., Loew L.M., Lucio D., Mendes P., Mjolsness E.D., Nakayama Y., Nelson M.R., Nielsen P.F., Sakurada T., Schaff J.C., Shapiro B.E., Shimizu T.S., Spence H.D., Stelling J., Takahashi K., Tomita M., Wagner J., Wang J. The Systems Biology Markup Language (SBML): A Medium for Representation and Exchange of Biochemical Network Models. Bioinformatics (2003), 19: 524-531. [https://identifiers.org/pubmed/12611808](https://identifiers.org/pubmed/12611808)

## History
Late in the year 1999 through early 2000, with funding from the Japan Science and Technology Corporation (JST), Hiroaki Kitano and John C. Doyle assembled a small team of researchers to work on developing better software infrastructure for computational modeling in systems biology. Hamid Bolouri was the leader of the development team, which consisted of Andrew Finney, Herbert Sauro, and Michael Hucka. Bolouri identified the need for a framework to enable interoperability and sharing between the different simulation software systems for biology in existence during the late 1990's, and he organized an informal workshop in December 1999 at the California Institute of Technology to discuss the matter. In attendance at that workshop were the groups responsible for the development of DBSolve, E-Cell, Gepasi, Jarnac, StochSim and The Virtual Cell. Separately, earlier in 1999, some members of these groups also had discussed the creation of a portable file format for metabolic network models in the BioThermoKinetics (BTK) group. The same groups who attended the first Caltech workshop met again on April 28-29, 2000, at the first of a newly-created meeting series called Workshop on Software Platforms for Systems Biology. It became clear during the second workshop that a common model representation format was needed to enable the exchange of models between software tools as part of any functioning interoperability framework, and the workshop attendees decided the format should be encoded in XML.

The Caltech ERATO team developed a proposal for this XML-based format and circulated the draft definition to the attendees of the 2nd Workshop on Software Platforms for Systems Biology in August, 2000. This draft underwent extensive discussion over mailing lists and during the 2nd Workshop on Software Platforms for Systems Biology, held in Tokyo, Japan, in November 2000 as a satellite workshop of the ICSB 2000 conference. After further revisions, discussions and software implementations, the Caltech team issued a specification for SBML Level 1, Version 1 in March, 2001.

SBML Level 2 was conceived at the 5th Workshop on Software Platforms for Systems Biology, held in July 2002, at the University of Hertfordshire, UK. By this time, far more people were involved than the original group of SBML collaborators and the continued evolution of SBML became a larger community effort, with many new tools having been enhanced to support SBML. The workshop participants in 2002 collectively decided to revise the form of SBML in Level 2. The first draft of the Level 2 Version 1 specification was released in August 2002, and the final set of features was finalized in May 2003 at the 7th Workshop on Software Platforms for Systems Biology in Ft. Lauderdale, Florida.

The next iteration of SBML took two years in part because software developers requested time to absorb and understand the larger and more complex SBML Level 2. The inevitable discovery of limitations and errors led to the development of SBML Level 2 Version 2, issued in September 2006. By this time, the team of SBML Editors (who reconcile proposals for changes and write a coherent final specification document) had changed and now consisted of Andrew Finney, Michael Hucka and Nicolas Le Novère.

SBML Level 2 Version 3 was published in 2007 after countless contributions by and discussions with the SBML community. 2007 also saw the election of two more SBML Editors as part of the introduction of the modern SBML Editor organization in the context of the SBML development process.

SBML Level 2 Version 4 was published in 2008 after certain changes in Level 2 were requested by popular demand. (For example, an electronic vote by the SBML community in late 2007 indicated a majority preferred not to require strict unit consistency before an SBML model is considered valid.) Version 4 was finalized after the SBML Forum meeting held in Gothenburg, Sweden, as a satellite workshop of ICSB 2008 in the fall of 2008.

SBML Level 3 Version 1 Core was published in final form in 2010, after prolonged discussion and revision by the SBML Editors and the SBML community. It contains numerous significant changes in syntax and constructs from Level 2 Version 4, but also represents a new modular base for continued expansion of SBML's features and capabilities going into the future.