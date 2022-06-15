# Standards covered by or related to COMBINE activities 

One of the major goals of COMBINE is to improve the interoperability of existing standards, and to foster or support fledging efforts aimed at filling gaps or new needs. Below are listed some of the major community standard representation formats covered by or related to COMBINE activity. 

= COMBINE standards =

The following standardization activities are open community efforts. The standards are described in freely available specifications, and associated tools (XML schemas, UML diagrams etc.).  They are piloted by democratically elected editorial boards, sometimes assisted by scientific committees.  A decent software support exist, including API implementations. The development is supported by central teams and/or funding sources. The different formats try to avoid overlapping but rather strive to interoperate, via interconversion, cross-linking, use of common metadata layers etc.  

A [[http://co.mbine.org/standards/specifications/ | comprehensive list of specification documents]] is also available, following the COMBINE [[standards/specification-infrastructure | specification infrastructure]].

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | BioPAX
|-
| style="background-color:#EFEFEF;color:black;"| [http://www.biopax.org BioPAX] is a standard language that aims to enable integration, exchange and analysis of biological pathway data. It is expressed in [http://www.w3.org/2004/OWL/ OWL].

The last specification is [http://www.biopax.org/release/biopax-level3-documentation.pdf BioPAX Level 3].

BioPAX development is [http://www.biopax.org/mediawiki/index.php/BioPAX_Governance coordinated] by an elected editorial board and a  Scientific Advisory Board.

BioPAX is supported by [http://biopax.sourceforge.net/mediawiki/index.php?title=Category:SOFTWARE many pathway database or processing tools]. An API is available to help implementing support: [http://www.biopax.org/mediawiki/index.php/Paxtools Paxtools]

[[http://co.mbine.org/standards/biopax|More information]]

|}

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;" | [[File:LogoWhiteBackBlackLetters-75.png| alt="SBGN" height="40"]] 
|-
| style="background-color:#EFEFEF;color:black;"| The [http://sbgn.org/ Systems Biology Graphical Notation (SBGN)], is a set standard graphical languages to describe visually biological knowledge. It is currently made up of three languages describing Process Descriptions, Entity Relationships and Activity Flows. 

The [http://sbgn.github.io/sbgn/specifications last specifications] are SBGN PD Level 1 Version 2.0, SBGN ER Level 1 Version 2 and SBGN AF Level 1 Version 1.2. 

SBGN development is [http://sbgn.github.io/sbgn/about coordinated] by an elected editorial board and a  Scientific Committee.

Several [https://sbgn.github.io/software data resources and software claim support for SBGN]. An API is available to help implementing support: [https://github.com/sbgn/sbgn/wiki/LibSBGN libSBGN] 

[[http://co.mbine.org/standards/sbgn|More information]]

|}

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | [[File:Official-sbml-supported-70.png| alt="SBML" height="40"]]
|-
| style="background-color:#EFEFEF;color:black;"| The [http://sbml.org Systems Biology Markup Language (SBML)] is a computer-readable [http://www.w3.org/XML/  XML format] for representing models of biological processes. SBML is suitable for, but not limited to,  models using a process description approach.

The latest stable specification is [http://sbml.org/Documents/Specifications Level 3 Version 2 Core].

SBML development is [http://sbml.org/About coordinated] by an elected editorial board and central developer team.

Over 250 software systems known to support SBML can be found in the [http://sbml.org/SBML_Software_Guide SBML software guide].  APIs are available to help implementing support: [http://sbml.org/Software/libSBML libSBML] in C++ and [http://sbml.org/Software/JSBML JSBML] in Java.

[[http://co.mbine.org/standards/sbml|More information]]

|} 

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | [[File:SED-ML-border.png| alt="SED-ML" height="40"]] 
|-
| style="background-color:#EFEFEF;color:black;"| 

The [http://sed-ml.org Simulation Experiment Description Markup Language (SED-ML)] is an XML-based format for encoding simulation experiments. SED-ML allows to define the models to use, the experimental tasks to run and which results to produce.is a computer-readable format for representing the models of biological processes. SED-ML can be used with models encoded in several languages, as far as they are in XML.

The latest stable specification is [http://co.mbine.org/specifications/sed-ml.level-1.version-3.pdf Level 1 Version 3].

SED-ML development is coordinated by an [http://sed-ml.org/about.html elected editorial board].

APIs are available to help implementing support: [http://libsedml.sourceforge.net/libSedML/Welcome.html libSedML] in C#, [https://github.com/fbergmann/libSEDML libSEDML] in C++ with swig bindings for python, java, perl, R and ruby, and [http://sourceforge.net/projects/jlibsedml/ jlibsedml] in Java.

[[http://co.mbine.org/standards/sed-ml|More information]]

|}

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | [[File:logo-cellml.png| alt="CellML" height="40"]] 
|-
| style="background-color:#EFEFEF;color:black;"| 

The [http://www.cellml.org CellML language] is an XML markup language to store and exchange computer-based mathematical models. CellML is being developed by the Auckland Bioengineering Institute at the University of Auckland and affiliated research groups.

The latest stable specification is [http://www.cellml.org/specifications/cellml_1.1 Version 1.1].

CellML development is coordinated by an [http://www.cellml.org/community/editorial_board elected editorial board].

APIs are available to help implementing support: [http://cellml-api.sourceforge.net/ CellML API] in C.

[[http://co.mbine.org/standards/CellML|More information]]

|}

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | [[File:sbol2017.png| alt="SBOLData" height="40"]] 
|-
| style="background-color:#EFEFEF;color:black;"| 

The [http://www.sbolstandard.org/ Synthetic Biology Open Language Data (SBOL Data)] is a language for the description and the exchange of synthetic biological parts, devices and systems. 

The latest stable specification of SBOL Data is [http://co.mbine.org/specifications/sbol.version-2.2.0.pdf 2.2.0].

SBOL Data is developed by the [http://sbolstandard.org/developers/ SBOL Developers Group]. The development is coordinated by an [http://sbolstandard.org/gov/ editorial board and the SBOL Chair].

SBOL data is supported by many  software tools. [http://sbolstandard.org/software/libraries/ APIs] are available to help implement the support of this data standard.

[[http://co.mbine.org/standards/sbol|More information]]

|}

{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | [[File:sbol_visual.png| alt="SBOLVisual" height="40"]] 
|-
| style="background-color:#EFEFEF;color:black;"| 

The [http://sbolstandard.org/visual/ Synthetic Open Language Visual (SBOL Visual) ] is an open-source graphical notation that uses schematic “glyphs” to specify genetic parts, devices, modules, and systems.

The latest stable specification of SBOL Visual is  [http://sbolstandard.org/wp-content/uploads/2017/10/SBOLVisual_Specification_2_0_0.pdf 2.0.0].

SBOL is developed by the [http://sbolstandard.org/developers/ SBOL Developers Group] and [http://sbolstandard.org/visual-2/ SBOL Visual Group]. The development is coordinated by an [http://sbolstandard.org/gov/ editorial board and the SBOL Chair].

SBOL Visual is supported by many   [http://sbolstandard.org/software/tools/ software tools]. 

[[http://co.mbine.org/standards/sbolVisual|More information]]

|}


{| cellpadding="10" 
| style="background-color:#1D636A;color:white;font-size:x-large;font-weight:bold;" | [[File:neuroml.png| alt="NeuroML" height="40"]] 
|-
| style="background-color:#EFEFEF;color:black;"| 

The [http://www.neuroml.org/ NeuroML] project focuses on the development of an XML based description language that provides a common data format for defining and exchanging descriptions of neuronal cell and network models. 

The latest stable specification of NeuroML is [https://www.neuroml.org/getneuroml version 2 beta 4].

NeuroML development is coordinated by the [https://www.neuroml.org/editors NeuroML Editorial Board]. 

NeuroML is supported by many software tools and databases, see [https://www.neuroml.org/tool_support here].

[[http://co.mbine.org/standards/neuroml|More information]]

|}


= Associated standardization efforts = 

The standardisation efforts described below are not community-developed representation formats. However, they are tools to add a layer of semantics that facilitate the use, the interoperability or enhance the usefulness of COMBINE representation formats.

== [[File:COMBINEArchive.png| alt="COMBINE Archive" height="40"]] COMBINE Archive  ==

A [http://co.mbine.org/standards/omex COMBINE archive] is a single file bundling the various documents necessary for a modelling and simulation project, and all relevant information.  The archive is encoded using the [http://co.mbine.org/standards/omex Open Modeling EXchange format (OMEX)]. 

== [[File:OMEXmetadataIconMetaBracketsVerySmall.png| alt="COMBINE Archive Metadata" height="40"]] COMBINE Archive Metadata ==

[http://co.mbine.org/standards/omex-metadata COMBINE archive metadata] provides a harmonized, community-driven approach for annotating a variety of standardized model and data representation formats within a COMBINE archive.

== [[File:identifiers-org_logo-new-whiteBg.png | alt="Identifiers.org" height="40"]]  Identifiers.org URIs ==

[http://co.mbine.org/standards/miriam_uris MIRIAM Unique Resource Identifiers] allow one to uniquely and unambiguously identify an entity in a stable and perennial manner. [http://co.mbine.org/standards/miriam#MIRIAM_Registry_and_Identifiers.org MIRIAM Registry] is a set of services and resources that provide support for generating, interpreting and resolving MIRIAM URIs. Through the [http://identifiers.org/ Identifiers.org] technology, MIRIAM URIs can be dereferenced in a flexible and robust way.

MIRIAM URIs are used by SBML, SED-ML, CellML and BioPAX controlled annotation schemes.

== [[File:sbo150x100.png | alt="SBO" height="40"]] Systems Biology Ontology ==

The [http://co.mbine.org/standards/sbo Systems Biology Ontology (SBO)] is a set of controlled, relational vocabularies of terms commonly used in Systems Biology, and in particular in computational modeling. 

Each element of an SBML file carries an optional attribute sboTerm which value must be a term from SBO. 

Each symbol of SBGN is associated with an SBO term.

== Kinetic Simulation Algorithm Ontology==

The [http://co.mbine.org/standards/kisao Kinetic Simulation Algorithm Ontology (KiSAO)] describes existing algorithms and their inter-relationships through their characteristics and parameters. 

KiSAO is used in SED-ML, which allows simulation software to automatically choose the best algorithm available to perform a simulation and unambiguously refer to it. 

== BioModels.net qualifiers ==

[[standards/qualifiers | BioModels.net qualifiers]] are standardized relationships (predicates) that specify the relation between an object represented in a description language and the external resource used to annotate it. The relationship is rarely one-to-one, and the information content of an annotation is greatly increased if one knows what it represents, rather than only know it is "related to" the model component.

= Related standardization efforts =

The following standardization efforts are of interest for COMBINE, either as candidate standards, or similar efforts in different domains.  

== Computational Neuroscience Ontology ==

The [https://github.com/INCF/Computational-Neurosciences-Ontology--C.N.O.- Computational Neuroscience Ontology (CNO)] is a controlled vocabulary composed of classes representing general concepts related to computational neuroscience. [http://www.biomedcentral.com/1471-2202/13/S1/P149 More ...]

== FieldML ==

[http://www.fieldml.org/ FieldML]'s (Field Modelling/Markup Language) goal is to be a declarative language for building hierarchical models represented by generalized mathematical fields. Its primary use will be to represent the dynamic geometry and solution fields from computational models of cells, tissues and organs. 

== [[File:fROG_analysis_200x95.png| alt="FROG" height="40"]] FROG ==

[https://www.ebi.ac.uk/biomodels/curation/fbc FROG] analysis - a community standard to foster reproducibility and curation of constraint-based models. FROG provides guidelines, best practices, and a set of standardized FBA analyses to assess reproducibility and curation efforts.

== FSK-ML ==

[https://foodrisklabs.bfr.bund.de/fsk-ml-food-safety-knowledge-markup-language/ FSK-ML]'s (Food Safety Knowledge Markup Language) aims at encoding experimental data and mathematical models from the domain of predictive microbial modelling (and beyond) in a software independent manner. An FSK-ML file is an [http://co.mbine.org/standards/omex OMEX] container, as the COMBINE Archive, and re-use other COMBINE standards to store models and simulations. A former version of the standard was the [https://sourceforge.net/projects/microbialmodelingexchange/ PMF-ML], and OpenML for Predictive Modelling in Food.

== GPML ==

[http://www.pathvisio.org/wiki/EverythingGpml GPML] (GenMAPP Pathway Markup Language) is an XML-based format to define a pathway consisting of purely graphical elements (such as lines and shapes) or graphical elements with added biological information (such as genes, proteins and datanodes).

== MAMO ==

The [[standards/MAMO | mathematical modelling ontology]] (MAMO) is an ontology describing and classifying the mathematical models used in the life sciences (for the time being). MAMO provides the types of models, the variables they use, the readout to expect and other relevant features.


== NineML ==

The [http://software.incf.org/software/nineml Network Interchange for Neuroscience Modeling Language (NineML)] - is a language developed by the [http://www.incf.org/ International Neuroinformatics Coordinating Facility (INCF)] and designed for the description of large networks of spiking neurons.

== NuML ==

The [http://code.google.com/p/numl/ Numerical Markup Language (NuML)] (pronounce "neumeul" and not "new em el", that sounds like NewML) is a simple XML format to exchange multidimensional arrays of numbers to be used with model and simulation descriptions. NuML was initially developed as part of the [http://www.comp-sys-bio.org/tiki-index.php?page=SBRML Systems Biology Results Markup Language (SBRML)].

== [[File:PEtab2.png| alt="PEtab" height="40"]] ==

[https://github.com/PEtab-dev/PEtab PEtab] is an SBML and TSV based data format for parameter estimation problems in systems biology.


== [[File:PharmML.gif | alt="PharmML" height="40"]] ==

The [http://pharmml.org Pharmacometrics Markup Language] is an exchange format for encoding of models, associated tasks and their annotation as used in pharmacometrics. PharmML is developed by the [http://ddmore.eu DDMoRe consortium], an [http://www.imi.europa.eu/ European Innovative Medicines Initiative (IMI)] project. 

== PSI-MI ==

The [http://www.psidev.info/index.php?q=node/60 Proteomics Standards Initiative Molecular Interaction XML Format] is a a data exchange format for molecular interactions developed by the [http://www.psidev.info/ the HUPO Proteomics Standards Initiative]

==  [[File:Spineml_logo_large.png | alt="SpineML" height="40"]] ==

The  [http://bimpa.group.shef.ac.uk/SpineML/index.php/Home Spiking Neural Mark-up Language (SpineML)] is a declarative XML based model description language for large scale neural network models. It is partially based upon on the [http://software.incf.org/software/nineml INCF NineML].

== [[File:teddy150x100.png | alt="TEDDY" height="40"]] ==

The [[standards/TEDDY| Terminology for the Description of Dynamics]] is a project to build an ontology for dynamical behaviours, observable dynamical phenomena, and control elements of bio-models and biological systems in Systems Biology and Synthetic Biology.

----

[[File:FAIRsharing-sdp.png | alt="FAIRsharing" height="80"]]

More information about standards used to share data in life sciences can be found at [https://fairsharing.org/ FAIRsharing]. The FAIRsharing team manually curates data and metadata standards, databases and data policies across all scientific research areas. FAIRsharing provides links among these standards and databases as well as to journal and funder data policies that recommend or endorse their use. For example, FAIRsharing contains a collection of the COMBINE standards as well as [https://fairsharing.org/search/?q=systems+biology&selected_facets=expanded_onto_disciplines_exact:Systems%20Biology many Systems Biology resources].
