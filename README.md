# Awesome Compilers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome resources, tools, technologies and source code projects in the field of Compilers, Interpreters and Runtimes.

## Table of Contents

  * [Learning](#learning)
    + [Books](#books)
    + [Papers](#papers)
    + [Courses](#courses)
    + [Talks](#talks)
    + [Articles](#articles)
    + [Tutorials](#tutorials)
    + [Community Discussions](#community-discussions)
  * [Projects](#projects)
    + [Production-Ready](#production-ready)
    + [Educational](#educational)
  * [Construction Technologies]()
     + [Compiler Backends]().
     + [Compiler Frontends]().
     + [Runtimes]().
  * [Verticals and Community Platforms]()

-----------------------------------------

## Learning

### Books

  * [Advanced Compiler Design and Implementation](https://www.amazon.com/dp/1558603204) - _TODO_.
  * [Advanced Topics in Types and Programming Languages](https://www.amazon.com/dp/0262162288) - _TODO_.
  * [A Simple Multi-Processor Computer Based on Subleq](https://arxiv.org/abs/1106.2593) - _TODO_.
  * [Basics of Compiler Design, T. Mogensen](http://www.diku.dk/hjemmesider/ansatte/torbenm/Basics/) - a introductory book on the Basics of Compiler Construction.
  * [Beautiful Racket - How to Make Your Own PL with Racket](http://beautifulracket.com) - _TODO_.
  * [Building an Optimizing Compiler](https://www.amazon.com/dp/155558179X) - _TODO_.
  * [Crafting Interpreters: A Handbook for Making PLs](http://www.craftinginterpreters.com/) - _TODO_.
    + [GitHub Repo](https://github.com/munificent/craftinginterpreters).
    + [HackerNews Discussion](https://news.ycombinator.com/item?id=13406081).
  * [Create Your Own Programming Language](http://createyourproglang.com/) - _TODO_.
    + [HackerNews Discussion](https://news.ycombinator.com/item?id=813133).
  * [Computer Systems: A Programmer’s Perspective, R. Bryant, D. O'Hallaron](https://www.amazon.com/dp/9332573905) - A comprehensive treatement of Computer Systems including Compilers and Interpreters.
  * [Compiling with Continuations](https://www.amazon.com/dp/052103311X) - _TODO_.
  * [Elements of Computing Systems, N. Nisan, S. Schocken](https://www.amazon.com/dp/0262640686) - A book about computer construction from Nand Gates, through Assemblers, Compilers up to Operating Systems and Tetris game development.
  * [Engineering a Compiler, K. Cooper, L. Torczon](https://www.amazon.com/dp/012088478X) - _TODO_.
  * [Essentials of Programming Languages](https://www.amazon.com/dp/0262062798) - _TODO_.
  * [Language Implementation Patterns](https://www.amazon.com/dp/193435645X) - _TODO_.
  * Machine Code Obfuscation via IS Reduction and CFG Linearization - PDF
  * [Modern Compiler Implementation in C](https://www.cs.princeton.edu/~appel/modern/c/) - _TODO_.
  * [Modern Compiler Implementation in ML](https://www.cs.princeton.edu/~appel/modern/ml/) - _TODO_.
  * [Modern Compiler Implementation in Java](https://www.cs.princeton.edu/~appel/modern/java/) - _TODO_.
  * [Optimizing Compilers for Modern Architectures](https://www.amazon.com/dp/1558602860/) - _TODO_.
  * [Programming Language Pragmatics](https://www.amazon.com/dp/0123745144) - _TODO_.
  * Programming Languages: Application and Interpretation - www , PDF
  * Programming Languages: Theory and Practice - PDF , lecture notes
  * [Programming Languages: Theory and Application](http://cs.brown.edu/courses/cs173/2012/book/) - _TODO_.
  * Project Oberon - 1992 edition , 2013 edition
  * [The SSA Book](http://ssabook.gforge.inria.fr/latest/book.pdf) - _TODO_.
  * Types and Programming Languages - www , Amazon
  * [Virtual Machines, Smith and Nait](https://www.amazon.com/dp/1558609105) - _TODO_.
  * [Virtual Machines, Iain Craig](https://www.amazon.com/dp/1852339691) - _TODO_.
  * Warren's Abstract Machine - Prolog in Haskell - http://www.cvc.uab.es/shared/…

### Papers

### Courses

  * [Compilers Construction, Cambridge](http://www.cl.cam.ac.uk/teaching/1516/CompConstr/materials.html) - an introduction to compiler construction course from the University of Cambridge.
  * [Compiler Construction for Undergrads, RICE University](https://www.clear.rice.edu/comp412/Lectures/) - an introduction to compiler construction and language translators course from the RICE University.
  * Compilers Theory, Stanford - [YouTube](https://www.youtube.com/playlist?list=PLLH73N9cB21VSVEX1aSRlNTufaLK1dTAI), [Stanford.edu](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/), [Class Notes](http://web.stanford.edu/class/cs143/) - an introduction to Compilers theory and construction course from Stanford.
  * [Design and Construction of Compilers, University of Texas](https://lambda.uta.edu/cse5317/) - _TODO_.
    + Lecture Notes: [PDF Document](https://lambda.uta.edu/cse5317/notes.pdf), [Single HTML Page](https://lambda.uta.edu/cse5317/long/long.html).
  * [DSL Design and Implementation Summer School](http://vjovanov.github.io/dsldi-summer-school/) - a Summer School program on the topics of DSL Design and Implementation hosted by the EPFL University.
  * [Foundations of Programming Languages](http://www.cs.cmu.edu/~fp/courses/15312-f04/) - a course that covers many of the concepts underlying the design, definition, implementation and use of modern programming languages from a formal standpoint.
  * [Nand2Tetris: How to Build a Computer from First Principles, Part 2](https://www.coursera.org/learn/nand2tetris2) - This 2nd part of the Nand2Tetris course covers basic language design and elementary compiler construction concepts in addition to many other topics on a basic level.
  * [Programming Languages: Part A, by Grossman](https://www.coursera.org/learn/programming-languages) - Part 1 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming.
  * [Programming Languages: Part B, by Grossman](https://www.coursera.org/learn/programming-languages-part-b) - Part 2 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming..
  * [Programming Languages: Part C, by Grossman](https://www.coursera.org/learn/programming-languages-part-c) - Part 3 of a 3-part course series to the basic concepts of programming languages, with a strong emphasis on functional programming..
  * [Types, Logic, Semantics, and Verification from Oregon University's Summer School](https://www.cs.uoregon.edu/research/summerschool/summer15/curriculum.html) - a Summer School program that consists of 80 minute lectures presented by internationally recognized leaders in programming languages and formal reasoning research.
  * [Virtual Machines and Managed Runtimes, UCB CS294](http://www.wolczko.com/CS294/) - an introductory course on Virtual Machines and Managed Runtimes from the University of Berkeley.
  * [Virtual Machines Summer School 2016 (VMSS 2016)](http://soft-dev.org/events/vmss16/) - VMSS is a Summer School program that aims to give an overview of the field, targeted at early career researchers.
    + [YouTube Videos Playlist](https://www.youtube.com/playlist?list=PLJq3XDLIJkib2h2fObomdFRZrQeJg4UIW).

### Talks and Seminars

* [Single Static Assignment Form Seminar](http://compilers.cs.uni-saarland.de/ssasem/) - an introductory seminar on SSA Form, Compiler Optimizations under it and its applications in other areas such as Program Analysis and Verification.
