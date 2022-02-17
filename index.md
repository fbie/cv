---
layout: cv
title: Florian Biermann's CV
---
# Florian Biermann
Software Engineer, PhD in Computer Science

<div id="webaddress">
<a href="florian.biermann@protonmail.com">florian.biermann@protonmail.com</a>
| <a href="https://github.com/fbie">GitHub</a>
| <a href="https://www.linkedin.com/in/fbie">LinkedIn</a>
</div>


## Currently

Tech Lead, Senior Software Engineer at SimCorp.

## Overview ##

Object-oriented and functional programming; weak memory models; concurrency and parallel programming.

`Currently`
C\#, F\#, OCaml, Emacs Lisp

`Previously`
Java, C++, Python, Ruby, Racket


## Education

`2015-2018`
__IT University of Copenhagen, Denmark__

- PhD in Computer Science
- Dissertation: ["Data-Parallel Spreadsheet Programming"](https://pure.itu.dk/portal/en/publications/id(4c3a3148-5ab5-4c8c-82b6-4e623a8789b4).html)
- Supervised by Prof. Peter Sestoft

<details>
<summary>More details</summary>

During my PhD project, I researched techniques for fully automated
parallelization of spreadsheet programs. I implemented these
techniques in Funcalc, a research prototype spreadsheet implementation
that allows for sheet-defined functions, developed by my supervisor.
Over the course of my project, I published three papers investigating
different automatic parallelization techniques:


- data-parallel approaches, including structural re-writing of highly
  parallel spreadsheet cell structures into higher-order, parallel
  functional programs; and
- data-flow approaches for dynamic, whole-program parallelization
  based on optimistic heuristics.

I spent a substantial amount of my PhD at the University of the
Chinese Academy of Sciences (UCAS) in Beijing, where I collaborated
with different researchers.

My teaching tasks included:
- Popular Concurrent and Parallel Programming, ITU, fall 2015;
- Functional programming, UCAS, spring 2016; and
- Popular Concurrent and Parallel Programming, ITU, fall 2017.
</details>


`2012-2014`
__IT University of Copenhagen, Denmark__

- M.Sc. in Software Engineering
- Thesis: "Connected Set Filtering on Shared Memory Multiprocessors"
- Supervised by Prof. Peter Sestoft

`2010-2011`
__Art Institute of Boston, Boston, USA__

- Exchange student

`2008-2011`
__University of Bremen, Bremen, Germany__

- B.Sc. in Digital Media


## Employment

`2018-now`
__SimCorp, Copenhagen, Denmark__

- Senior Software Developer, Tech Lead
- C\#, OCaml and F\#

<details>
<summary>More details</summary>

My work revolves around the implementation of the Trade Manager
application for bookkeeping of OTC derivative trades. In particular, I
work with:

- implementing OTC contract logic in an embedded DSL in OCaml;
- developing and maintaining the DSL interpreter in C\#;
- planning and grooming features together with product owners, system
  architects and other stake holders.

As on of the senior members of the team, I regularly perform
onboarding and coaching of more junior members of the team. As
tech-lead, I spend a significant amount of time advising architects
and project managers in technical matters.

The following list contains some of the projects I have been working
on:

- Improving performance of executing the contract models implemented
  in the OCaml DSL by introducing new data structures that increase
  data-sharing, resulting in hundreds of megabytes lower memory
  consumption.

- A zero-overhead API for the Trade Manager: design and
  implementation, including a C\# embedded DSL for interacting with
  OTC contract objects.

- Implementing a variant of the Cucumber language using this API:
  making lightweight test automation available to non-programmer test
  analysts and resulting in higher quality releases measured by the
  number of customer defects.

- The migration of tests written in an inaccessible legacy OCaml-DSL
  to Cucumber: design of the strategy as an interpreter
  instrumentation and run-time introspection and an initial
  implementation, resulting in more than 600 subtle business logic
  test cases executed multiple times a day and previously making
  hidden documentation about system behavior accessible.

- Designing a new architecture for Trade Manager data import:
  replacing a hard to maintain legacy implementation based on ad-hoc
  recursive calls to implementations of abstract classes by a
  principled approach using continuation-passing style.

</details>

`2014-2015`
__IT University, Copenhagen, Denmark__

- Research assistant
- Java, F\#

<details>
<summary>More details</summary>

I designed and implemented a Java FX virtual-reality application
rendering LEGO construction manuals step-by-step, where the user can
move between steps and manipulate a 3D model of the LEGO model using
only their eyes. This project was showcased at CES 2015.

</details>

`2013-2014`
__Medial Insight A/S, Copenhagen, Denmark__

- Student programmer
- C++, Ruby


## Publications

`2018`
__[Puncalc: Task-Based Parallelism and Speculative Reevaluation in Spreadsheets](https://doi.org/10.1007/s11227-019-02823-8)__.
- with Alexander Asp Bock.
- HLPP '18 and The Journal of Supercomputing.


__[Rewriting High-Level Spreadsheet Structures into Higher-Order Functional Programs](https://doi.org/10.1007/978-3-319-73305-0_2)__
- with Wensheng Dou and Peter Sestoft.
- PADL '18.

`2017`
__[Quad Ropes: Immutable, Declarative Arrays with Parallelizable Operations](http://dl.acm.org/citation.cfm?id=3091971)__
- with Peter Sestoft.
- ARRAY '17.

`2016`
__[Declarative Parallel Programming in Spreadsheet End-User Development](https://pure.itu.dk/portal/files/80807389/ITU_TR_2016_192.pdf)__
- Technical report.

__[Wrist-worn Pervasive Gaze Interaction](http://dx.doi.org/10.1145/2857491.2857514)__
- with John Paulin Hansen, Haakon Lund, Emilie Møllenbach, Sebastian Sztuk and Javier San Agustin.
- ETRA '16.

`2015`
__[A Gaze Interactive Textual Smartwatch Interface](http://dx.doi.org/10.1145/2800835.2804332)__
- with John Paulin Hansen, Janus Aksø Madsen, Morten Jonassen, Haakon Lund, Javier San Agustin and Sebastian Sztuk,
- UbiComp '15

__[A GazeWatch Pototype](http://dx.doi.org/10.1145/2786567.2792899)__
- with John Paulin Hansen, Emilie Møllenbach, Haakon Lund, Javier San Agustin, Sebastian Sztuk
- MobileHCI '15

`2012`
__[The Animation Loop Station: Near Real-Time Animation Production](http://dx.doi.org/10.1007/978-3-642-33542-6_55)__
- with Benjamin Walther-Franks, Nikolaas Steenbergen and Rainer Malaka
- ICEC '12
