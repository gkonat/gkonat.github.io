---
---

<img src="assets/image/small.jpg" alt="Gabriël Konat" style="float: right; margin-left: 20px; margin-bottom: 20px; margin-top: 0px;">

I am a PhD candidate in the [Programming Languages Research Group](https://www.tudelft.nl/en/eemcs/the-faculty/departments/software-technology/programming-languages/) at the [Delft University of Technology](https://www.tudelft.nl/) supervised by [Eelco Visser](http://eelcovisser.org/). I am interested in domain-specific languages (DSLs), language workbenches, incremental execution, and software development pipelines (e.g., build scripts) and and their use in interactive environments such as IDEs.

The overarching theme of my research is *language-parametric methods for developing interactive programming systems*. A language-parametric method takes as input a description of a programming language (such as a DSL), and automatically implements (parts of) an interactive programming system, reducing development effort, thereby making programming language development more feasible.

This page lists my scientific publications and projects I've worked on, my experience and education, and my contact information.

## Publications

2019

Gabriël Konat, Roelof Sol, Sebastian Erdweg, and Eelco Visser: __[Precise, Efficient, and Expressive Incremental Build Scripts with PIE](assets/publication/pie-ic19.pdf)__. IC 2019. [[Link](https://2019.splashcon.org/details/ic-2019-papers/3/Precise-Efficient-and-Expressive-Incremental-Build-Scripts-with-PIE)]

2018

<a name="sbuild"></a> Gabriël Konat, Sebastian Erdweg, and Eelco Visser: __[Scalable Incremental Building with Dynamic Task Dependencies](assets/publication/scalable_incremental_building-ase18.pdf)__. ASE 2018. [[DOI](https://doi.org/10.1145/3238147.3238196)]

<a name="pie"></a> Gabriël Konat, Michael J. Steindorfer, Sebastian Erdweg, and Eelco Visser: __[PIE: A Domain-Specific Language for Interactive Software Development Pipelines](assets/publication/pie-programming18.pdf)__. Programming Journal 2.3 (2018). [[DOI](https://doi.org/10.22152/programming-journal.org/2018/2/9)]

2016

<a name="bootstrapping"></a> Gabriël Konat, Sebastian Erdweg, and Eelco Visser: __[Bootstrapping Domain-Specific Meta-Languages in Language Workbenches](assets/publication/bootstrapping-gpce16.pdf)__. GPCE 2016. [[DOI](https://doi.org/10.1145/2993236.2993242)]

Gabriël Konat, Luís Eduardo de Souza Amorim, Sebastian Erdweg, and Eelco Visser: __[Bootstrapping, Default Formatting, and Skeleton Editing in the Spoofax Language Workbench](assets/publication/spoofax-lwc16.pdf)__. Language Workbench Challenge (LWC@SLE) 2016. [[Link](https://2016.splashcon.org/event/lwc2016-bootstrapping-default-formatting-and-skeleton-editing-in-the-spoofax-language-workbench)]

Gabriël Konat, Sebastian Erdweg, and Eelco Visser: __[Towards Live Language Development](assets/publication/towards-live-language-development-live16.pdf)__. Workshop on Live Programming Systems (LIVE) 2016. [[Link](https://2016.ecoop.org/event/live-2016-paper-4-title-live-language-development)]

2015

Sebastian Erdweg, Tijs van der Storm, Markus Völter, Laurence Tratt, Remi Bosman, William R. Cook, Albert Gerritsen, Angelo Hulshout, Steven Kelly, Alex Loh, Gabriël Konat, Pedro J. Molina, Martin Palatnik, Risto Pohjonen, Eugen Schindler, Klemens Schindler, Riccardo Solmi, Vlad A. Vergu, Eelco Visser, Kevin van der Vlist, Guido Wachsmuth, and Jimi van der Woning: __[Evaluating and comparing language workbenches: Existing results and benchmarks for the future](assets/publication/language_workbenches-clss15.pdf)__. Computer Languages, Systems & Structures 44 (2015). [[DOI](https://doi.org/10.1016/j.cl.2015.08.007)]

2014

Eelco Visser, Guido Wachsmuth, Andrew P. Tolmach, Pierre Néron, Vlad A. Vergu, Augusto Passalaqua, and Gabriël Konat: __[A Language Designer’s Workbench: A One-Stop-Shop for Implementation and Verification of Language Designs](assets/publication/language_designers_workbench-onward14.pdf)__. Onward! 2014. [[DOI](https://doi.org/10.1145/2661136.2661149)]

Guido Wachsmuth, Gabriël Konat, and Eelco Visser: __[Language Design with the Spoofax Language Workbench](assets/publication/language_design_with_spoofax-ieeesoftware14.pdf)__. IEEE Software 31.5 (2014). [[DOI](https://doi.org/10.1109/MS.2014.100)]

2013

Sebastian Erdweg, Tijs van der Storm, Markus Völter, Meinte Boersma, Remi Bosman, William R. Cook, Albert Gerritsen, Angelo Hulshout, Steven Kelly, Alex Loh, Gabriël Konat, Pedro J. Molina, Martin Palatnik, Risto Pohjonen, Eugen Schindler, Klemens Schindler, Riccardo Solmi, Vlad A. Vergu, Eelco Visser, Kevin van der Vlist, Guido Wachsmuth, and Jimi van der Woning: __[The State of the Art in Language Workbenches - Conclusions from the Language Workbench Challenge](assets/publication/state_of_the_art_in_language_workbenches-sle13.pdf)__. SLE 2013. [[DOI](https://doi.org/10.1007/978-3-319-02654-1_11)]

<a name="taskengine"></a> Guido Wachsmuth, Gabriël Konat, Vlad A. Vergu, Danny M. Groenewegen, and Eelco Visser. __[A Language Independent Task Engine for Incremental Name and Type Analysis](assets/publication/task_engine-sle13.pdf)__. SLE 2013. [[DOI](https://doi.org/10.1007/978-3-319-02654-1_15)]

2012

<a name="nabl"></a> Gabriël Konat, Lennart C. L. Kats, Guido Wachsmuth, and Eelco Visser: __[Declarative Name Binding and Scope Rules (NaBL)](assets/publication/declarative_name_binding_and_scope_rules-sle12.pdf)__. SLE 2012. [[DOI](https://doi.org/10.1007/978-3-642-36089-3_18)]

## Projects

### Spoofax

The [Spoofax Language Workbench](http://www.metaborg.org/en/latest/) is a platform for developing textual (domain-specific) programming languages and their corresponding interactive programming systems. In Spoofax, programming languages are specified in declarative meta-DSLs for syntax, static semantics, dynamic semantics, transformations, and editor services. From such a specification, Spoofax generates a parser, name and type analysis, interpreter, compiler, and an Eclipse or IntelliJ code editor with editor services.

Spoofax is a large project with many components that are being worked on in our group. I have worked on several parts of Spoofax:

* __NaBL, TS, and the task engine__ is a framework for incremental name and type analysis in Spoofax. [NaBL](#nabl) is a meta-DSL for declaratively specifying the name and scope rules of a language. TS is a meta-DSL for simple type system specification. The [task engine](#taskengine) is a framework for incrementally executing name and type analysis tasks. NaBL and TS generate a tree traversal for collecting name and type tasks of an abstract syntax tree (AST), which the task engine then incrementally executes.
* __Spoofax Core__ is a project to turn Spoofax, which was fully based on the Eclipse IDE in 2013, into a platform-independent language workbench core which could be integrated with any platform. This required a full reimplementation of the core language workbench logic, as well as a full reimplementation of the integration with Eclipse, Maven, and the command-line. Together with Vlad Vergu, Hendrik van Antwerpen, and Daniel Pelsmaeker, we successfully implemented Spoofax Core and its various integrations. Spoofax Core has powered (and is powering) parts of our research and is being used by Oracle Labs to develop several DSLs.
* __Meta-DSL bootstrapping__ in Spoofax is important, as we want to reap the benefits of our own meta-DSLs to improve our own meta-DSLs. To that end, we have developed a [fixpoint bootstrapping approach](#bootstrapping) that versions meta-DSL compilers, records explicit dependencies between them, and iteratively self-applies meta-DSL compilers until either a defect is found, or a new baseline is created when a fixpoint is found.

### PIE: Pipelines for Interactive Environments

[PIE](#pie) is a DSL, API, and runtime for developing interactive software development pipelines, such as IDEs which need to process events responsively in a live environment, but also incremental build scripts which need to provide timely feedback. With PIE, pipeline developers can concisely write pipeline programs in terms of tasks and dependencies between tasks and files, which the PIE runtime then incrementally executes. We have developed a [change-driven incremental build algorithm](#sbuild) that makes incremental execution of PIE programs scale down to many low-impact changes, while scaling up to large dependency graphs.

## Experience and Education

__2012 - present__

Ph.D. in Computer Science.
*Delft University of Technology*.
Department of Software Technology, Programming Languages Research Group

__06/2013 - 08/2013__, __07/2014 - 09/2014__, __07/2015 - 09/2015__

Research Assistant.
*Oracle Labs* in Redwood Shores, California, United States of America

__2009 - 2012__

M.Sc. in Computer Science (cum laude). *Delft University of Technology*. Specialization: Software Engineering

__2005 - 2009__

B.Sc. in Computer Science.
*Rijswijk University of Technology*. Specialization: Software Development

__2000 - 2005__

HAVO diploma.
*Segbroek College* in Den Haag. Specialization: Nature & Technology

## Contact

Gabriël Konat

Email: [g.d.p.konat@tudelft.nl](mailto:g.d.p.konat@tudelft.nl)

LinkedIn: [gabrielkonat](https://www.linkedin.com/in/gabrielkonat/)
