# CellML
[[File:logo-cellml.png]] 

CellML is an open standard based on the XML markup language. The purpose of CellML is to store and exchange computer-based mathematical models. CellML allows scientists to share models even if they are using different model-building software. It also enables them to reuse components from one model in another, thus accelerating model building.

## Normative definitions

CellML is defined in a set of specification documents that describe the elements of the language, its syntax, and provide validation rules.

The specifications are:

* [CellML 1.1](cellml.1.1.md): [`http://identifiers.org/combine.specifications/cellml.1.1`](http://identifiers.org/combine.specifications/cellml.1.1)
* [CellML 1.0](cellml.1.0.md): [`http://identifiers.org/combine.specifications/cellml.1.0`](http://identifiers.org/combine.specifications/cellml.1.0)

## Governance

CellML development is coordinated by an [editorial board](http://www.cellml.org/community/editorial_board) elected by the community.

## Communication

CellML development is discussed on the mailing list [cellml-discussion@cellml.org](http://lists.cellml.org/mailman/listinfo/cellml-discussion).

## Software support

There are some [tools, APIs, and libraries available](http://www.cellml.org/tools) which support the CellML format. An extensive [[http://models.cellml.org|repository of models]] is also available.

## Contact

For information about CellML itself, contact [cellml-discussion@cellml.org](http://lists.cellml.org/mailman/listinfo/cellml-discussion). For other issues related to CellML there are a variety of options for [contacting](http://www.cellml.org/about/contact) the appropriate people.

# How to cite CellML

Cuellar, A.A., Lloyd, C.M., Nielsen, P.F., Bullivant, D.P., Nickerson, D.P. and Hunter, P.J. An overview of CellML 1.1, a biological model description language. SIMULATION (2003), 79(12):740-747. http://identifiers.org/doi/10.1177/0037549703040939

# History

The CellML language grew from a need to share models of cardiac cell dynamics among researchers at a number of sites across the world. The original working group consisted of David Bullivant, Warren Hedley, and Poul Nielsen, at the time (~1998) all members of the Department of Engineering Science at the University of Auckland. The language was based upon the emerging XML specifications developed by the World Wide Web Consortium. Existing XML-based languages were leveraged to describe the mathematics (content MathML), metadata (RDF), and links between resources (XLink). The working group collaborated with Melanie Nelson and a number of other researchers at Physiome Sciences Inc. to draft the initial CellML 1.0 specification published in early 2001. This first draft was followed by specifications for CellML Metadata and an update to CellML to accommodate structured nesting of models with the addition of the <import> element.