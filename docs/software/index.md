# Alex\'s Software Page

I subscribe to the view that computer science researchers in the area of
programming languages and software have two ways to disseminate their
results. Papers are the means of communicating ideas to other
specialists in the area, and implementations are the means of
communicating ideas to non-specialists, in the form of tools they can
use. My students and I probably devote more effort than is usual in
translating our research into software that can be used by others.

Here is a list of publicly available software systems with which I have
been involved:

- [Lux](https://github.com/LuxGraph/Lux) is a system for high
  performance distributed graph processing. Lux is built on top of
  [Legion](http://legion.stanford.edu).

- _[STOKE](http://stoke.stanford.edu)_ is a program
  transformation/optimization system for X86 assembly based on
  randomized search.

- _[Legion](http://legion.stanford.edu)_ is a programming model for
  heterogeneous and distributed parallel machines.

- _[Terra](http://terralang.org)_ is a statically typed low-level
  language that is integrated with and meta-programmed by Lua (a
  dynamically typed high-level language). Terra provides support for
  producing very high performance code using meta-programming
  techniques.

- _[Mistral](http://www.cs.utexas.edu/~tdillig/mistral/index.html)_ is
  a SMT solver incorporating support for abductive inference and fast
  solutions of integer linear constraints.

- _[Sixgill](http://sixgill.org)_ is a descendant of the Saturn
  project aimed at analysis of large C/C++ systems. As might be
  expected, sixgill shares some features with Saturn, but also takes a
  new direction in being a _near verifier_, meaning that it is
  designed to be sound and in principle can be made into a full
  verifier if a few known soundness holes are plugged with more
  analysis and any bugs in sixgill are fixed. Sixgill is also a
  complete rewrite and shares no code with Saturn.

- _[SAIL](http://www.stanford.edu/~isil/sail/index.html)_ is an
  intermediate language designed for static analysis; it explicitly
  both a high- and a low-level representation, with mappings between
  them, to facilitate both analysis (on the low-level representation)
  and reporting (through the high-level representation).

- _[Sequoia](http://sequoia.stanford.edu)_ is a programming language
  for hierarchical memory machines. A key feature of Sequoia is that
  data locality is expressible directly in the language.

- _[Saturn](http://saturn.stanford.edu)_ is a second-generation
  constraint-based analysis framework, primarily exploiting boolean
  satisfiability as the underlying constraint language.

- _[Banshee](http://banshee.sourceforge.net)_, which is a descendant
  of the earlier
  [BANE](http://http.cs.berkeley.edu/Research/Aiken/bane.html)
  project, is a framework for constructing efficient, scalable
  constraint-based program analyses. Banshee has been used in a
  variety of projects outside our group, including by gcc. UPDATE
  2/2015:
  [Here](software/banshee.tgz) is an
  updated version of Banshee that builds on a current (as of 2015)
  32-bit Ubuntu VM. Thank you Collin Gordon!

- _[Cooperative Bug Isolation (CBI)](http://www.cs.wisc.edu/cbi/)_ is
  designed to leverage the power of thousands or millions of users to
  help isolate bugs in deployed software systems.

- _[CQual](http://www.cs.umd.edu/~jfoster/cqual/)_ is a tool for
  adding type qualifiers to C programs to enable additional static
  checking.

- _[Moss](http://cs.stanford.edu/~aiken/moss)_ is a system for
  efficiently detecting copies or partial copies of documents within a
  large corpus. Moss, which was first developed in 1994 and released
  in 1997, is widely used in engineering courses to help detect
  plagiarism in programming assignments.

- _[CAP](http://moss.cs.berkeley.edu/~moss/cap/index.html)_ is a
  descendant of Moss that provides a query interface to millions of
  lines of open source software.

- _[Titanium](http://www.cs.berkeley.edu/projects/titanium/)_ is a
  memory and type-safe explicitly parallel programming language based
  on Java.

- _[Datasplash](http://datasplash.cs.berkeley.edu/)_, a tool for
  constructing database visualizations.

- [_Cool_](software/cooldist), the
  _Classroom Object Oriented Language_ , is a small language designed
  for use in an undergraduate compiler course project. While small
  enough for a one term project, Cool still has many of the features
  of modern programming languages, including objects, inheritance, and
  strong static typing.

    Cool is built entirely on public domain tools; it generates code for
  a MIPS simulator, [_spim_](http://www.cs.wisc.edu/~larus/spim.html)
  . Thus, the project should port easily to other platforms. The
  project has been used for teaching compilers at many institutions
  around the world and the source code is available. The complete Cool
  distribution includes the manual, source and makefiles for the
  compiler, source and makefiles for each of the assignments, test
  cases for each of the assignments, and lecture notes. Because the
  project is still being used at Berkeley, only the manual is
  available here. If you are interested in obtaining the complete
  distribution, send mail to [aaiken@stanford.edu]{.kbd}.

- Illyria was finished in 1994 and is still on this page just for
  historical reasons.

    [_Illyria_](Illyria.tar.gz) is a small functional
  language designed to illustrate a subtype inference system based on
  solving systems of type inclusion constraints. Illyria includes the
  lambda calculus, polymorphic let, constructors, case expressions,
  and record operations. The type language is rich, with union,
  intersection, complement, conditional, recursive, and universally
  quantified types. This package includes the type inclusion
  constraint solver, type inference for Illyria, and examples.

    Illyria runs under Common Lisp on Unix systems. The only known
  problem is that Illyria does not compile under CMU Common Lisp,
  although it will run interpreted in that environment. After
  retrieving the package, do:
  ``` Bash
  gunzip Illyria.tar.gz
  mv Illyria.tar dir/.
  cd dir
  tar -xvf Illyria.tar
  ```
  See the instructions in the Illyria/README file.
