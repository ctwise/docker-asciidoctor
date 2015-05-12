This is an extension of the official Asciidoctor image that adds in the [blockdiag](http://blockdiag.com/en/) diagram types:

- blockdiag (block diagrams)
- seqdiag (sequence diagrams)
- actdiag (activity diagrams)
- nwdiag (network diagrams)

A simple example is:

	["blockdiag", "block-diagram", "svg"]
	---------------------------------------------------------------------
	blockdiag {
	   A -> B -> C -> D;
	   A -> E -> F -> G;
	}
	---------------------------------------------------------------------

