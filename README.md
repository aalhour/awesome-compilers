# ![AWESOME COMPILERS](img/awesome-compilers.png)

A curated list of awesome resources, learning materials, tools, frameworks, platforms, technologies and source code projects in the field of Compilers, Interpreters and Runtimes. This list has a bias towards education.

[![](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

-----------------------------------------

## Contents

  * [Learning](#learning)
    + [Books](#books)
      * [General Overview](#general-overview)
      * [Introductory](#introductory)
      * [Advanced](#advanced)
    + [Papers](#papers)
      * [Researchers and Institutes](#researchers-and-institutes)
    + [Specifications](#specifications)
    + [Courses](#courses)
    + [Talks and Conferences](#talks-and-conferences)
      * [Channels](#channels)
      * [Videos](#videos)
    + [Articles](#articles)
    + [Tutorials](#tutorials)
    + [Community Discussions](#community-discussions)
  * [Tools and Frameworks](#tools-and-frameworks)
    + [Language Agnostic](#language-agnostic)
    + [C / C++](#c--c)
    + [CLR](#clr)
    + [D](#d)
    + [Go](#go)
    + [Graal](#graal)
    + [Haskell](#haskell)
    + [JavaScript](#javascript)
    + [JVM](#jvm)
    + [Kotlin](#kotlin)
    + [Python](#python)
      * [Lists of Python Parsing Tools](#lists-of-python-parsing-tools)
    + [Rust](#rust)
  * [Compilers and Interpreters](#compilers-and-interpreters)
    + [Serious Projects](#serious-projects)
    + [Educational and Toy Projects](#educational-and-toy-projects)
  * [Runtimes and VMs](#runtimes-and-vms)
  * [Blogs](#blogs)
  * [Communities](#communities)
  * [Verticals](#verticals)

-----------------------------------------


## Learning

### Books

#### General Overview

  * [Computer Systems: A Programmer’s Perspective](https://www.amazon.com/dp/9332573905) - General treatment of Computer Systems including Compilers, Interpreters and Runtimes.
  * [Elements of Computing Systems](https://www.amazon.com/dp/0262640686) - How to build a computer from Nand Gates all the way to Compilers and Operating Systems.
  * [Structure and Interpretation of Computer Programs](https://mitpress.mit.edu/sicp/full-text/book/book.html) - Study the building blocks of computation using Scheme by building a Scheme interpreter in a Scheme!
    + Other editions: [HTML5/EPUB version](https://sarabander.github.io/sicp/).

#### Introductory

  * [Basics of Compiler Design](http://www.diku.dk/hjemmesider/ansatte/torbenm/Basics/) - Provides a short treatment of the basic concepts.
  * [Beautiful Racket](http://beautifulracket.com) - How to make your own Programming Language with Racket.
  * [Build Your Own Lisp](http://www.buildyourownlisp.com) - Learn C and build your own Lisp Programming Language in 1000 LoC.
  * [Compilers: Principles, Techniques and Tools](https://www.amazon.com/dp/0321486811) - The Dragons Book. A classic textbook on Compiler Construction.
  * [Crafting Interpreters](http://www.craftinginterpreters.com/) - An all-stop-shop for learning (nearly) everything you need to learn to build an interpreted, full-featured, efficient scripting language.
    + [GitHub Repo](https://github.com/munificent/craftinginterpreters).
    + Discussions: [HN](https://news.ycombinator.com/item?id=13406081).
  * [Create Your Own Programming Languauge](http://createyourproglang.com/) - Example-driven approach to building your own programming language with video tutorials and source code projects.
    + Discussions: [HN](https://news.ycombinator.com/item?id=813133).
  * [Engineering a Compiler](https://www.amazon.com/dp/012088478X) - The modern textbook on Compilers Construction, covering SSA-Form and recent research on Code Generation.
  * [Essentials of Programming Languages](https://www.amazon.com/dp/0262062798) - Fundamental concepts of programming languages with a focus on Semantics, Interpretation and CPS (Continuation Passing Style).
  * [Language Implementation Patterns](https://www.amazon.com/dp/193435645X) - Learn the patterns behind building programming languages and build an interpreter yourself, using ANTLR.
  * [Modern Compiler Implementation in ML](https://www.cs.princeton.edu/~appel/modern/ml/) - Build a compiler using ML (MetaLanguage) with a textbook that has one of the best coverage on all compiler stages. The book comes with a reference compiler implementation to guide your software development process.
    + Other editions: [MCI in C](https://www.cs.princeton.edu/~appel/modern/c/), [MCI in Java](https://www.cs.princeton.edu/~appel/modern/java/).
  * [Programming Language Pragmatics](https://www.amazon.com/dp/0123745144) - Integrated treatement of language design and implementation, the examples feature famous architectures like ARM and x86 64-bit.
  * [Programming Languages: Application and Interpretation](http://cs.brown.edu/courses/cs173/2012/book/) - Excellent introduction to the subject that uses an incremental approach to building programs. The mistakes are included too to highlight key concepts.
    + [PDF](http://cs.brown.edu/courses/cs173/2012/book/book.pdf).
  * [Programming Languages: Theory and Practice](http://people.cs.uchicago.edu/~blume/classes/aut2008/proglang/text/offline.pdf) - Collected lecture notes for the _Programming Languages_ course taught at Carnegie Mellon University, most suitable as an introductory text on the subject.
  * [Project Oberon](http://people.inf.ethz.ch/wirth/ProjectOberon1992.pdf) - The design of an operating system and compiler.
    + Other editions: [2013 Edition](http://www.cs.cmu.edu/~fp/courses/15312-f04/handouts/).
  * [The BEAM Book](https://github.com/happi/theBeamBook) - Description of the ERTS (Erlang Runtime System) and the BEAM Virtual Machine.
  * [Virtual Machines](https://www.amazon.com/dp/1852339691) - Good book on how to build Virtual Machines especially tailored for the topic of building Programming Languages.
  * [Virtual Machines: Versatile Platforms for Systems and Processes](https://www.amazon.com/dp/1558609105) - Key textbook on the subject of Virtual Machines which examines virtual machine technologies across the disciplines that use them, e.g.: OS and Programming Languages.
  * [Write a Compiler in Go](https://compilerbook.com/) - Well-known introduction to the Go programming language and its ecosystem through building a Compiler project.
  * [Write an Interpreter in Go](https://interpreterbook.com/) - Successor of the "Write a Compiler in Go" book, but this one builds an interpreter project instead.
  * [Writing Compilers and Interpreters: A Software Engineering Approach](https://www.amazon.com/dp/0470177071) - How to build Compilers using Java, this book is tailored for the working Software Engineer.
    + Other editions: [Using C++](https://www.amazon.com/dp/0471113530), [Using C](https://www.amazon.com/dp/0471555800).
  * [Writing Interpreters and Compilers for the Raspberry Pi Using Python](https://www.amazon.de/gp/product/1977509207) - If you want to learn how to write interpreters and compilers, and at the same time learn how Python, Python bytecode, assembly language, and dynamic typing work, this is the book for you.


#### Advanced

  * [Advanced Compiler Design and Implementation](https://www.amazon.com/dp/1558603204) - In-depth treatement of advanced design topics such as: Intermediate Representation, SSA, Code Optimization and the various processor architectures.
  * [Advanced Design and Implementation of Virtual Machines](https://www.amazon.com/dp/146658260X) - Step-by-step hollistic introduction to the design of Virtual Machine architectures, topics and algorithms. Contains illustrated figures and implementations for the algorithms in the book.
  * [Advanced Topics in Types and Programming Languages](https://www.amazon.com/dp/0262162288) - Intensive study of Type Systems, covering topics such as, but not limited to: Precise Type Analyses; Type Systems for Low-Level Languages and Advanced Techniques in ML-style Type Inference..
  * [A Retargetable C Compiler: Design and Implementation](https://www.amazon.com/dp/0805316701) - Examines the design and implementation of Icc, a production-quality, retargetable compiler, designed at AT&T Bell Labs for the ANSI C programming language.
  * [Building an Optimizing Compiler](https://www.amazon.com/dp/155558179X) - Fills the gap in the domain of code optimization. This book provides a high level design for a thorough optimizer, code generator, scheduler and register allocator for a generic modern RISC processor.
  * [Compiling with Continuations](https://www.amazon.com/dp/052103311X) - Introduction to CPS (Continuation-Passing Style) as an Intermediate Representation in Compiler for doing optimizations and program transformations.
  * [Design Concepts in Programming Languages](https://www.amazon.com/dp/0262201755) - Systematic exploration of techniques and ideas used in Programming Language Design, covers topics such as: Operational and Denotational Semantic techniques, Dynamic Semantic techniques and Static Semantic techniques.
  * [Instruction Level Parallelism](https://www.amazon.com/dp/1489977953) - This book precisely formulates and simplifies the presentation of Instruction Level Parallelism (ILP) compilation techniques.
  * [Linkers and Loaders](https://www.amazon.com/dp/1558604960) - Definitive text on the compile-time and runtime processes of linking and loading.
  * [Optimizing Compilers for Modern Architectures](https://www.amazon.com/dp/1558602860/) - Optimizing program generation based on recent gains and breakthroughs in modern high-performance CPU architectures.
  * [Parsing Techniques: A Practical Guide](https://www.amazon.com/dp/038720248X) - Definitive guide on parsing algorithms and techniques, also contains an introduction to Formal Grammar and Parsing Theory.
    + [1st Edition, PDF](https://dickgrune.com/Books/PTAPG_1st_Edition/).
  * [The Garbage Collection Handbook: The Art of Automatic Memory Management](https://www.amazon.com/dp/1420082795) - The living-classic and definitive text on the topic of Garbage Collection, also covers hardware-based optimizations in light of modern advances in CPU architectures.
  * [The Implementation of Functional Programming Languages](https://www.microsoft.com/en-us/research/wp-content/uploads/1987/01/slpj-book-1987-small.pdf) - Classic textbook on implementing Functional Languages, covers Structured Types, Pattern Matching Semantics, Lambda Calculus Transformation, Polymorphic Type Checking and many other topics.
  * [The SSA Book](http://ssabook.gforge.inria.fr/latest/book.pdf) - The only in-depth study of SSA-form (Static Single Assignment Form) in book format.
  * [Types and Programming Languages](https://www.amazon.com/dp/0262162091) - Comprehensive introduction to the topic of Type Systems and Programming Languages from a Type-Theoretic perspective.
  * [Warren's Abstract Machine: Prolog in Haskell](https://mitpress.mit.edu/books/warrens-abstract-machine) - Introduction to WAM from Logic Programming in Prolog.

### Papers

  * [A Brief History of JIT Compilation, J. Aycock](http://eecs.ucf.edu/~dcm/Teaching/COT4810-Spring2011/Literature/JustInTimeCompilation.pdf).
  * [A Flexible Prolog Interpreter in Python, C. Bolz & M. Leuschel](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.103.1886&rep=rep1&type=pdf).
  * [A Graph Higher-Order IR, R. Leißa, M. Koster & S. Hack](http://compilers.cs.uni-saarland.de/papers/lkh15_cgo.pdf).
  * [A Micro-Manual for LISP - Not the Whole Truth, J. McCarthy](https://www.uraimo.com/files/MicroManual-LISP.pdf).
    + Other editions: [Neat and nice typeset](https://github.com/jaseemabid/micromanual).
  * [A Prolog Interpreter in Python, C. Bolz](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.121.8625&rep=rep1&type=pdf).
  * [A Simple Multi-Processor Computer Based on Subleq, O. Mazonka, A. Kolodin](https://arxiv.org/abs/1106.2593).
  * [An Evil Copy: How the Loader Betrays You](http://www.cse.psu.edu/~trj1/papers/ndss17.pdf) - About security issues related to Dynamic Loading.
  * [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf).
  * [Compiler Construction Using Scheme, E. Hilsdale, J. Ashley, R. Dybvig & D. Friedman](https://www.cs.indiana.edu/~dyb/pubs/fple95.pdf).
  * [Compiling with Continuations: Continued, A. Kennedy](https://www.microsoft.com/en-us/research/wp-content/uploads/2007/10/compilingwithcontinuationscontinued.pdf).
  * [Definitional Interpreters for Higher-Order Programming Languages, J. Reynolds](http://www.cs.uml.edu/~giam/91.531/Textbooks/definterp.pdf).
  * [Draining the Swamp: Micro Virtual Machines as Solid Foundation for Languauage Development, K. Wang, Y. Lin, S. Blackburn, M. Norrish & A. Hosking](http://drops.dagstuhl.de/opus/volltexte/2015/5034/pdf/24.pdf).
  * [Engineering Definitional Interpreters, J. Midtgaard, N. Ramsey, B. Larsen](https://www.cs.tufts.edu/~nr/pubs/interps.pdf).
  * [Garbage Collection in an Uncooperative Environment, H. Boehm, M. Weiser](https://pdfs.semanticscholar.org/6434/aa10f3745dcf959cfca9c379aae120396724.pdf?_ga=2.133026126.1710272003.1495044697-300816831.1495044697).
  * [Machine Code Obfuscation via Instruction Set Reduction and CFG Linearization, C. Jonischkeit](https://kirschju.re/static/ba_jonischkeit_2016.pdf).
  * [`MOV` is Turing-Complete, S. Dolan](https://www.cl.cam.ac.uk/~sd601/papers/mov.pdf).
    + Discussions: [HN](https://news.ycombinator.com/item?id=6309631), [Reddit](https://redd.it/1nft0x).
  * [Nanopass Framework for Commercial Compiler Development, A. Keep & R. Dybvig](https://www.cs.indiana.edu/~dyb/pubs/commercial-nanopass.pdf).
  * [Nanopass Framework for Compiler Education, D. Sarkar, O. Waddell & R. Dybvig](https://www.cs.indiana.edu/~dyb/pubs/nano-jfp.pdf).
  * [Notes on Graph Algorithms Used in Optimizing Compilers, C. Offner](http://www.cs.umb.edu/%7Eoffner/files/flow_graph.pdf).
  * [Packrat Parsing Thesis on PEG, B. Ford](https://pdos.csail.mit.edu/~baford/packrat/thesis/).
  * [PEG-based transformer provides front-end, middle-end and back-end stages in a simple Compiler, I. Piumarta](http://www.vpri.org/pdf/tr2010003_PEG.pdf).
  * [Pycket: A Tracing JIT for a Functional Language](http://homes.soic.indiana.edu/samth/pycket-draft.pdf).
  * [PyPy’s Approach to VM Construction, A. Rigo & S. Pedroni](http://www.csc.lsu.edu/~gb/csc7700/Reading/pypy-vm-construction.pdf).
  * [RABBIT: A Compiler for SCHEME, G. Steele](http://repository.readscheme.org/ftp/papers/ai-lab-pubs/AITR-474.pdf).
  * [Simple and Efficient Construction of SSA Form](http://compilers.cs.uni-saarland.de/projects/ssaconstr/).
  * [SSA-based Register Allocation, S. Hack & G. Goos](http://compilers.cs.uni-saarland.de/projects/ssara/).
  * [The Essence of Compiling with Continuations, C. Flanagan, A. Sabry, B. Duba & M. Felleisen](https://users.soe.ucsc.edu/~cormac/papers/pldi93.pdf).
  * [The Page-Faults Weird Machine: Lessons in Instruction-less Computation, J. Bangert, S. Bratus, R. Shapiro, S. Smith](https://www.usenix.org/system/files/conference/woot13/woot13-bangert.pdf).
  * [Trace-based JIT Compilation for Lazy Functional Languages, T. Schilling](http://files.catwell.info/misc/mirror/tracing-jit-haskell-schilling.pdf).
  * [Using Datalog with Binary Decision Diagrams for Program Analysis, J. Whaley, D. Avots, M. Carbin & M. Lam](https://people.csail.mit.edu/mcarbin/papers/aplas05.pdf).

#### Researchers and Institutes

  * [C. Bolz’s Research Publications](https://scholar.google.com/citations?user=S0rpYpkAAAAJ).
  * [Compilers Lab at Saarland University](http://compilers.cs.uni-saarland.de).
  * [Kenichi Asai](http://pllab.is.ocha.ac.jp/%7Easai/papers/).
  * [Packrat Parsing (PEG) Papers and Resources](http://bford.info/packrat/).

### Specifications

  * [CLI (ECMA-335) Specification](http://www.ecma-international.org/publications/standards/Ecma-335.htm).
  * [Mu Specification](https://gitlab.anu.edu.au/mu/mu-spec).
  * [JVM SE8 Specification](https://docs.oracle.com/javase/specs/jvms/se8/html/).

### Courses

  * [Compilers Construction, Cambridge](http://www.cl.cam.ac.uk/teaching/1516/CompConstr/materials.html) - Introduction to compiler construction course from the University of Cambridge.
  * [Compiler Construction for Undergrads, RICE University](https://www.clear.rice.edu/comp412/Lectures/) - Introduction to compiler construction and language translators course from the RICE University.
  * Compilers Theory, Stanford - [YouTube](https://www.youtube.com/playlist?list=PLLH73N9cB21VSVEX1aSRlNTufaLK1dTAI), [Stanford.edu](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/), [Class Notes](http://web.stanford.edu/class/cs143/) -Introduction to Compilers theory and construction course from Stanford.
  * [Design and Construction of Compilers, University of Texas](https://lambda.uta.edu/cse5317/) - Design and construction of compilers including lexical analysis, parsing, code generation techniques, error analysis and simple code optimizations.
    + Lecture Notes: [PDF](https://lambda.uta.edu/cse5317/notes.pdf), [HTML](https://lambda.uta.edu/cse5317/long/long.html).
  * [DSL Design and Implementation Summer School](http://vjovanov.github.io/dsldi-summer-school/) - Summer School program on the topics of DSL Design and Implementation hosted by the EPFL University.
  * [Foundations of Programming Languages](http://www.cs.cmu.edu/~fp/courses/15312-f04/) - Concepts that underlie the design, definition, implementation and use of modern programming languages from a formal standpoint.
  * [Nand2Tetris: How to Build a Computer from First Principles, Part 2](https://www.coursera.org/learn/nand2tetris2) - This 2nd part of the Nand2Tetris course covers basic language design and elementary compiler construction concepts in addition to many other topics on a basic level.
  * [NPTEL's Principles of Compiler Design Course](https://www.youtube.com/playlist?list=PLbMVogVj5nJQNjkHZgwuAlfQ9tzmQDxjA) - Introductory course from NPTEL on Compiler Design.
  * [NPTEL's Compiler Design Course](http://nptel.ac.in/courses/106108052/32) - Slightly more advanced course than their Principles of Compiler Design course, covers SSA Form to a good degree.
    + [YouTube Video Playlist](https://www.youtube.com/playlist?list=PLbMVogVj5nJTmKzaSlCpGgi7qxgcRRs8h).
  * [Programming Languages: Part A, by Grossman](https://www.coursera.org/learn/programming-languages) - Part 1 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming.
  * [Programming Languages: Part B, by Grossman](https://www.coursera.org/learn/programming-languages-part-b) - Part 2 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming.
  * [Programming Languages: Part C, by Grossman](https://www.coursera.org/learn/programming-languages-part-c) - Part 3 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming.
  * [Types, Logic, Semantics, and Verification from Oregon University's Summer School](https://www.cs.uoregon.edu/research/summerschool/summer15/curriculum.html) - Summer School program that consists of 80 minute lectures presented by internationally recognized leaders in programming languages and formal reasoning research.
  * [Virtual Machines and Managed Runtimes, UCB CS294](http://www.wolczko.com/CS294/) - Introductory course on Virtual Machines and Managed Runtimes from the University of Berkeley.
  * [Virtual Machines Summer School 2016 (VMSS 2016)](http://soft-dev.org/events/vmss16/) - VMSS is a Summer School program that aims to give an overview of the field, targeted at early career researchers.
    + [YouTube Videos Playlist](https://www.youtube.com/playlist?list=PLJq3XDLIJkib2h2fObomdFRZrQeJg4UIW).

### Talks and Conferences

#### Channels

  * [Curry On! Conference](http://www.curry-on.org/) - Programming Languages Conference.
    + [YouTube Channel](https://www.youtube.com/channel/UC-WICcSW1k3HsScuXxDrp0w/videos).
  * [Lang.NEXT Conference 2012](https://channel9.msdn.com/Events/Lang-NEXT/Lang-NEXT-2012).
  * [Lang.NEXT Conference 2014](https://channel9.msdn.com/Events/Lang-NEXT/Lang-NEXT-2014).
  * [LLVM Developers Meeting YouTube Channel](https://www.youtube.com/channel/UCv2_41bSAa5Y_8BacJUZfjQ).

#### Videos

  * [Anders Hejlsberg on Modern Compiler Construction](https://channel9.msdn.com/Blogs/Seth-Juarez/Anders-Hejlsberg-on-Modern-Compiler-Construction).
  * [An Introduction to Combinator Compilers and Graph Reduction Machines](https://www.youtube.com/watch?v=GawiQQCn3bk).
  * [Building an Interpreter in RPython](https://www.youtube.com/watch?v=9tDpjzPLvNY).
  * [CPython - A Ten-Hour Codewalk](http://pgbovine.net/cpython-internals.htm).
  * [Exploring Python’s Bytecode](https://ep2016.europython.eu/media/conference/slides/exploring-python-bytecode.pdf).
  * [How to Build a Virtual Machine](https://www.youtube.com/watch?v=OjaAToVkoTw) - Terence Parr gives an idea of the core mechanisms behind virtual machines by building one, in front of your eyes, from scratch. It is the same kind of commercial interpreter he made for Renault cars.
  * [Java AOT (Ahead of Time) Compilation](https://2016.javazone.no/program/java-aot-compilation).
  * [MetaScala: A Tiny DIY JVM](https://skillsmatter.com/skillscasts/4916-metascala-a-tiny-diy-jvm) - Metascala is a tiny metacircular Java Virtual Machine (JVM) written in the Scala programming language.
  * [Meta-Tracing, RPython and PyPy](https://ia601503.us.archive.org/32/items/vmss16/bolz.pdf).
  * [One VM to Rule Them All, One VM to Bind Them](https://www.youtube.com/watch?v=FJY96_6Y3a4) - Tutorial on the Truffel technology.
  * [Programming Should Eat Itself](https://www.youtube.com/watch?v=SrKj4hYic5A) - StrangeLoop Talk on Reflective Programming and Kenichi Asai's Black Programming Language.
  * [Python, Linkers and Virtual Memory - PYCON US](https://www.youtube.com/watch?v=twQKAoq2OPE).
  * [Reverse Engineering the MOS 6502 CPU](https://youtube.com/watch?v=fWqBmmPQP40).
  * [Single Static Assignment Form Seminar](http://compilers.cs.uni-saarland.de/ssasem/) - Introductory seminar on SSA Form, Compiler Optimizations under it and its applications in other areas such as Program Analysis and Verification.
  * [The JVM (Java Virtual Machine) Architecture](https://www.youtube.com/watch?v=ZBJ0u9MaKtM).
  * [The Most Beautiful Program Ever Written](https://www.youtube.com/watch?v=OyfBQmvr2Hc) - William Byrd on a Lisp interpreter written in 15 lines of Lisp.
  * [The MoVfuscator: turning mov into a soul crushing RE nightmare](https://www.youtube.com/watch?v=R7EEoWg6Ekk).
    + Discussions: [HN](https://news.ycombinator.com/item?id=9751312), [Reddit](https://redd.it/4zl8mh).
  * The SSA Form - Video Lectures from NPTEL's Compilers Course (see: [Courses](#courses) for more info):
    + [Part 1](https://www.youtube.com/watch?v=Q7hlcuCGbxE).
    + [Part 2](https://www.youtube.com/watch?v=FV9fq_HfPsM).
    + [Part 3](https://www.youtube.com/watch?v=GyYiic8trCE).
  * [Type-Driven Development with Idris](https://www.youtube.com/watch?v=X36ye-1x_HQ).
  * [Understanding Compiler Optimization](https://www.youtube.com/watch?v=FnGCDLhaxKU).

### Articles

  * [A Tourist’s Guide to the LLVM Source Code](https://blog.regehr.org/archives/1453).
  * [Accidentally Turing Complete](http://beza1e1.tuxen.de/articles/accidentally_turing_complete.html).
  * Adventures in JIT Compilation by Eli Bendersky:
    + [Part 1 - An Interpreter](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-1-an-interpreter/).
    + [Part 2 - An x64 JIT](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-2-an-x64-jit/).
    + [Part 3 - LLVM](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-3-llvm/).
    + [Part 4 - In Python](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-4-in-python/).
  * [ALIVe: Automatic LLVM InstCombine Verifier](https://blog.regehr.org/archives/1170).
  * [Graal and Truffel](https://blog.plan99.net/graal-truffle-134d8f28fb69) - Obscure research project could radically accelerate innovation in programming language design.
    + Discussions: [Reddit](https://redd.it/4tm4mj).
  * [How to Compile with Continuations](http://matt.might.net/articles/cps-conversion/).
  * [Interpreter, Compiler and JIT](https://nickdesaulniers.github.io/blog/2015/05/25/interpreter-compiler-jit/).
  * [Introducing the B3 JIT Compiler](https://webkit.org/blog/5852/introducing-the-b3-jit-compiler/).
  * [LLVM Architecture](http://www.aosabook.org/en/llvm.html) - Chapter from the book Architecture of Open Source Applications.
  * [LLVM for Graduate Students](http://www.cs.cornell.edu/~asampson/blog/llvm.html) - Introduction to doing research with the LLVM compiler infrastructure.
  * [Pratt Parsers: Expression Parsing Made Easy](http://journal.stuffwithstuff.com/2011/03/19/pratt-parsers-expression-parsing-made-easy/).
  * [Rust Compiler Walk-Through](https://gchp.ie/2016/08/09/rust-compiler-walkthrough-introduction/).
  * [Rust's Incremental Compilation](https://blog.rust-lang.org/2016/09/08/incremental.html).
  * [Rust’s Upcoming MIR](https://blog.rust-lang.org/2016/04/19/MIR.html).
  * [The Memory Models that Underlie Programming Languages](http://canonical.org/~kragen/memory-models/).


### Tutorials

  * [A Tutorial Implementation of a Dependently Typed Lambda Calculus](https://www.andres-loeh.de/LambdaPi/).
  * [A Beginner's Guide to Linkers](http://www.lurklurk.org/linkers/linkers.html) - Tutorial for helping C & C++ programmers understand the essentials of what the linker does.
  * [Algorithm W Step By Step](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.65.7733&rep=rep1&type=pdf).
  * [Building a LISP from scratch with Swift](https://www.uraimo.com/2017/02/05/building-a-lisp-from-scratch-with-swift/).
  * [Compiler Optmization Tutorial](https://www.youtube.com/watch?v=SfV8aRX0YY0).
  * [Hindley-Damas-Milner Tutorial](https://github.com/quchen/articles/tree/master/hindley-milner) - Extensively documented walkthrough for typechecking a basic functional language using the Hindley-Damas-Milner algorithm.
  * [How I Wrote a Programming Language, and How You Can Too](https://medium.com/@william01110111/the-programming-language-pipeline-91d3f449c919).
    + Discussions: [Reddit](https://redd.it/62ixbc).
  * [Implementing a JIT Compiled Language with Haskell and LLVM](http://www.stephendiehl.com/llvm/).
  * [Kaleidoscope: Implementing a Language with LLVM in Objective Caml](http://llvm.org/docs/tutorial/index.html#kaleidoscope-implementing-a-language-with-llvm-in-objective-caml).
  * [Let’s Build A Simple Interpreter](https://ruslanspivak.com/lsbasi-part1/).
  * [Lisperator](http://lisperator.net/pltut/) - How to implement a programming language in JavaScript.
  * [Little Lisp Interpreter](https://maryrosecook.com/blog/post/little-lisp-interpreter) - Interpreter that supports function invocation, lambdas, lets, ifs, numbers, strings, a few library functions, and lists in under 120 lines of JavaScript.
    + [GitHub Repository](https://github.com/maryrosecook/littlelisp).
  * [`lis.py`, v1: (How to Write a (Lisp) Interpreter (in Python))](http://norvig.com/lispy.html) - Tutorial by Peter Norvig on writing a simple Lisp interpreter.
  * [`lis.py`, v2: An ((Even Better) Lisp) Interpreter (in Python)](http://norvig.com/lispy2.html) - Follow-up tutorial by Peter Norvig on making `lis.py` slightly better.
  * [LLVM Tutorial: Implementing Kaleidoscope](http://releases.llvm.org/3.6.2/docs/tutorial/LangImpl1.html).
    + [Python version with LLVMPY](http://www.llvmpy.org/llvmpy-doc/dev/doc/kaleidoscope/index.html).
  * [Metacompiler Tutorial, Part 1](http://www.bayfronttechnologies.com/mc_tutorial.html).
  * [Project: A Programming Language](http://eloquentjavascript.net/11_language.html) - Chapter 11 from the book _Eloquent JavaScript_, 2nd Edition.
  * [Write You a Haskell](http://dev.stephendiehl.com/fun/).
  * [Writing a Language in Truffel](http://cesquivias.github.io/tags/truffle.html) - Interpreter development tutorial using Truffel, by Cristian Esquivias.


### Community Discussions

  * [Can we stop recommending the Dragon Book, please?](https://meta.stackexchange.com/questions/25840/can-we-stop-recommending-the-dragon-book-please) - StackExchange thread criticising the [Dragons Book](https://www.amazon.com/dp/0321486811) in favor of alternatives.
  * [What is difference between an LL and Recursive Descent parser?](http://stackoverflow.com/questions/1044600/difference-between-an-ll-and-recursive-descent-parser).
  * Does a compiler use all x86 instructions? - [@HN](https://news.ycombinator.com/item?id=12352959), [@Reddit](https://redd.it/4zgawj) - Article discussions on HN and Reddit.
  * [How to Write a Compiler](https://redd.it/4o7qag) - Article discussion on Reddit.
  * [How to Write a Very Basic Compiler](https://softwareengineering.stackexchange.com/questions/165543/how-to-write-a-very-basic-compiler).
  * [How to Write a Prolog Interpreter in a Purely Functional Language](https://cs.stackexchange.com/questions/6618/how-to-implement-a-prolog-interpreter-in-a-purely-functional-language).
    + Discussions: [Reddit](https://redd.it/4u2xt3).
  * [Implementing Type Inference](http://stackoverflow.com/questions/415532/implementing-type-inference).
  * [I want to build a VM, any good references?](https://softwareengineering.stackexchange.com/questions/178224/i-want-to-build-a-virtual-machine-are-there-any-good-references).
  * [Resources for Amatuer Compilers Writers](https://redd.it/4u15t1).
  * [What are the good open source implementations of Java Virtual Machine?](http://stackoverflow.com/questions/1621899/what-are-the-good-open-source-implementations-of-java-virtual-machine).
  * [What are the latest research trends in Compilers and PLs](https://www.quora.com/What-are-the-latest-research-trends-in-compilers-and-programming-languages).


## Tools and Frameworks

### Language Agnostic

  * [B3: The Bare Bones Backend](https://webkit.org/docs/b3/) - WebKit's optimizing JIT Compiler for procedures containing C-like code.
  * [Capstone](https://github.com/aquynh/capstone) - Lightweight multi-platform, multi-architecture disassembly framework with bindings to various famous programming languages.
  * [Keystone](https://github.com/keystone-engine/keystone) - Lightweight multi-platform, multi-architecture assembler framework with bindings to various famous programming languages.
  * [LLILCL](https://github.com/dotnet/llilc) - LLVM-based Compiler Backend for .NET Core.
  * [LLVM](http://llvm.org/) - The LLVM Compiler-Backend Framework.
  * [MicroVM](http://microvm.github.io/) - The "Mu" Framewrok for Programming Languages development based on the MuVM Specification.
  * [Movfuscator Compiler](https://github.com/xoreaxeaxeax/movfuscator) - The `M/o/Vfuscator` compiles programs into "mov" instructions, and only "mov" instructions.
  * [QBE: The Quick Backend](http://c9x.me/compile/) - Pure C embeddable SSA-based compiler backend.
  * [Rubinius](https://github.com/rubinius/rubinius) - Programming Languages Development Platform.
  * [Summus](https://github.com/igor84/summus) - Basic, reusable, compiler-frontend implementation using LLVM as a backend.
  * [ZetaVM](https://github.com/zetavm/zetavm) - Multi-Language Platform for Dynamic Programming Languages.

### C / C++

  * [AsmJIT](https://github.com/asmjit/asmjit) - Complete x86/x64 JIT and Remote Assembler for C++.
  * [GCC](https://gcc.gnu.org/) - The GNU Compiler Collection (C as a Backend).
  * [LCC](https://github.com/drh/lcc) - The lcc retargetable ANSI C compiler (C as a Backend).
  * [libFirm](http://pp.ipd.kit.edu/firm/) - C-library that provides a graph-based intermediate representation, optimizations, and assembly code generation suitable for use in compilers.
  * [libJIT](https://www.gnu.org/software/libjit/) - Library for generic Just-In-Time compiler functionality independent of any particular bytecode, language, or runtime.
  * [myJIT](http://myjit.sourceforge.net/) - Library for machine-code generation and execution at run-time.
  * [OrangeC](http://github.com/LADSoft/OrangeC) - Win32 C11/C++2014 compiler and toolchain.
  * [PCC](http://pcc.ludd.ltu.se/) - The Portable C Compiler (C as a Backend).
  * [Ragel](http://www.colm.net/open-source/ragel/) - Ragel State Machine Compiler.
  * [TCC](http://bellard.org/tcc/) - The Tiny C Compiler (C as a Backend).

### CLR

  * [Cecil](http://www.mono-project.com/docs/tools+libraries/libraries/Mono.Cecil/) - Library to generate and inspect programs and libraries in the ECMA CIL format.
  * [DotNetPELib](https://github.com/LADSoft/DotNetPELib) - Library to read and write .net assemblies in C++11
  * [ILSpy](http://ilspy.net) - .NET Decompiler.
  * [Reflector](http://www.red-gate.com/products/dotnet-development/reflector/) - .NET Decompiler.
  * [Reflexil](http://sebastien.lebreton.free.fr/reflexil/) - Assembly code editor which can be used as a plugin with other .NET/CLR tools.

### D

  * [dunnart](https://github.com/pwil3058/dunnart) - LALR(1) Parser Generator.
  * [FancyPars-lite](https://github.com/UplinkCoder/FancyPars-lite) - Fast parser generator.
  * [libdparse](https://github.com/dlang-community/libdparse) - Library allowing to build lexers and parsers. Contains a lexer and a parser for the D language itself.
  * [llvm-d](https://github.com/Calrama/llvm-d) - D bindings for LLVM.
  * [Pegged](https://github.com/PhilippeSigaud/Pegged) - design, test and generate parsers for PEG grammars.

### Go

  * [goyacc](https://godoc.org/golang.org/x/tools/cmd/goyacc) - YACC Implementation in Go. Standard LALR(1) parser generator.
  * [LLVM Go binding](https://godoc.org/llvm.org/llvm/bindings/go/llvm) - Official Go LLVM binding.

### Graal

  * [Graal](https://github.com/graalvm/graal) - High-Performance Polyglot Runtime.
  * [Graal Core](https://github.com/graalvm/graal-core) - Compiler and Truffel Partial Evaluator.
  * [Graal VM](https://github.com/graalvm/graalvm) - Graal's multi-language VM distribution.

### Haskell

  * [Bound](https://github.com/ekmett/bound/) / [unbound](https://github.com/sweirich/replib) / [unbound-generics](https://github.com/lambdageek/unbound-generics) - Libraries for manipulating bound variables.
  * [Hoopl](https://github.com/haskell/hoopl) - Higher-order optimization library.
  * [llvm-general](https://github.com/bscarlet/llvm-general/) - Haskell bindings for LLVM.
  * [Parsec](https://github.com/aslatter/parsec) / [attoparsec](https://github.com/bos/attoparsec) / [Megaparsec](https://github.com/mrkkrp/megaparsec) / [Trifecta](https://github.com/ekmett/trifecta/) / [Alex](https://github.com/simonmar/alex) + [Happy](https://github.com/simonmar/happy) - Parsers for every use case.
  * [wl-pprint-text](https://github.com/ivan-m/wl-pprint-text) / [ansi-wl-pprint](https://github.com/batterseapower/ansi-wl-pprint) - Walder-style pretty-printing libraries.

### JavaScript

  * [IRHudra](http://mrale.ph/irhydra/2/) - Tool for displaying intermediate representations used by V8 and Dart VM optimizing compilers.
    + [GitHub Repo](https://github.com/mraleph/irhydra).
  * [JISON](http://zaa.ch/jison/docs/) - Context-free grammar parser generator for JavaScript.
    + [GerHobbelt/jison](https://github.com/GerHobbelt/jison) - active fork of jison with bunch of improvements.  
  * [Nearley](https://github.com/Hardmath123/nearley) - Simple, fast, powerful parser toolkit for JavaScript.
  * [Ohm](https://github.com/harc/ohm) - A library and language for building parsers, interpreters, compilers, etc.
  * [PEG.js](https://pegjs.org) - Simple parser generator for JavaScript.

### JVM

  * [ANTLR](http://www.antlr.org) - Parser generator for reading, processing, executing, or translating structured text or binary files.
  * [BYAAC/J](http://byaccj.sourceforge.net) - BYACC/Java is an extension of the Berkeley v 1.8 YACC-compatible parser generator for Java.
  * [CGLIB](https://github.com/cglib/cglib) - High level API library for generating and transforming Java Byte Code.
  * [FCP JVM](http://wiki.freepascal.org/FPC_JVM) - JVM Backend for generating Java Byte Code that conforms to the JDK v1.5+ Specification and the Dalvik VM.
  * [JavaCC](https://javacc.org) - Java Compiler Construction and Parser Generator Toolkit.
  * [JavaCPP Presets for LLVM](https://github.com/bytedeco/javacpp-presets/tree/master/llvm) - Library for easily interacting with the LLVM API.
  * [JFlex](http://www.jflex.de) - JFlex is a lexical analyzer generator for Java with full Unicode support.
  * [JLex](http://www.cs.princeton.edu/~appel/modern/java/JLex/) - JLex is a lexical analyzer generator, that can be used in combination with CUP.

### Kotlin

  * [The Whimsy Compiler Framework](https://github.com/norswap/whimsy) - Compiler framework research project in Kotlin.

### Python

  * [AST](https://docs.python.org/3.5/library/ast.html) - Python's builtin Abstract Syntax Tree package.
  * [Dis](https://docs.python.org/3.6/library/dis.html) - Python's builtin Disassembler package.
  * [Parsing](http://www.canonware.com/Parsing/) - Pure-Python module that implements an LR(1) parser generator, as well as CFSM and GLR parser drivers.
  * [PLY](http://www.dabeaz.com/ply/) - Implementation of lex and yacc parsing tools for Python.
  * [PyParsing](http://pyparsing.wikispaces.com/) - Alternative approach to creating and executing simple grammars, vs. the traditional lex/yacc approach, or the use of regular expressions.
  * [RPLY](https://github.com/alex/rply) - Port of the PLY project to RPython.
  * [RPython](https://rpython.readthedocs.io/en/latest/) - RPython is a framework for the implementatation of dynamic languages.

#### Lists of Python Parsing Tools

  * [List of Language Parsing Tools at the Python Wiki](https://wiki.python.org/moin/LanguageParsing).
  * [Survey of Python Parsers, by Ned Batchelder](http://nedbatchelder.com/text/python-parsers.html).

### Rust

  * [Combine](https://github.com/Marwes/combine) - Parser Combinator Library for Rust.
  * [IronLLVM](https://github.com/jauhien/iron-llvm) - Safe LLVM bindings for Rust.
  * [LALRPOP](https://github.com/nikomatsakis/lalrpop) - LR(1) parser generator for Rust.
  * [Nom](https://github.com/Geal/nom) - Parser Combinator Framework.
  * [PEG](https://github.com/kevinmehall/rust-peg) - PEG Parser Generator.
  * [Pest](https://github.com/pest-parser/pest) - PEG Parser Generator.
  * [RLS](https://github.com/rust-lang-nursery/rls) - The Rust Language Server implementation (aka RLS).

## Compilers and Interpreters

_This section aims at listing code projects of Compilers, Interpreters, Translators, Runtimes, Virtual Machines and the like._

### Serious Projects

  * [Babel.js](https://github.com/babel/babel) - Next-generation JavaScript Compiler.
  * [BOLT](https://github.com/facebookincubator/BOLT) - Binary Optimization and Layout Tool.
  * [ChezScheme's Compiler](https://github.com/cisco/ChezScheme) - ChezScheme Language Compiler.
  * [ELENA Compiler](https://github.com/ELENA-LANG/elena-lang) - Elena programming language.
  * [Eta' Compiler](https://github.com/typelead/eta) - JVM-based Compiler for the Eta Programming Language.
  * [Frege's Compiler](https://github.com/Frege/frege) - JVM-based Compiler for the Frege Programming Language.
  * [Gluon's Compiler](https://github.com/gluon-lang/gluon) - Embedded Language Compiler written in Rust.
  * [HHVM](https://github.com/facebook/hhvm) - Virtual Machine for running programs written in Hack and PHP.
  * [Lily's Interpreter](https://github.com/FascinatedBox/lily).
  * [Lua's Interpreter](https://github.com/LuaDist/lua) - Official Lua Language Interperter.
    + [Lua's Annotated Source Code](http://stevedonovan.github.io/lua-5.1.4/) - Annotated source code of the Lua Programming Language Interpreter v5.1.4.
  * [Mirah's Compiler](https://github.com/mirah/mirah) - JVM-based Compiler for the Mirah Programming Language.
  * [Nim's Compiler](https://github.com/nim-lang/Nim).
  * [P Lang](https://github.com/p-org/P) - The P Programming Language Runtime.
  * [Red's Compiler](https://github.com/red/red).
  * [Roslyn](https://github.com/dotnet/roslyn) - The .NET "Roslyn" Compiler Platform.
  * [Simple-MSIL-Compiler](https://github.com/LADSoft/Simple-MSIL-Compiler) - C compiler that compiles to CLR.
  * [TypeScript's Compiler](https://github.com/Microsoft/TypeScript).
  * [Wren's Compiler](https://github.com/munificent/wren).
  * [Zig's Compiler](https://github.com/zig-lang/zig) - Zig Language Compiler.

### Educational and Toy Projects
  * [Akilang](https://github.com/syegulalp/Akilang) - A compiler for a simple language, built with Python and LLVM
  * [amacc](https://github.com/jserv/amacc) - Small C Compiler generating ELF executable for Arm architecture.
    + Discussions: [HN](https://news.ycombinator.com/item?id=11411124).
  * [Black](http://www.is.ocha.ac.jp/~asai/Black/) - Scheme interpreter for the Reflective Programming Language "Black", by Kenichi Asai's.
    + Other sources: [GitHub Mirror](https://github.com/readevalprintlove/black).
  * [C4](https://github.com/rswier/c4) - C Lang in 4 Functions.
    + Discussions: [HN](https://news.ycombinator.com/item?id=8558822).
  * [CarpVM](https://github.com/tekknolagi/carp) - Experimental VM implementation in C.
  * [Charly](https://github.com/charly-lang/charly) - Interpreter for a dynamically typed language written in Crystal.
  * [Dale](https://github.com/tomhrr/dale) - Lisp-flavoured C: a system programming language.
  * [EasyLang](https://github.com/erhanbaris/EasyLang) - Easy Programming Language / VM.
  * [Eschelle](https://github.com/Eschelle/Eschelle) - Open source cross platform multi-paradigm language with VM & JIT
  * [Gecho](https://github.com/tekknolagi/gecho) - Simple-stack language implementation in C.
  * [gocaml](https://github.com/rhysd/gocaml) - Minimal functional programming language implementation in Go and LLVM.
  * [gone](https://github.com/paivett/gone) - Compiler for a tiny programming language called Gone, implemented using Python 3.6, SLY and llvmlite. Developed as part of the January 2018 [Write a compiler course](http://www.dabeaz.com/compiler.html), under the supervision of David Beazly.
  * [Hython](https://github.com/mattgreen/hython) - Haskell-powered Python 3 interpreter.
    + Discussions: [Reddit](https://redd.it/46f8j4).
  * [llgo](https://github.com/llvm-mirror/llgo) - Go frontend for LLVM written in Go.
  * [MAL](https://github.com/kanaka/mal): Make a Lisp - Clojure-inspired Lisp interpreter implemented in 64 languages.
  * [MetaScala](https://github.com/lihaoyi/Metascala) - Metacircular JVM implementation in Scala.
  * [mini-js](https://github.com/maierfelix/mini-js) - Experimental self-hosted JavaScript compiler in 1K LoC.
  * [MunVM](https://github.com/MunVM/MunVM) - Lua VM & Compiler in C.
  * [MY-BASIC](https://github.com/paladin-t/my_basic) - An embeddable BASIC dialect interpreter in C with modern paradigms.
  * [oberonc](https://github.com/lboasso/oberonc) - A single pass, self-hosting compiler for the Oberon-07 programming language. It targets the JVM.
  * [Poprc](https://github.com/HackerFoo/poprc) - Compiler for the Popr Language.
  * [PyCOOLC](https://github.com/aalhour/PyCOOLC) - Compiler for the COOL Programming Language written in Python 3.
  * [RabbitVM](https://github.com/rabbitvm/rabbit) - RISC-based VM implementation in C.
  * [StackVM](https://github.com/KCreate/stackvm) - Virtual Machine with an integrated VRAM display.
  * [stack_cpu](https://github.com/dsturnbull/stack_cpu) - Stack-machine simulator.
  * [The Super Tiny Compiler](https://github.com/thejameskyle/the-super-tiny-compiler) - Tiny educational compiler project in JavaScript.
    + Discussions: [HN](https://news.ycombinator.com/item?id=11395656).
  * [tinyc.c](http://www.iro.umontreal.ca/~felipe/IFT2030-Automne2002/Complements/tinyc.c) - Tiny-C language compiler in C.
  * [tisp](https://github.com/raviqqe/tisp) - "Time is Space" Programming Language Interpreter.
  * [Ultra Tiny Compiler](https://github.com/antonmedv/ultra-tiny-compiler) - Another tiny compiler in less then 90 lines of code.


## Runtimes and VMs

  * [CakeML](https://github.com/CakeML/cakeml).
  * [CoreCLR](https://github.com/dotnet/coreclr) - The .NET's Common Language Runtime.
  * [Erlang BEAM](https://github.com/erlang/otp).
  * [HHVM](https://github.com/facebook/hhvm) - Facebook's Open Source VM for running Hack and PHP programs.
  * [HLVM](http://www.ffconsultancy.com/ocaml/hlvm/).
  * JVM Implementations:
    + [OpenJDK](http://openjdk.java.net/).
    + [Kaffe](https://github.com/kaffe/kaffe).
    + [JamVM](http://jamvm.sourceforge.net) - [GitHub project mirror](https://github.com/cfriedt/jamvm).
    + [Apache Harmony](https://harmony.apache.org/).
    + [Other JVM Runtimes](https://en.wikipedia.org/wiki/List_of_Java_virtual_machines).


## Blogs

  * [Eli Bendersky](http://eli.thegreenplace.net/).
  * [John Regehr](https://blog.regehr.org/).
  * [Krister Walfridsson](https://kristerw.blogspot.com/).
  * [Lambda The Ultimate](http://lambda-the-ultimate.org).
  * [LLVM Developers' Meetings](http://llvm.org/devmtg/).
  * [LLVM Weekly](http://llvmweekly.org/) - Weekly newsletter about LLVM.


## Communities

  * [/r/Compilers](https://www.reddit.com/r/Compilers) - Subreddit community about the theory and development of compilers.
  * [/r/ProgrammingLanguages](https://reddit.com/r/ProgrammingLanguages) - Subreddit community that is dedicated to discussion of programming languages, programming language theory, design, their syntax and compilers.


## Verticals

  * [68 Resources for Creating Programming Languages](https://tomassetti.me/resources-create-programming-languages/).
  * [Awesome Static Analysis](https://github.com/mre/awesome-static-analysis).
  * [Compiler Conferences, Workshops and Journals](https://github.com/MattPD/cpplinks/blob/master/compilers.md#conferences).
  * [Languages and Compilers Network Graph](https://mohd-akram.github.io/languages/).
  * [miniKanren.org](http://minikanren.org) - Papers, Talks and Implementations of miniKanren and microKanren.
  * [PLT Enlightenment](http://steshaw.org/plt/).
  * [Resources for Amateur Compiler Writers](https://c9x.me/compile/bib/).
  * [SSA Form Bibliography](http://www.dcs.gla.ac.uk/~jsinger/ssa.html).
  * [Summer Schools](https://gist.github.com/biboudis/377b4a4de4d1718df2d0).
  * [The Witchcraft Compiler Collection](https://github.com/endrazine/wcc).
  * [TypeFunc](https://github.com/williamdemeo/TypeFunc).


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ahmad Alhour](http://aalhour.com) has waived all copyright and related or neighboring rights to this work.

The logo was designed using [TextCraft](https://textcraft.net).
