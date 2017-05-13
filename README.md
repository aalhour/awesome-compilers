# Awesome Compilers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome resources, tools, technologies and source code projects in the field of Compilers, Interpreters and Runtimes.

## Table of Contents

  * [Learning](#learning)
    + [Books](#books)
    + [Papers](#papers)
      * [Researchers and Institutes](#researchers-and-institutes)
    + [Courses](#courses)
    + [Talks](#talks)
    + [Articles](#articles)
    + [Tutorials](#tutorials)
    + [Community Discussions](#community-discussions)
  * [Projects](#projects)
    + [Production-Ready](#production-ready)
    + [Educational](#educational)
  * [Construction Technologies](#construction-technologies)
     + [Backends](#backends)
     + [Frontends](#frontends)
     + [Runtimes](#runtimes)
  * [Verticals](#verticals)
  * [Communities](#communities)

-----------------------------------------


## Learning

### Books

  * [Advanced Compiler Design and Implementation, S. Muchnick](https://www.amazon.com/dp/1558603204).
  * [Advanced Topics in Types and Programming Languages, B. Pierce](https://www.amazon.com/dp/0262162288).
  * [Basics of Compiler Design, T. Mogensen](http://www.diku.dk/hjemmesider/ansatte/torbenm/Basics/).
  * [Beautiful Racket - How to Make Your Own PL with Racket, M. But­t­er­ick](http://beautifulracket.com).
  * [Building an Optimizing Compiler, B. Morgan](https://www.amazon.com/dp/155558179X).
  * [Crafting Interpreters: A Handbook for Making Programming Languages, B. Nystrom](http://www.craftinginterpreters.com/).
    + [GitHub Repo](https://github.com/munificent/craftinginterpreters).
    + [HackerNews Discussion](https://news.ycombinator.com/item?id=13406081).
  * [Create Your Own Programming Language](http://createyourproglang.com/).
    + [HackerNews Discussion](https://news.ycombinator.com/item?id=813133).
  * [Computer Systems: A Programmer’s Perspective, R. Bryant, D. O'Hallaron](https://www.amazon.com/dp/9332573905) - A comprehensive treatement of Computer Systems including Compilers and Interpreters.
  * [Compiling with Continuations, A. Appel](https://www.amazon.com/dp/052103311X).
  * [Elements of Computing Systems, N. Nisan, S. Schocken](https://www.amazon.com/dp/0262640686) - A book about computer construction from Nand Gates, through Assemblers, Compilers up to Operating Systems and Tetris game development.
  * [Engineering a Compiler, K. Cooper, L. Torczon](https://www.amazon.com/dp/012088478X).
  * [Essentials of Programming Languages, D. Friedman & M. Wand](https://www.amazon.com/dp/0262062798).
  * [Language Implementation Patterns, T. Parr](https://www.amazon.com/dp/193435645X).
  * [Modern Compiler Implementation in C, A. Appel](https://www.cs.princeton.edu/~appel/modern/c/).
  * [Modern Compiler Implementation in ML, A. Appel](https://www.cs.princeton.edu/~appel/modern/ml/).
  * [Modern Compiler Implementation in Java, A. Appel](https://www.cs.princeton.edu/~appel/modern/java/).
  * [Optimizing Compilers for Modern Architectures, R. Allen & K. Kennedy](https://www.amazon.com/dp/1558602860/).
  * [Programming Language Pragmatics, M. Scott](https://www.amazon.com/dp/0123745144).
  * [Programming Languages: Application and Interpretation, S. Krishnamurthi](http://cs.brown.edu/courses/cs173/2012/book/).
    + [PDF Document](http://cs.brown.edu/courses/cs173/2012/book/book.pdf).
  * [Programming Languages: Theory and Practice](http://people.cs.uchicago.edu/~blume/classes/aut2008/proglang/text/offline.pdf).
  * Project Oberon, N. Wirth & J. Gutknecht - [1992 Edition](http://people.inf.ethz.ch/wirth/ProjectOberon1992.pdf), [2013 Edition](http://www.cs.cmu.edu/~fp/courses/15312-f04/handouts/).
  * [The SSA Book, Springer, Zadeck](http://ssabook.gforge.inria.fr/latest/book.pdf).
  * [Types and Programming Languages, B. Pierce](https://www.amazon.com/dp/0262162091).
  * [Virtual Machines, Smith and Nait](https://www.amazon.com/dp/1558609105).
  * [Virtual Machines, Iain Craig](https://www.amazon.com/dp/1852339691).
  * [Warren's Abstract Machine - Prolog in Haskell, H. Aït-Kaci](https://mitpress.mit.edu/books/warrens-abstract-machine).


### Papers

  * [A Brief History of JIT Compilation, J. Aycock](http://eecs.ucf.edu/~dcm/Teaching/COT4810-Spring2011/Literature/JustInTimeCompilation.pdf).
  * [A Flexible Prolog Interpreter in Python, C. Bolz & M. Leuschel](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.103.1886&rep=rep1&type=pdf).
  * [A Graph Higher-Order IR, R. Leißa, M. Koster & S. Hack](http://compilers.cs.uni-saarland.de/papers/lkh15_cgo.pdf).
  * [A Prolog Interpreter in Python, C. Bolz](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.121.8625&rep=rep1&type=pdf).
  * [A Simple Multi-Processor Computer Based on Subleq, O. Mazonka, A. Kolodin](https://arxiv.org/abs/1106.2593).
  * [Compiler Construction Using Scheme, E. Hilsdale, J. Ashley, R. Dybvig & D. Friedman](https://www.cs.indiana.edu/~dyb/pubs/fple95.pdf).
  * [Compiling with Continuations: Continued, A. Kennedy](https://www.microsoft.com/en-us/research/wp-content/uploads/2007/10/compilingwithcontinuationscontinued.pdf).
  * [Machine Code Obfuscation via Instruction Set Reduction and CFG Linearization, C. Jonischkeit](https://kirschju.re/static/ba_jonischkeit_2016.pdf).
  * [`MOV` is Turing-Complete, S. Dolan](https://www.cl.cam.ac.uk/~sd601/papers/mov.pdf).
    + Discussions: [HN](https://news.ycombinator.com/item?id=6309631), [Reddit](https://redd.it/1nft0x).
  * [Nanopass Framework for Commercial Compiler Development, A. Keep & R. Dybvig](https://www.cs.indiana.edu/~dyb/pubs/commercial-nanopass.pdf).
  * [Nanopass Framework for Compiler Education, D. Sarkar, O. Waddell & R. Dybvig](https://www.cs.indiana.edu/~dyb/pubs/nano-jfp.pdf).
  * [Packrat Parsing Thesis on PEG, B. Ford](https://pdos.csail.mit.edu/~baford/packrat/thesis/).
  * [PEG-based transformer provides front-end, middle-end and back-end stages in a simple Compiler, I. Piumarta](http://www.vpri.org/pdf/tr2010003_PEG.pdf).
  * [Pycket: A Tracing JIT for a Functional Language](http://homes.soic.indiana.edu/samth/pycket-draft.pdf).
  * [PyPy’s Approach to VM Construction, A. Rigo & S. Pedroni](http://www.csc.lsu.edu/~gb/csc7700/Reading/pypy-vm-construction.pdf).
  * [Simple and Efficient Construction of SSA Form](http://compilers.cs.uni-saarland.de/projects/ssaconstr/).
  * [SSA-based Register Allocation, S. Hack & G. Goos](http://compilers.cs.uni-saarland.de/projects/ssara/).
  * [The Essence of Compiling with Continuations, C. Flanagan, A. Sabry, B. Duba & M. Felleisen](https://users.soe.ucsc.edu/~cormac/papers/pldi93.pdf).
  * [The Page-Faults Weird Machine: Lessons in Instruction-less Computation, J. Bangert, S. Bratus, R. Shapiro, S. Smith](https://www.usenix.org/system/files/conference/woot13/woot13-bangert.pdf).
  * [Trace-based JIT Compilation for Lazy Functional Languages, T. Schilling](http://files.catwell.info/misc/mirror/tracing-jit-haskell-schilling.pdf).

#### Researchers and Institutes

  * [C. Bolz’s Research Publications](https://scholar.google.com/citations?user=S0rpYpkAAAAJ).
  * [Compilers Lab at Saarland University](http://compilers.cs.uni-saarland.de).
  * [Packrat Parsing (PEG) Papers and Resources](http://bford.info/packrat/).


### Courses

  * [Compilers Construction, Cambridge](http://www.cl.cam.ac.uk/teaching/1516/CompConstr/materials.html) - an introduction to compiler construction course from the University of Cambridge.
  * [Compiler Construction for Undergrads, RICE University](https://www.clear.rice.edu/comp412/Lectures/) - an introduction to compiler construction and language translators course from the RICE University.
  * Compilers Theory, Stanford - [YouTube](https://www.youtube.com/playlist?list=PLLH73N9cB21VSVEX1aSRlNTufaLK1dTAI), [Stanford.edu](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/), [Class Notes](http://web.stanford.edu/class/cs143/) - an introduction to Compilers theory and construction course from Stanford.
  * [Design and Construction of Compilers, University of Texas](https://lambda.uta.edu/cse5317/) - _TODO_.
    + Lecture Notes: [PDF Document](https://lambda.uta.edu/cse5317/notes.pdf), [Single HTML Page](https://lambda.uta.edu/cse5317/long/long.html).
  * [DSL Design and Implementation Summer School](http://vjovanov.github.io/dsldi-summer-school/) - a Summer School program on the topics of DSL Design and Implementation hosted by the EPFL University.
  * [Foundations of Programming Languages](http://www.cs.cmu.edu/~fp/courses/15312-f04/) - a course that covers many of the concepts underlying the design, definition, implementation and use of modern programming languages from a formal standpoint.
  * [Nand2Tetris: How to Build a Computer from First Principles, Part 2](https://www.coursera.org/learn/nand2tetris2) - This 2nd part of the Nand2Tetris course covers basic language design and elementary compiler construction concepts in addition to many other topics on a basic level.
  * [NPTEL's Principles of Compiler Design Course](https://www.youtube.com/playlist?list=PLbMVogVj5nJQNjkHZgwuAlfQ9tzmQDxjA) - an introductory course from NPTEL on Compiler Design.
  * [NPTEL's Compiler Design Course](http://nptel.ac.in/courses/106108052/32) - a slightly more advanced course than their Principles of Compiler Design course, covers SSA Form to a good degree.
    + [YouTube Video Playlist](https://www.youtube.com/playlist?list=PLbMVogVj5nJTmKzaSlCpGgi7qxgcRRs8h).
  * [Programming Languages: Part A, by Grossman](https://www.coursera.org/learn/programming-languages) - Part 1 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming.
  * [Programming Languages: Part B, by Grossman](https://www.coursera.org/learn/programming-languages-part-b) - Part 2 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming..
  * [Programming Languages: Part C, by Grossman](https://www.coursera.org/learn/programming-languages-part-c) - Part 3 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming..
  * [Types, Logic, Semantics, and Verification from Oregon University's Summer School](https://www.cs.uoregon.edu/research/summerschool/summer15/curriculum.html) - a Summer School program that consists of 80 minute lectures presented by internationally recognized leaders in programming languages and formal reasoning research.
  * [Virtual Machines and Managed Runtimes, UCB CS294](http://www.wolczko.com/CS294/) - an introductory course on Virtual Machines and Managed Runtimes from the University of Berkeley.
  * [Virtual Machines Summer School 2016 (VMSS 2016)](http://soft-dev.org/events/vmss16/) - VMSS is a Summer School program that aims to give an overview of the field, targeted at early career researchers.
    + [YouTube Videos Playlist](https://www.youtube.com/playlist?list=PLJq3XDLIJkib2h2fObomdFRZrQeJg4UIW).


### Talks

  * [Anders Hejlsberg on Modern Compiler Construction](https://channel9.msdn.com/Blogs/Seth-Juarez/Anders-Hejlsberg-on-Modern-Compiler-Construction).
  * [An Introduction to Combinator Compilers and Graph Reduction Machines](https://www.youtube.com/watch?v=GawiQQCn3bk).
  * [Building an Interpreter in RPython](https://www.youtube.com/watch?v=9tDpjzPLvNY).
  * [Curry On! Conference](http://www.curry-on.org/) - Programming Languages Conference.
    + [YouTube Channel](https://www.youtube.com/channel/UC-WICcSW1k3HsScuXxDrp0w/videos).
  * [Exploring Python’s Bytecode](https://ep2016.europython.eu/media/conference/slides/exploring-python-bytecode.pdf).
  * [Java AOT (Ahead of Time) Compilation](https://2016.javazone.no/program/java-aot-compilation).
  * [Lang.NEXT Conference 2014](https://channel9.msdn.com/Events/Lang-NEXT/Lang-NEXT-2012).
  * [Lang.NEXT Conference 2014](https://channel9.msdn.com/Events/Lang-NEXT/Lang-NEXT-2014).
  * [MetaScala: A Tiny DIY JVM](https://skillsmatter.com/skillscasts/4916-metascala-a-tiny-diy-jvm) - Metascala is a tiny metacircular Java Virtual Machine (JVM) written in the Scala programming language.
  * [Meta-Tracing, RPython and PyPy](https://ia601503.us.archive.org/32/items/vmss16/bolz.pdf).
  * [Python, Linkers and Virtual Memory - PYCON US](https://www.youtube.com/watch?v=twQKAoq2OPE).
  * [Reverse Engineering the MOS 6502 CPU](https://youtube.com/watch?v=fWqBmmPQP40).
  * [Single Static Assignment Form Seminar](http://compilers.cs.uni-saarland.de/ssasem/) - an introductory seminar on SSA Form, Compiler Optimizations under it and its applications in other areas such as Program Analysis and Verification.
  * The SSA (Static Single Assignment) Form - [Part 1](https://www.youtube.com/watch?v=Q7hlcuCGbxE), [Part 2](https://www.youtube.com/watch?v=FV9fq_HfPsM), [Part 3](https://www.youtube.com/watch?v=GyYiic8trCE) - Video Lectures from NPTEL's Compilers Course on SSA Form (see: [Courses](#courses) for more information).
  * [Type-Driven Development with Idris](https://www.youtube.com/watch?v=X36ye-1x_HQ).
  * [Understanding Compiler Optimization](https://www.youtube.com/watch?v=FnGCDLhaxKU).


### Articles

  * [Accidentally Turing Complete](http://beza1e1.tuxen.de/articles/accidentally_turing_complete.html).
  * Adventures in JIT Compilation by Eli Bendersky:
    + [Part 1 - An Interpreter](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-1-an-interpreter/).
    + [Part 2 - An x64 JIT](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-2-an-x64-jit/).
    + [Part 3 - LLVM](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-3-llvm/).
    + [Part 4 - In Python](http://eli.thegreenplace.net/2017/adventures-in-jit-compilation-part-4-in-python/).
  * [How to Compile with Continuations](http://matt.might.net/articles/cps-conversion/).


### Tutorials

  * [Compiler Optmization Tutorial](https://www.youtube.com/watch?v=SfV8aRX0YY0).
  * [Metacompiler Tutorial, Part 1](http://www.bayfronttechnologies.com/mc_tutorial.html).
  * [How I Wrote a Programming Language, and How You Can Too](https://medium.com/@william01110111/the-programming-language-pipeline-91d3f449c919).
    + Discussions: [Reddit](https://redd.it/62ixbc).


### Community Discussions

  * [Difference between an LL and Recursive Descent parser?](http://stackoverflow.com/questions/1044600/difference-between-an-ll-and-recursive-descent-parser) - StackOverflow question.
  * Does a compiler use all x86 instructions? - [@HackerNews](https://news.ycombinator.com/item?id=12352959), [@Reddit](https://redd.it/4zgawj) - Article discussions on HackerNews and Reddit.
  * [How to Write a Compiler](https://redd.it/4o7qag) - Article discussion at Reddit.
  * [How to Write a Very Basic Compiler](https://softwareengineering.stackexchange.com/questions/165543/how-to-write-a-very-basic-compiler) - StackExchange thread.
  * [How to Write a Prolog Interpreter in a Purely Functional Language](https://cs.stackexchange.com/questions/6618/how-to-implement-a-prolog-interpreter-in-a-purely-functional-language) - StackExchange thread.
    + Discussions: [Reddit](https://redd.it/4u2xt3).
  * [Implementing Type Inference](http://stackoverflow.com/questions/415532/implementing-type-inference) - StackOverflow 
  * [I want to build a VM, any good references?](https://softwareengineering.stackexchange.com/questions/178224/i-want-to-build-a-virtual-machine-are-there-any-good-references) - StackExchange thread.
  * [Resources for Amatuer Compilers Writers](https://redd.it/4u15t1).
  * [What are the latest research trends in Compilers and PLs](https://www.quora.com/What-are-the-latest-research-trends-in-compilers-and-programming-languages) - Quora thread.


## Projects

### Production-Ready

_WIP_.


### Educational

_WIP_.


## Construction Technologies

### Backends

_WIP_.


### Frontends

_WIP_.


### Runtimes

_WIP_.


## Verticals

  * [Languages and Compilers Network Graph](https://mohd-akram.github.io/languages/).
  * [PLT Enlightenment](http://steshaw.org/plt/).
  * [SSA Form Bibliography](http://www.dcs.gla.ac.uk/~jsinger/ssa.html).
  * [Summer Schools](https://gist.github.com/biboudis/377b4a4de4d1718df2d0).
  * [The Witchcraft Compiler Collection](https://github.com/endrazine/wcc).
  * [TypeFunc](https://github.com/williamdemeo/TypeFunc).


## Communities

  * [/r/Compilers](https://www.reddit.com/r/Compilers) - a subreddit community about the theory and development of compilers.
  * [/r/ProgrammingLanguages](https://reddit.com/r/ProgrammingLanguages) - a subreddit communit that is dedicated to discussion of programming languages, programming language theory, design, their syntax and compilers.

