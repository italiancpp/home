---
title: "Dettagli Italian C++ Conference 2019"
layout: splash
permalink: /conf19-talks
---

[Slides repository](https://github.com/italiancpp/itcppcon19)

#### Allegro Means Both Fast and Happy. Coincidence?

Speaker: **Andrei Alexandrescu**

Sorting and searching. Two fundamental tasks in Computer Science, and definitely among the most studied. Efficient algorithms for sorting and searching are now taught in core undergraduate classes. Are they at their best, or is there more blood to squeeze from that stone? This talk will explore a few less known – but more allegro! – variants of classic algorithms.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/Allegro%20Means%20Both%20Fast%20and%20Happy%20-%20Andrei%20Alexandrescu.pdf)
- [Video](https://youtu.be/zxwKAX7p8GE)
 

#### Concepts in C++20: A Revolution

Speaker: **Rainer Grimm**

The key idea of generic programming with templates is it to define functions and classes which  
can be used with various types. Often it happens that you instantiate a template with the wrong  
type. The result is typically a few pages of cryptic error messages. This sad story ends with  
concepts. Concepts empower you to write requirements for your templates which can be  
checked by the compiler. Concepts revolutionise the way, we think about and write generic  
code. Here is why:

*   Requirements for templates are part of the interface.
*   The overloading of functions or specialisation of class templates can be based on concepts.
*   We get improved error message because the compiler compares the requirements of the template parameter with the actual template arguments.

However, this is not the end of the story.

*   You can use predefined concepts or define your own.
*   The usage of auto and concepts is unified. Instead of auto, you can use a concept.
*   If a function declaration uses a concept, it automatically becomes a function template. Writing function templates is, therefore, as easy as writing a function.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/Concepts%20-%20Rainer%20Grimm.pdf)
- [Video](https://youtu.be/3XYrw1N-Ev4)
 

#### The joys and trials of writing cross-platform C++ code – let tools help!  

Speaker: **Marc Goodner**

Writing high-quality error-free C++ code is a challenging task, let alone when having to juggle multiple platforms at the same time! In this session we will be exploring the many challenges in cross-platform C++ development and how tools can help. What options do I have if my production environment is different than my dev-box? Can I be as productive when working with remote Linux machines? How can I efficiently build and debug CMake projects and how can I acquire open-source libraries? Come see what Visual Studio 2019, Visual Studio Code, CMake, WSL, Vcpkg and more have to offer to make your C++ development much easier in this demo-heavy talk.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/The%20joys%20and%20trials%20of%20writing%20cross-platform%20C%2B%2B%20code%20Let%20tools%20help%20-%20Marc%20Goodner.pdf)
- [Video](https://youtu.be/_e0A74Jzxvc)


#### Vector++ 17  

Speaker: **Davide Bianchi**

Let’s see how to build a modern vector that can serve as the pillar for any geometrical library  
using a little of metaprogramming and the new c++17 language feature: fold expressions.  
What we aim to achieve is a Vector<T, N> of type T and with N dimensions that behaves like  
any other scalar type in scalar conditions, but that is capable to behave correctly when the  
geometrical operations on vectors are invoked.  
In particular, we would like to be able to:

*   sum vectors of the same order, with different types and get, as a result, a vector which has the type according to the performed operation (for instance, float + int = float, then veci + vecf = vecf);
*   invoke cmath functions using as arguments either scalar or other vectors (e.g. pow(vec3f, float) = vec3d, but also pow(vec3f, vec3i) = vec3d);
*   have an easy-to-extend and “soft-typed” code base of vector functions;
*   take advantage of any possible implicit conversion that would be legal with scalars on vectors;
*   be able to almost effortlessly enable/disable the possibility to allow implicit conversion and narrow conversion on vectors.

All this reducing the syntactic noise to its minimum and letting the possibility to extend the library

in a clear and easy-to-understand way.  
As a plus we would like to take advantage of swizzlers like the common shader languages does.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/Vector%2B%2B%2017%20-%20Davide%20Bianchi.pdf)
- [Video](https://youtu.be/c_D_jAh1p-c)

#### Optimizing after the optimizer: Link Time and Profile Guided Optimization

Speaker: **Nicolò Valigi**

Link Time Optimization (LTO) and Profile Guided Optimization (PGO) are two complementary techniques for improving the performance of C++ code beyond what’s normally achieved by optimizing compilers. In most projects, optimization and inlining opportunities are limited because C++ inherits the concept of independent translation units from C. LTO sidesteps this issue by deferring emission of the final binary code to the linker. After turning on LTO, Firefox saw 5% and up improvements in some benchmarks. PGO uses profiling data collected at runtime to optimize decisions made by the compiler, like branch predictions and code placement. This talk will explore LTO and PGO as implemented by clang. We’ll show how to enable these features in an example project, and dissect the generated code to understand how they work.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/Optimizing%20beyond%20the%20Optimizer%20-%20Nicol%C3%B2%20Valigi.pdf)
- [Video](https://youtu.be/ADLIxC-WeMw)

#### Custom tooling for frameworks, libraries and projects using Clang – getting Clazy

Speaker: **James Turner**

Each programming framework or API we use typically brings with it its own history, best-practices and pitfalls. Whether through documentation, trial-and-error or searching Stack Overflow, we eventually figure out the most efficient, performant and correct way to use our frameworks. But like many problems, better tooling can remove much of the pain. In this session we’ll look at a specific example of using the Clang compiler framework to detect outdated practices, inefficient choice of APIs and good old fashioned typos, and even provide automatic fixes to problems when requested.

Besides looking at the specific example, we’ll consider how to apply this concept to any large C++ project, to develop your own checks and automated refactorings. We’ll examine the models of your code which Clang builds internally, and how we introspect and modify those to reason about code, while preserving structure, formatting and comments.

Material:

- [Video](https://youtu.be/z8w-2A0GHW8)


#### The Future of C++ with Modules  

Speaker: **Dmitry Kozhevnikov**

Modules are probably the most anticipated as well as the most controversial feature proposed for the upcoming C++20. It might be viewed as the most revolutionary change in the language ever, affecting the way we structure, write and build our programs.  
The work that’s going on around this feature is very related to the problems we have as IDE developers, so I’m following it very closely and very carefully.  
In this talk, I’m going to talk about:

*   How modules would work for the end user, and how are they implemented in the compiler
*   What are the expected benefits of modules (i.e. “How exacly would they help with build times?”)
*   What are the common misconceptions and misunderstanding about the scope of the modules (i.e. “Modules are supposed to solve package management problem, right?”)
*   What is the history of the current proposal and why it takes so long to get in the standard

Also, by the time of the talk the fate of Modules in C++20 would be decided – they’ll either be  
accepter, so I’ll cover what it means for the rest of the world, or they’ll be postponed for C++23,  
in this case I’ll describe what were the concerns and unsolved problems.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/Modules%20in%20C%2B%2B20%20-%20Dmitry%20Kozhevnikov.pdf)
- [Video](https://youtu.be/yRuxpVo5wJQ)


#### ABI compatibility is not a MAJOR problem  

Speaker: **Javier Garcia Sogo**

Too often, C++ developers tend to ignore ABI compatibility problems and think that incompatibilities are limited to changes in the interface of the library motivated by new features or bugs. However, the ABI can also be affected by the context of the compilation (architecture, compiler, C++ runtime, …) and even by the libraries that we are consuming. Using semantic versioning is not enough.

In this presentation, Javier intends to make clear the difference between API and ABI, source and binary compatibility. He’ll point out the extreme relevance that ABI compatibility has for library developers and give examples of things that affect the ABI and some techniques to minimize that pain. Taking care of ABI stability can become very important when libraries can’t be built always from sources due to very long compilation times, licensing issues or closed source components.

In the last part of the talk Javier will introduce Conan ([https://conan.io](https://conan.io/)) as the right tool to address this problem. He’ll show how many different binaries can be generated by one simple library taking into account some settings (OS, compiler) and options (shared, static), and how the problem becomes more and more complex when the graph of dependencies of your project grows. Conan has some useful tools to help you know and handle the ABI compatibility problem.

Material:

- [Video](https://youtu.be/2Jt4_A8-694)


#### Coroutines in practice  

Speaker: **Alberto Barbati**

Coroutines have been voted into C++20 and at least two major compilers already support them to some extent. They will eventually be available to the main public, but you can experiment with them right today! In this practical talk we’ll see how to write an IPC facility with named pipes on Windows, using coroutines to implement cooperative multitasking in a single-thread application.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/Coroutines%20in%20practice%20-%20Alberto%20Barbati.pdf)
- [Video](https://youtu.be/sUajXn2YCgg)


#### ECS back and forth

Speaker: **Michele Caini**

The first time I heard of the entity component system architectural pattern, I searched on the web for more information. Sadly, I didn’t find many details on the topic nor a single source where the different approaches were described along with their pros and cons, so as to guide the reader from OOP to component-based models.  
In this talk I’ll try to introduce the topic and to explore briefly a few implementations I’ve seen so far.

Material:

- [Slides](https://github.com/italiancpp/itcppcon19/blob/master/ECS%20Back%20and%20Forth%20-%20Michele%20Caini.pdf)
- [Video](https://youtu.be/WB5bRKKGRUk)
