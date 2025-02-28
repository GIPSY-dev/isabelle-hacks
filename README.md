# Isabelle Hacks

This project contains small Isabelle "hacks" that provide additional 
functionality to [Isabelle](https://isabelle.in.tum.de) or showcase
specific functionality. The individual hacks usually consist out of 
a single theory file and all documentation is contained in that 
theory file. The master branch should work with the latest official 
release of Isabelle (Isabelle 2021-1, at time of writing), hacks for 
older versions might be available on a dedicated branch.

## List of Isabelle Hacks

* [Assert.thy](Assert.thy) provides a new top level command **assert**
  that provides a simple way for specifying assertions that Isabelle
  checks while processing a theory.

* [Code_Reflection.thy](Code_Reflection.thy) provides a new top-level 
  command for reflecting generated SML code into Isabelle's ML 
  environment.

* [Fxp.thy](Fxp.thy) provides Isabelle support for The Functional XML
  Parser (fxp).

* [Hiding_Type_Variables.thy](Hiding_Type_Variables.thy) provides
  print a setup for defining default type variables of type
  constructors. The default type variables can be hidden in output,
  e.g., `('a, 'b, 'c) foo` is shown as `(_) foo`. This shorthand
  notation can also be used in input (using a parse translation),
  which (sometimes) helps to focus on the important parts of complex
  type declarations.

* [Ml_Yacc_Lib.thy](Ml_Yacc_Lib.thy) provides Isabelle support for parser 
  generated by ml-yacc (part of sml/NJ).

* [Nano_JSON.thy](Nano_JSON.thy) provides support for a JSON-like 
  data exchange for Isabelle/HOL.

* [Simple_Oracle.thy](Simple_Oracle.thy) provides an example on integrating 
  an external tool as simple oracle or counter example generator, similar
  to the built-in quickcheck.

## Authors

Main author: [Achim D. Brucker](http://www.brucker.ch/)

## License

If not otherwise stated, all hacks are licensed under a 2-clause 
BSD-style license.

## Authors

Main author: [Achim D. Brucker](http://www.brucker.ch/)

## License

If not otherwise stated, all hacks are licensed under a 2-clause 
BSD-style license.

SPDX-License-Identifier: BSD-2-Clause

## Upstream Repository

The upstream git repository, i.e., the single source of truth, for this project is hosted 
by the [Software Assurance & Security Research Team](https://logicalhacking.com) at
<https://git.logicalhacking.com/adbrucker/isabelle-hacks>.
