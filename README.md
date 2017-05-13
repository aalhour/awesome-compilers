# Awesome Compilers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome resources, learning materials, tools, frameworks, platforms, technologies and source code projects in the field of Compilers, Interpreters and Runtimes. This list has a bias towards education.

## Table of Contents

  * [Learning](#learning)
    + [Books](#books)
    + [Papers](#papers)
      * [Researchers and Institutes](#researchers-and-institutes)
    + [Specifications](#specifications)
    + [Courses](#courses)
    + [Talks](#talks)
    + [Articles](#articles)
    + [Tutorials](#tutorials)
    + [Community Discussions](#community-discussions)
  * [Projects](#projects)
    + [Production-Ready](#production-ready)
    + [Educational and Toys](#educational-and-toys)
  * [Tools and Frameworks](#tools-and-frameworks)
     + [Language Agnostic](#language-agnostic)
     + [C (as a Backend)](#c-as-a-backend)
     + [CLR](#clr)
     + [D](#d)
     + [Graal](#graal)
     + [JavaScript](#javascript)
     + [JVM](#jvm)
     + [Kotlin](#kotlin)
     + [Python](#python)
       * [Lists of Python Parsing Tools](#lists-of-python-parsing-tools).
     + [Rust](#rust)
  * [Runtimes and VMs](#runtimes-and-vms)
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
    + Discussions: [HN](https://news.ycombinator.com/item?id=13406081).
  * [Create Your Own Programming Language](http://createyourproglang.com/).
    + Discussions: [HN](https://news.ycombinator.com/item?id=813133).
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
  * [Using Datalog with Binary Decision Diagrams for Program Analysis, J. Whaley, D. Avots, M. Carbin & M. Lam](https://people.csail.mit.edu/mcarbin/papers/aplas05.pdf).

#### Researchers and Institutes

  * [C. Bolz’s Research Publications](https://scholar.google.com/citations?user=S0rpYpkAAAAJ).
  * [Compilers Lab at Saarland University](http://compilers.cs.uni-saarland.de).
  * [Packrat Parsing (PEG) Papers and Resources](http://bford.info/packrat/).

### Specifications

  * [The CLI (Common Language Interface) Specification (ECMA-335)](http://www.ecma-international.org/publications/standards/Ecma-335.htm).
  * [The JVM (Java Virtual Machine) Specification](https://docs.oracle.com/javase/specs/jvms/se8/html/).

### Courses

  * [Compilers Construction, Cambridge](http://www.cl.cam.ac.uk/teaching/1516/CompConstr/materials.html) - an introduction to compiler construction course from the University of Cambridge.
  * [Compiler Construction for Undergrads, RICE University](https://www.clear.rice.edu/comp412/Lectures/) - an introduction to compiler construction and language translators course from the RICE University.
  * Compilers Theory, Stanford - [YouTube](https://www.youtube.com/playlist?list=PLLH73N9cB21VSVEX1aSRlNTufaLK1dTAI), [Stanford.edu](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/), [Class Notes](http://web.stanford.edu/class/cs143/) - an introduction to Compilers theory and construction course from Stanford.
  * [Design and Construction of Compilers, University of Texas](https://lambda.uta.edu/cse5317/) - Design and construction of compilers including lexical analysis, parsing, code generation techniques, error analysis and simple code optimizations.
    + Lecture Notes: [PDF](https://lambda.uta.edu/cse5317/notes.pdf), [HTML](https://lambda.uta.edu/cse5317/long/long.html).
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
  * [Lang.NEXT Conference 2012](https://channel9.msdn.com/Events/Lang-NEXT/Lang-NEXT-2012).
  * [Lang.NEXT Conference 2014](https://channel9.msdn.com/Events/Lang-NEXT/Lang-NEXT-2014).
  * [MetaScala: A Tiny DIY JVM](https://skillsmatter.com/skillscasts/4916-metascala-a-tiny-diy-jvm) - Metascala is a tiny metacircular Java Virtual Machine (JVM) written in the Scala programming language.
  * [Meta-Tracing, RPython and PyPy](https://ia601503.us.archive.org/32/items/vmss16/bolz.pdf).
  * [Python, Linkers and Virtual Memory - PYCON US](https://www.youtube.com/watch?v=twQKAoq2OPE).
  * [Reverse Engineering the MOS 6502 CPU](https://youtube.com/watch?v=fWqBmmPQP40).
  * [Single Static Assignment Form Seminar](http://compilers.cs.uni-saarland.de/ssasem/) - an introductory seminar on SSA Form, Compiler Optimizations under it and its applications in other areas such as Program Analysis and Verification.
  * [The JVM (Java Virtual Machine) Architecture](https://www.youtube.com/watch?v=ZBJ0u9MaKtM).
  * [The MoVfuscator: turning mov into a soul crushing RE nightmare](https://www.youtube.com/watch?v=R7EEoWg6Ekk).
    + Discussions: [HN](https://news.ycombinator.com/item?id=9751312), [Reddit](https://redd.it/4zl8mh).
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
  * [Introducing the B3 JIT Compiler](https://webkit.org/blog/5852/introducing-the-b3-jit-compiler/).

### Tutorials

  * [Compiler Optmization Tutorial](https://www.youtube.com/watch?v=SfV8aRX0YY0).
  * [Metacompiler Tutorial, Part 1](http://www.bayfronttechnologies.com/mc_tutorial.html).
  * [How I Wrote a Programming Language, and How You Can Too](https://medium.com/@william01110111/the-programming-language-pipeline-91d3f449c919).
    + Discussions: [Reddit](https://redd.it/62ixbc).

### Community Discussions

  * [Can we stop recommending the Dragon Book, please?](https://meta.stackexchange.com/questions/25840/can-we-stop-recommending-the-dragon-book-please) - A StackExchange thread criticising the [Dragons Book](https://www.amazon.com/dp/0321486811).
  * [Difference between an LL and Recursive Descent parser?](http://stackoverflow.com/questions/1044600/difference-between-an-ll-and-recursive-descent-parser) - StackOverflow question.
  * Does a compiler use all x86 instructions? - [@HN](https://news.ycombinator.com/item?id=12352959), [@Reddit](https://redd.it/4zgawj) - Article discussions on HN and Reddit.
  * [How to Write a Compiler](https://redd.it/4o7qag) - Article discussion on Reddit.
  * [How to Write a Very Basic Compiler](https://softwareengineering.stackexchange.com/questions/165543/how-to-write-a-very-basic-compiler) - StackExchange thread.
  * [How to Write a Prolog Interpreter in a Purely Functional Language](https://cs.stackexchange.com/questions/6618/how-to-implement-a-prolog-interpreter-in-a-purely-functional-language) - StackExchange thread.
    + Discussions: [Reddit](https://redd.it/4u2xt3).
  * [Implementing Type Inference](http://stackoverflow.com/questions/415532/implementing-type-inference) - StackOverflow question.
  * [I want to build a VM, any good references?](https://softwareengineering.stackexchange.com/questions/178224/i-want-to-build-a-virtual-machine-are-there-any-good-references) - StackExchange thread.
  * [Resources for Amatuer Compilers Writers](https://redd.it/4u15t1) - Question on Reddit.
  * [What are the good open source implementations of Java Virtual Machine?](http://stackoverflow.com/questions/1621899/what-are-the-good-open-source-implementations-of-java-virtual-machine).
  * [What are the latest research trends in Compilers and PLs](https://www.quora.com/What-are-the-latest-research-trends-in-compilers-and-programming-languages) - Quora thread.


## Projects

_This section aims at listing code projects of Compilers, Interpreters, Translators, Runtimes, Virtual Machines and the like._

### Production-Ready

  * [Chez Scheme Compiler](https://github.com/cisco/ChezScheme).
  * [Lua Programming Language](https://github.com/LuaDist/lua).
    + [Lua's Annotated Source Code](http://stevedonovan.github.io/lua-5.1.4/).
  * [Nim Language Compiler](https://github.com/nim-lang/Nim).
  * [Red Programming Language](https://github.com/red/red).
  * [TypeScript Language Compiler](https://github.com/Microsoft/TypeScript).

### Educational and Toys

  * [C4](https://github.com/rswier/c4) - C Lang in 4 Functions.
    + Discussions: [HN](https://news.ycombinator.com/item?id=8558822).
  * [CarpVM](https://github.com/tekknolagi/carp) - An experimental VM implementation in C.
  * [Gecho](https://github.com/tekknolagi/gecho) - A simple-stack language implementation in C.
  * [Hython](https://github.com/mattgreen/hython) - A Haskell-powered Python 3 interpreter.
    + Discussions: [Reddit](https://redd.it/46f8j4).
  * [MetaScala](https://github.com/lihaoyi/Metascala) - A Metacircular JVM implementation in Scala.
  * [Poprc](https://github.com/HackerFoo/poprc) - A compiler for the Popr Language.
  * [PyCOOLC](https://github.com/aalhour/PyCOOLC) - A compiler for the COOL Programming Language written in Python 3.
  * [RabbitVM](https://github.com/rabbitvm/rabbit) - A RISC-based VM implementation in C.
  * [stack_cpu](https://github.com/dsturnbull/stack_cpu) - a Stack-machine simulator.
  * [The Super Tiny Compiler](https://github.com/thejameskyle/the-super-tiny-compiler) - a tiny educational compiler project in JavaScript.
    + Discussions: [HN](https://news.ycombinator.com/item?id=11395656).
  * [tinyc.c](http://www.iro.umontreal.ca/~felipe/IFT2030-Automne2002/Complements/tinyc.c) - A Tiny-C language compiler in C.


## Tools and Frameworks

### Language Agnostic

  * [B3: The Bare Bones Backend](https://webkit.org/docs/b3/) - WebKit's optimizing JIT Compiler for procedures containing C-like code.
  * [LLILCL](https://github.com/dotnet/llilc) - An LLVM-based Compiler Backend for .NET Core.
  * [LLVM](http://llvm.org/) - The LLVM Compiler-Backend Framework.
  * [MicroVM](http://microvm.github.io/) - The "Mu" Framewrok for Programming Languages development based on the MuVM Specification.
  * [Movfuscator Compiler](https://github.com/xoreaxeaxeax/movfuscator) - The `M/o/Vfuscator` compiles programs into "mov" instructions, and only "mov" instructions.
  * [QBE: The Quick Backend](http://c9x.me/compile/) - A pure C embeddable SSA-based compiler backend.
  * [Summus](https://github.com/igor84/summus) - A (reusable) basic compiler frontend implementation using LLVM as a backend.

### C (as a Backend)

  * [GCC](https://gcc.gnu.org/) - The GNU Compiler Collection.
  * [libFirm](http://pp.ipd.kit.edu/firm/) - A C library that provides a graph-based intermediate representation, optimizations, and assembly code generation suitable for use in compilers.
  * [libJIT](https://www.gnu.org/software/libjit/) - a library that provides generic Just-In-Time compiler functionality independent of any particular bytecode, language, or runtime.
  * [myJIT](http://myjit.sourceforge.net/) - A library for machine-code generation and execution at run-time.
  * [PCC](http://pcc.ludd.ltu.se/) - The Portable C Compiler.
  * [TCC](http://bellard.org/tcc/) - The Tiny C Compiler.

### CLR

  * [Cecile](http://www.mono-project.com/docs/tools+libraries/libraries/Mono.Cecil/) - A library to generate and inspect programs and libraries in the ECMA CIL format.
  * [ILSpy](http://ilspy.net) - A .NET Decompiler.
  * [Reflector](http://www.red-gate.com/products/dotnet-development/reflector/) - A .NET Decompiler.
  * [Reflexil](http://sebastien.lebreton.free.fr/reflexil/) - An an assembly editor which can be used as a plugin with other .NET/CLR tools.
  
### D

  * [dunnart](https://github.com/pwil3058/dunnart) - LALR(1) Parser Generator.
  * [FancyPars-lite](https://github.com/UplinkCoder/FancyPars-lite) - A fast parser generator.
  * [libdparse](https://github.com/dlang-community/libdparse) - A library allowing to build lexers and parsers. Contains a lexer and a parser for the D language itself.
  * [llvm-d](https://github.com/Calrama/llvm-d) - D bindings for LLVM.
  * [Pegged](https://github.com/PhilippeSigaud/Pegged) - design, test and generate parsers for PEG grammars.

### Graal

  * [Graal](https://github.com/graalvm/graal) - High-Performance Polyglot Runtime.
  * [Graal Core](https://github.com/graalvm/graal-core) - Compiler and Truffel Partial Evaluator.
  * [Graal VM](https://github.com/graalvm/graalvm) - Graal's multi-language VM distribution.

### JavaScript

  * [Babel.js](https://github.com/babel/babel) - Next-generation JavaScript Compiler.
  * [IRHudra](http://mrale.ph/irhydra/2/) - A tool for displaying intermediate representations used by V8 and Dart VM optimizing compilers.
    + [GitHub Repo](https://github.com/mraleph/irhydra).
  * [JISON](http://zaa.ch/jison/docs/) - a context-free grammar parser generator for JavaScript.
  * [PEG.js](https://pegjs.org) - A simple parser generator for JavaScript.

### JVM

  * [ANTLR](http://www.antlr.org) - A parser generator for reading, processing, executing, or translating structured text or binary files.
  * [BYAAC/J](http://byaccj.sourceforge.net) - BYACC/Java is an extension of the Berkeley v 1.8 YACC-compatible parser generator for Java.
  * [JavaCC](https://javacc.org) - Java Compiler Construction and Parser Generator Toolkit.
  * [JFlex](http://www.jflex.de) - JFlex is a lexical analyzer generator for Java with full Unicode support.
  * [JLex](http://www.cs.princeton.edu/~appel/modern/java/JLex/) - JLex is a lexical analyzer generator, that can be used in combination with CUP.

### Kotlin

  * [The Whimsy Compiler Framework](https://github.com/norswap/whimsy) - A compiler framework research project in Kotlin.

### Python

  * [AST](https://docs.python.org/3.5/library/ast.html) - Python's builtin Abstract Syntax Tree package.
  * [Dis](https://docs.python.org/3.6/library/dis.html) - Python's builtin Disassembler package.
  * [Parsing](http://www.canonware.com/Parsing/) - A pure-Python module that implements an LR(1) parser generator, as well as CFSM and GLR parser drivers.
  * [PLY](http://www.dabeaz.com/ply/) - An implementation of lex and yacc parsing tools for Python.
  * [PyParsing](http://pyparsing.wikispaces.com/) - an alternative approach to creating and executing simple grammars, vs. the traditional lex/yacc approach, or the use of regular expressions.
  * [RPLY](https://github.com/alex/rply) - A port of the PLY project to RPython.
  * [RPython](https://rpython.readthedocs.io/en/latest/) - RPython is a framework for the implementatation of dynamic languages.

#### Lists of Python Parsing Tools

  * [List of Language Parsing Tools at the Python Wiki](https://wiki.python.org/moin/LanguageParsing).
  * [Survey of Python Parsers, by Ned Batchelder](http://nedbatchelder.com/text/python-parsers.html).

### Rust

  * [Combine](https://github.com/Marwes/combine) - Parser Combinator Library for Rust.
  * [IronLLVM](https://github.com/jauhien/iron-llvm) - Safe LLVM bindings for Rust.
  * [LALRPOP](https://github.com/nikomatsakis/lalrpop) -  LR(1) parser generator for Rust
  * [Nom](https://github.com/Geal/nom) - Parser Combinator Framework.
  * [PEG](https://github.com/kevinmehall/rust-peg) - A PEG Parser Generator.
  * [Pest](https://github.com/pest-parser/pest) - A PEG Parser Generator.
  * [RLS](https://github.com/rust-lang-nursery/rls) - The Rust Language Server implementation (aka RLS).

## Runtimes and VMs

  * [CakeML](https://github.com/CakeML/cakeml).
  * [HLVM](http://www.ffconsultancy.com/ocaml/hlvm/).
  * JVM Implementations:
    + [OpenJDK](http://openjdk.java.net/).
    + [Kaffee](https://github.com/kaffe/kaffe).
    + [JamVM](http://jamvm.sourceforge.net) - [GitHub project mirror](https://github.com/cfriedt/jamvm).
    + [Apache Harmony](https://harmony.apache.org/).
    + [Other JVM Runtimes](https://en.wikipedia.org/wiki/List_of_Java_virtual_machines).


## Verticals

  * [Languages and Compilers Network Graph](https://mohd-akram.github.io/languages/).
  * [PLT Enlightenment](http://steshaw.org/plt/).
  * [Resources for Amateur Compiler Writers](https://c9x.me/compile/bib/).
  * [SSA Form Bibliography](http://www.dcs.gla.ac.uk/~jsinger/ssa.html).
  * [Summer Schools](https://gist.github.com/biboudis/377b4a4de4d1718df2d0).
  * [The Witchcraft Compiler Collection](https://github.com/endrazine/wcc).
  * [TypeFunc](https://github.com/williamdemeo/TypeFunc).


## Communities

  * [/r/Compilers](https://www.reddit.com/r/Compilers) - a subreddit community about the theory and development of compilers.
  * [/r/ProgrammingLanguages](https://reddit.com/r/ProgrammingLanguages) - a subreddit communit that is dedicated to discussion of programming languages, programming language theory, design, their syntax and compilers.


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ahmad Alhour](http://aalhour.de) has waived all copyright and related or neighboring rights to this work.
