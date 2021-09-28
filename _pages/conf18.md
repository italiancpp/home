---
title: "Dettagli Italian C++ Conference 2018"
layout: splash
permalink: /conf18-talks
---

[Slides repository](https://github.com/italiancpp/itcppcon18)


#### ABC – Agile, BMWs, and C++: 30+ years as a Software Engineer

Speaker: **Peter Sommerlad**

TL;DR:  
Cool stuff on C++, Developer tools, Agile, Patterns and fancy cars.

This talk will tell some stories of my life where my goal is to rid the world from bad software (which I will surely never reach completely, unless we no longer have hardware to run it on).

From being a Programmer and UNIX trainer as a CS student, over creating Developer tools, writing Patterns and working on other stuff in my first job after graduating, leading a developer team doing C++ Web applications and becoming a professor. Interluded with other interesting stuff about my life, such as the fancy cars that I got and some other interruptions that changed some of my life.

The Pattern movement introduced me to the protagonists of what later became known as Agile. How I incorporated agile practices in my professional life and teaching, such as automated (unit) testing, that I introduced to my team in early 1998 and that I still instill on my students – they will fail without adequate test automation in their project work.

I use C++ since 1989, if I remember correctly, and C from at least 5 years earlier. Having learned vi long before there was something called vim, I no longer recommend plain editors for non-trivial programming. However, creating a C++ IDE was what I subscribed for in my first job 1990. It just took me 20+ years to make something that I would like to have had then and with a lot of work by my students: Cevelop a C++ IDE with support for Agile practices. Since I care about C++ (I never got a big fan of Java, even so I use it), I joined the C++ standardization committee in 2009 and tend to do janitorial work on the library, specifying obvious missing parts or helping others getting their ideas done. Since my father worked the last years of his worklife as a janitor in a factory, that seems to fit my legacy.

Being a teacher by heart and soul, I will definitely provide many hooks for (re-) visiting practical software engineering books and practices that seem to be relevant for the audience. So i hope, the organizers will not regret dragging me in.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/ABC%20Agile%2C%20BMWs%2C%20and%20C%2B%2B%20-%20Peter%20Sommerlad.pdf)
- [Video](https://www.youtube.com/watch?v=k_4f7HImi7o)


#### Coming Soon to a C++ Compiler Near You: Coroutines

Speaker: **Alberto Barbati**

The Coroutine TS has been published in 2017 and at least two major compilers (MSVC and Clang) already provide support for them. What are they and why should I bother learning such an amazing language feature even if it’s not yet widespread?

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Coming%20Soon%20to%20a%20C%2B%2B%20Compiler%20Near%20You%2C%20Coroutines%20-%20Alberto%20Barbati.pdf)
- [Video](https://www.youtube.com/watch?v=itlLZXhRf28)


#### Channels are usefull, not just for water  

Speaker: **Felix Petriconi**

This talk is the natural continuation of my [There is a New Future](https://www.youtube.com/watch?v=vDmQlIeY4z0). The second part of this series will cover _Communicating Sequential Processes_ (CSP) channels which are also offered by the [stlab library](https://github.com/stlab). These channels can be used to create graphs of n:m input/output tasks all running in parallel.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Channels%20Are%20Useful%20-%20Felix%20Petriconi.pdf)
- [Video](https://www.youtube.com/watch?v=-0t2cg3hkOg)



#### Time Travel Debugging in Windows  

Speaker: **Paolo Severini**

How many nights we have spent in the company of a debugger, trying to understand how the process could ever have ended up in such an invalid state? How many times have we wished we could “rewind” and “replay” the execution of a process? Now we can! 🙂  
Time Travel Debugging is a new reverse-debugging technology recently released by Microsoft. It allows to record instruction-by-instruction the execution of your process and then to replay forwards and backwards in the WinDbg debugger.  
In this talk we will take a quick look at this new magical tool.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Time%20Travel%20Debugging%20-%20Paolo%20Severini.pdf)
- [Video](https://www.youtube.com/watch?v=NF8IPyBC91U)


#### Work with C++ on Mac, Linux and Windows with Visual Studio Code

Speaker: **Emanuele Bartolesi**

In this session we will see how we can use Visual Studio Code and some extensions to work with a C++ project on the three major operative system.  
This is a little introduction but after this session you can start to develop your new projects with the best, light and extensible code editors in the universe.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Work%20with%20C%2B%2B%20on%20Mac%20Linux%20and%20Windows%20with%20Visual%20Studio%20Code%20-%20Emanuele%20Bartolesi.pdf)
- [Video](https://www.youtube.com/watch?v=Kma6g3EsiE4)

#### WebAssembly: Native code for the web

Speaker: **Paolo Severini**

In this talk I will present WebAssembly, a virtual ISA now supported by all modern web browsers.  
WebAssembly provides a way to run on the web at near native speed, and safely, code written in C++ (and in other languages).  
We will take a look at what WebAssembly is, how it works, and why it is becoming an important complement to script languages to write great web applications.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Web%20Assembly%20-%20Paolo%20Severini.pdf)
- [Video](https://www.youtube.com/watch?v=s5S3Mkocwyc)

#### Debug C++ Without Running  

Speaker: **Anastasia Kazakova**

Macros, templates, compile-time evaluation and code generation, reflection and metaclasses – C++ tends to hide the final code passed to the compiler under the tons of various names and aliases. Add here the preprocessor that shadows the actual running curve of your program with dozens of alternatives mixed in a non-trivial way. While this allows to avoid boilerplate code and reduce copy-paste and other errors, such an approach demands better tooling support to make the debugging process easier.

To find an error in such a code, one has to continuously read-fix-run it and compare the results with some etalon, or to debug in order to find actual substitutions. But should you really wait until your code is run or even compiled to debug it? Or how to deal with the situations when the code can’t be run on the local machine? A text editor with code completion won’t help, while a smart IDE that “gets” your code can do a better job.

In this talk we’ll see interesting approaches to solving cases like macro and typedef ‘debug’, understanding types when auto/decltype hide them, dealing with different code branches depending on the preprocessor’s pass-through, and other ideas. Some suggestions are already implemented as ready-to-use features in CLion and ReSharper C++, tools for C++ from JetBrains (that means I can show it in action), others are planned for the future. The aim of this talk is to share the workflows supported by the tools that can help C++ developers create better modern C++ code.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Debug%20C%2B%2B%20without%20Running%20-%20Anastasia%20Kazakova.pdf)
- [Video](https://www.youtube.com/watch?v=8Vx_Ah9NtwE)


#### Writing and using compile-time heterogeneous hash table in C++17  

Speaker: **Denis Panin**

During talk, we will write heterogeneous tuple-based hash table from scratch, using C++17 with little bit of boost. And on top of this hash-table we will write small RPC-ish framework, which will use type information from table values. Also, I will discuss about bringing this prototype into production (yes, it’s used in production).

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Writing%20and%20using%20compile-time%20heterogeneous%20hash-table%20-%20Denis%20Panin.pdf)
- [Video](https://www.youtube.com/watch?v=NQ3o2YiuPVs)


#### Zero-allocation & no type erasure futures  

Speaker: **Vittorio Romeo**

The most popular implementations of futures, including std::future, use dynamic allocation and type erasure in order to allow composition of futures into fork/join asynchronous computation graphs. While this overhead is unavoidable when the control flow of the asynchronous graph depends on run-time conditions, it is unnecessary when the “shape” of the computation graph is known at compile-time.

Is it possible to implement composable futures without dynamic allocation and type erasure?  
Is it worth it?

After a brief overview of the upcoming std::experimental::future additions focused on composability, this talk answers these questions showing the train of thought behind the design and implementation of an experimental future library, step-by-step. Running time, compilation time, and generated assembly benchmarks/comparisons will be provided and analyzed.

The code covered in the talk will make use of C++17 language and library features, that will be explained throughout the presentation. The intended audience for the talk should be familiar with most C++11/14 language features and with std::future(or boost::future). Knowledge of C++17 features is helpful but not required.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/Zero-allocation%20%26%20no%20type%20erasure%20-%20Vittorio%20Romeo.pdf)
- [Video](https://www.youtube.com/watch?v=3RfR4C0Wy-w)


#### CppWinRT e il futuro dello sviluppo desktop in Windows

Speaker: **Raffaele Rialdi**

Il progetto cppwinrt è diventato finalmente il tool principe per lo sviluppo sulle maggiori API esposte da Windows e utilizzato dai team di sviluppo in Microsoft.

Si tratta di una ‘projection’ ISO C++17 che permette di utilizzare le API esposte come componenti WinRT. Anche se il beneficio maggiore è tangibile dai developer di applicazioni UWP in C++, questa projection è usabile anche da normalissime applicazioni Console e quindi si configura come un potente alleato nelle applicazioni server.

Durante la sessione scopriremo quali siano le novità di cppwinrt per il desktop ma con un rapido sguardo anche alle applicazioni headless.

Material:

- [Slides](https://github.com/italiancpp/itcppcon18/blob/master/CppWinRT%20e%20il%20futuro%20dello%20sviluppo%20desktop%20in%20Windows%20-%20Raffaele%20Rialdi.pdf)
- [Video](https://www.youtube.com/watch?v=Y-0m0os-ZD8)

#### C++ Barbarian Quiz

Moderator: **Diego Rodriguez-Losada Gonzalez**

*   Show your creativity and C++ mastery
*   25 minutes of crazy C++ questions
*   Prizes for the winners


#### Introduction to Conan C/C++ Package Manager

Speaker: **Diego Rodriguez-Losada Gonzalez**

This talk will do a quick introduction to [Conan C/C++ Package manager](https://www.conan.io/):

*   How to consumer existing packages
*   How to create packages
*   How to develop with conan

The talk will include live demos of all concepts.

Material:

- [Video](https://www.youtube.com/watch?v=3NdIjZNnJ0Y)