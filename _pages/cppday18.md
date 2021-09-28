---
title: "Dettagli C++ Day 2018"
layout: splash
permalink: /cppday18-talks
---

[Slides repository](https://github.com/italiancpp/cppday18)

#### HPX : High performance computing in C++ with concurrency, parallelism and futures

Speaker: **John Biddiscombe**

HPX implements upcoming C++ standards proposals for C++17/20 and beyond, focusing on futures, executors and task based approaches to parallelism. The aim of HPX is to make distributed multi-threaded programming easier and safer so that the developer can focus on algorithm development and worry less about race conditions and concurrent programming tricks, whilst still giving the programmer the low-level tools necessary to fine tune performance. In this talk, I will cover the API basics of futures, continuations and the basics of Task Graphs (DAGs), some examples of executor use and show how CSCS is using HPX for High Performance Codes by exploring task affinity, thread pools, schedulers and how they interoperate with the C++ standard and the many core world of processors (and accelerators).

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Keynote%20HPX%20-%20John%20Biddiscombe.pdf)
- [Video](https://www.youtube.com/watch?v=ScKNrkN2SF4)


#### Unconvex Nesting Optimization

Speaker: **Fabrizio Radaelli**

Optimization problems consists in finding the value of an optimization variable x that minimizes a function F(x) under some constrains. We can distinguish between convex and non-convex optimization problems: while it is certain to reach the optimal value for the optimization variable (i.e. the value of x for which F(x) is at its minimum) when solving problems of the first kind, in the non-convex case it is not guaranteed that the reached minimum of F(x) is a global or a local minimum.  
Despite optimization problems can be solved analytically, in the most of the cases it is requested a numerical approach to optimization. Machine learning, deep learning and, in general, artificial intelligence are based on numerical optimization of non-convex problems.

Here we present an algorithm we developed to solve a common case of non-convex problem: the 2D nesting problem. The goal of a nesting algorithm is to arrange some objects into a container, satisfying some arbitrary criteria (e.g. nest the objects in the most compact fashion). Our method is able to reach a solution in few ms; moreover it exploits a GPU-based geometrical approach and it can tackle nesting problems independently from the size and the shape of both objects and container.

After an introduction about non-convex problems, how they are defined and how they can be solved, we will present the principles of our nesting algorithm and discuss its potential. Next we will introduce a deep learning method to boost the nesting procedure, reaching high precision results without exploiting the nesting algorithm.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Unconvex%20Nesting%20Optimization%20-%20Fabrizio%20Radaelli.pptx)
- [Video](https://www.youtube.com/watch?v=bDYjZsfbPkA) 
   

#### A.I. dalla teoria alla pratica  

Speaker: **Sebastiano Galazzo**

Una introduzione teorica agli algoritmi di machine learning ed A.I. seguita da una panoramica completa dei Microsoft Cognitive Services di Microsoft e la loro integrazione ed utilizzo pratico in C++ tramite il framework Qt.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/AI%20-%20Sebastiano%20Galazzo.pptx)
- [Video](https://www.youtube.com/watch?v=J1fv33NBvP8)


#### Exploring IoT with RTI DDS Connext  

Speaker: **Giorgio Zoppi**

RTI Connext DDS is a C++ framework designed to address the performance, scalability, security and resilience requirements of the Industrial Internet of Things.  
Its architecture is completely decentralized. Applications automatically discover each other and communicate peer-to-peer.  
Initally created for U.S.Navy, nowadays RTI Connext DDS has been employed in many different scenarios: medical hospital, automotive, real time network traffic. At first we will explain you the infrastracture of DDS, its distributed bus structure, performance, quality of service. In second instance we will use a real use case, vehicle tracking in C++14 using RTI DDS as data distribution bus and its “thing” discovery capabilities.  
We will show a fleet vehicle tracking application in C++14 where each vehicle send updates to the DDS and the UI will show us the state of the vehicle. As we guide you through this use case, we will talk about the architecture, the code, and the configuration in a way that it will make easy and fast the deployment of DDS.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Exploring%20IoT%20with%20RTI%20DDS.pdf)
- [Video](https://www.youtube.com/watch?v=GLaj5Vm6jOE)

#### Unevaluated operands: the SFINAE you don’t expect

Speaker: **Michele Caini**

C++11 gave us an extended set of contexts where unevaluated operands appear. SFINAE adepts said thank you and started doing strange things with them.  
Let’s discuss some modern techniques to solve ancient problems.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Unevaluated%20Operands%20-%20Michele%20Caini.pdf)
- [Video](https://www.youtube.com/watch?v=BjVvCZgOE8E)

#### Macro free non intrusive runtime reflection system in C++

Speaker: **Michele Caini**

C++ and reflection are a long debated topic. Sooner or later we’ll see reflection finds its way into the standard. Until then, a non intrusive runtime reflection system is probably the most respectful thing you can do for your colleagues.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Runtime%20Reflection%20-%20Michele%20Caini.pdf)
- [Video](https://www.youtube.com/watch?v=qGUKZWXkM7k)


#### Lessons Learned Developing Evolutionary Algorithms in C++  

Speaker: **Manlio Morini**

Evolutionary optimisation frameworks offer significant ‘off-the-shelf’ optimisation capabilities.  
Many C++ libraries enjoy on-going development and increasing maturity and they can be attractive options for programmers.

This talk describes some key aspects to make an informed choice:

*   evolutionary algorithms (EAs) and the AI / ML landscape;
*   how do they work;
*   (sub-)varieties of EAs;
*   when to prefer other approaches;
*   coding examples;
*   survey of available C++ frameworks.

It also deals with C++ techniques adopted in our open source Genetic Programming framework (Vita) regarding:

*   PRNG;
*   hashing;
*   small vector optimization.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Lessons%20Learned%20Developing%20Evolutionary%20Algorithms%20in%20C%2B%2B%20-%20Manlio%20Morini.pdf)
- [Video](https://www.youtube.com/watch?v=WQoy2BxoCwg)


#### Building a scientific C++ library as front-end of a Fortran library  

Speaker: **Alfio Lazzaro**

Fortran is one of the most used languages for scientific libraries in the High Performance Computing community. In the recent years, there has been a progressive shift in the community to use the C++ language for the development of new libraries. Therefore, it becomes important to allow codes written in the two languages to interplay. Here we present how we built a C++ API to the sparse matrix library DBCSR (Distributed Block Compressed Sparse Row). The library is written in Fortran and is freely available under GPL license. We present the design strategies implemented for the interoperability between C++ and Fortran.


#### Il punto su C++20  

Speaker: **Alberto Barbati**

Il C++20 porterà molte importanti novità al linguaggio. Vedremo come concetti e contratti, feature già ufficialmente approvate, ma anche feature minori come i “class non type template parameters” possono cambiare profondamente il modo di programmare. Ne approfitteremo anche per vedere la situazione delle altre attesissime feature maggiori: moduli, coroutine e range, la cui inclusione nello standard è al momento ancora in discussione.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/Il%20Punto%20su%20C%2B%2B20%20-%20Alberto%20Barbati.pdf)
- [Video](https://www.youtube.com/watch?v=psZPax9TWrk)

#### Cython: Importare il C++ in Python velocemente

Speaker: **Federico Pasqua**

Un introduzione al Cython, un modo semplice e veloce di mettere in comunicazione C/C++ con il Python, seguita dall’analisi di un progetto PyGame + Cython preso come esempio.

Material:

- [Slides](https://github.com/italiancpp/cppday18/tree/master/Cython)
- [Video](https://www.youtube.com/watch?v=Nxc7AQvH6Ws)

#### GIS in C++: cosa si nasconde dietro l’app mappe del tuo smarthphone?

Speaker: **Alberto Bignotti**

Verrà mostrata l’architettura di un componente C++ dedicato allo sviluppo di app Map centriche (Desktop/Mobile). In particolare vedremo alcuni concetti fondamentali di una applicazione GIS:

*   creazione di componenti grafici per il disegno di geometrie e immagini
*   sistemi di coordinate, breve introduzione alla libreria proj4 (https://proj4.org/)
*   interazione con la mappa, mouse + touch gestures
*   manipolazione di geometrie in C++, breve introduzione alla libreria geos (http://trac.osgeo.org/geos)
*   descrizione e esempio di alcuni standard per dati vettoriali e raster (WMS, OpenStreetMap, Bing Maps, GeoJson, WKB/WKT…)
*   esempio di App QML (Desktop/Mobile) per mostrare gli argomenti trattati

Negli esempi, verrà utilizzato il framework Qt per l’interfaccia, C++14 per le componenti core.

Material:

- [Slides](https://github.com/italiancpp/cppday18/blob/master/GISinCPP.pptx)
- [Video](https://www.youtube.com/watch?v=uhUdLcJqMl0)