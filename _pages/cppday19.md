---
title: "Dettagli C++ Day 2019"
layout: splash
permalink: /cppday19-talks
---

[Slides repository](https://github.com/italiancpp/cppday19)

#### C and C++ as programming languages in automation technology

Speaker: **Stefano Monti**

TwinCAT 3 offers the possibility to program TwinCAT runtime modules in C/C++ languages. If Visual Studio® in the version Professional, Premium or Ultimate is available on the engineering system, then TwinCAT 3 will integrate itself into the existing Visual Studio Shell® in order to  
use the programming language C or C++ in addition to I/O configuration and the IEC 61131-3 for real-time tasks.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/Twin%20Cat%203%20-%20Stefano%20Monti.pdf)


#### Flip Model Design Pattern

Speaker: **Daniele Pallastrelli**

Il problema dello scambio di dati complessi in ambito concorrente tra un produttore e più consumatori è frequente in certi ambiti ma sicuramente non banale.  
Nel mio intervento descriverò una soluzione adottata con successo diverse volte nel campo della diagnostica di sistemi distribuiti, che ho voluto formalizzare secondo l’usuale struttura di design pattern.  
Sarà non solo l’occasione per parlare di architettura, ma anche per approfondire le caratteristiche di concorrenza del C++ moderno.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/Flip%20Pattern%20-%20Daniele%20Pallastrelli.pdf)
   

#### TBB Dataflow: parallelism through computational graphs  

Speaker: **Nicolò Valigi**

This talk will present the Dataflow component of the Intel Threading Building Blocks (TBB) library. While many developers are familiar with TBB’s suite of parallel algorithms and containers, the Dataflow component is less well-known. It implements an elegant and effective high-level approach to concurrency and parallelism. Dataflow programs are described as a computational graph, a series of nodes that share data through messages flowing through graph edges. The TBB runtime takes care of scheduling and executive computation while respecting the dependency information encoded in the graph and maximizing the potential for parallelism. This declarative approach to task orchestration is especially suitable for pipeline of CPU-heavy tasks, like Computer Vision and Robotics. The talk will include an example from these domains, complete with a performance evaluation and a comparison with more manual implementations.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/TBB%20Data%20Flow%20graphs%20in%20Robotics%20-%20Nicol%C3%B2%20Valigi.pdf)

#### Principles of algorithm design in STL  

Speaker: **Francesco Fucci**

The STL algorithm library is a unique example of library design. The principles behind its design have roots in functional programming and abstract algebra. This talk aims to discuss some examples from STL algorithm implementation and the ideas behind the design of the abstractions underlying most of the STL algorithms, comparing with examples from Haskell.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/Principles%20of%20STL%20algorithms%20-%20Francesco%20Fucci.pdf)


#### From Iterators To Ranges — The Upcoming Evolution Of the Standard Library

Speaker: **Valentin Ziegler**

Pairs of iterators are ubiquitous throughout the C++ library. It is generally accepted that combining such a pair into a single entity usually termed Range delivers more concise and readable code. Defining the precise semantics of such Range concept proves surprisingly tricky, however. Theoretical considerations conflict with practical ones. Some design goals are mutually incompatible altogether.


#### The (few) joys and (many) sorrows of cross-compilation

Speaker: **Valter Minute**

The first challenge of running your code on a device with a limited amount of processing power and resources is building it. Many devices can’t run a C/C++ compiler or anyway build your code in a reasonable time.  
Cross-compiling is the best approach to have code you can maintain and manage in a modern way, but this may become quite complicated if legacy code or third party libraries are involved.  
We will focus on Linux based devices and see what are the challenges involved and what are the tools that may help you solve those issue and have good development experience and software that you can run and debug on your target device.  
This talk will show some real world samples and show how to use some modern tools, including containers, to create cross-build environments that work.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/The%20(few)%20joys%20and%20(many)%20sorrows%20of%20cross-compilation%20-%20Valter%20Minute.zip)

#### Idioms: you’re doing it right

Speaker: **Michele Caini**

Many idioms grew with the language and changed their shape. Just think of the detection idiom and its C++98 version.  
This talk is a roundup of those idioms that have benefited from the continuous evolution of the C++ more than others. The goal is to give an idea of how the way we write code has changed in recent years.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/Idioms%20you're%20doing%20it%20right%20-%20Michele%20Caini.pdf)

#### Python bindings in C++

Speaker: **Andrea Pallini**

C++ is well known as a general-purpose programming language created by Bjarne Stroustrup as an extension of the C programming language. It is object-oriented, it has functional features in addition to facilities for low-level memory manipulation. It is almost always implemented as a compiled language. Often, this characteristic makes it fight against other programming languages that are not compiled but just interpreted such as Python. Python is an interpreted, high-level, general-purpose programming language. These two programming languages can be combined using bindings between the two of them. The combination of the two can be extremely useful in large embedded projects where it is important to have a compiled code, fast and with high performances on the devices. At the same time, might be necessary to keep some flexibility on runtime for testing and data computations using scripting languages. This is the use-case of python bindings in the software team of Leica Geosystem  
s.

In this talk, you will learn how to get started with writing python bindings for your c++ project. Furthermore, you will learn how they have been integrated and use in an existing system and how they became essentials in the phase of testing and production.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/C%2B%2B%20Python%20bindings%20-%20Andrea%20Pallini.pdf)

#### An introduction to Monte Carlo Tree Search  

Speaker: **Manlio Morini**

Monte Carlo Tree Search is one of the machine learning techniques at the heart of AlphaGo/Zero, the first computer program to beat the world champion in a game of Go.

It’s elegant and easy to understand, can be used with little or no domain knowledge, and has succeeded on difficult problems (not only in the game area).

As we describe the algorithm, we will write a basic C++ implementation.

Material:

- [Slides](https://github.com/italiancpp/cppday19/blob/master/An%20Introduction%20toMonte%20Carlo%20Tree%20Search%20-%20Manlio%20Morini.pdf)
  
#### MISRA C++: A Subset of C++ for the Development of High-Integrity Systems

Speaker: **Roberto Bagnara**

C++ is increasingly used for the development of safety- and mission-critical systems.  Among other reasons, C++ penetration in these challenging sectors is strongly pushed by market demand concerning new machine learning methodologies and applications such as advanced driver assistance systems.  While C++ improves upon C by providing linguistic support for features that allow programmers writing safer code, C++ presents numerous traps and pitfalls that can easily result into defective, unreadable, unmaintainable and difficult to test software.  Such traps and pitfalls come both from the past (non-definite behavior in the language for historical reasons), the nature (behavior resulting from the possibility of accessing the hardware with low-level constructs), and the evolution (e.g., the rate at which new features are added) of the language.  In this talk we present MISRA C++, a subset of C++ that has been designed to greatly reduce the possibility of unwanted and non-definite program behaviors, and to improve code readability, maintainability and testability.  We will first explain the non-definite behaviors of C++ and their origin.  We will then introduce MISRA C++, its history and evolution and how it is part of a software development process that addresses the requirements of functional safety standards.  We will also cover the planned evolution of MISRA C++ including its relationship with AUTOSAR C++:14.

This talk is given also by **Chris Tapp**:  
Keylevel Consultants Limited and LDRA  
Chairman, MISRA C++ Working Group  
Member, MISRA C Working Group  
Member, ISO/IEC JTC1/SC22/WG23 – Programming Language Vulnerabilities

Chris Tapp is a Technical Specialist at LDRA with more than 30 years’ experience of embedded software development. Graduating from the University of Durham in 1987, Chris has spent most of his career working within the automotive, industrial control and information technology industries. He has been involved with MISRA since 2001 and is currently chairman of the MISRA C++ Working Group and an active member of the MISRA C Working Group. He has been with LDRA since 2007.

#### Panel: _Ask Us Everything_

*All speakers and guests*

Interactive Q/A with all the speakers and a few selected guests on stage.