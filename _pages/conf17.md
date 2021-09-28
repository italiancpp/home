---
title: "Dettagli Italian C++ Conference 2017"
layout: splash
permalink: /itppcon17-talks
---

#### C++ executors to enable heterogeneous computing in tomorrow’s C++ today

Speaker: **Michael Wong**

For a long time, C++ has been outpaced by other models such as CUDA, OpenMP, OpenCL, HSA, which has offered Heterogeneous computing capability to enable dispatch to GPU, DSP, FPGA or other accelerators.  
SG14 is an ISO C++ SG that works on low-latency, in the areas of Games, Financial, Embedded programming. One of their mandate is support of heterogeneous in Native C++, without having to drop to some other model as is needed today.  
This talk will describe the first and possibly the most important step towards supporting heterogeneous computing with a description of C++ executors, an interface between concurrency constructs, and the agents/resources, one of which can be a GPU core, or a SIMD unit.  I have led a small group of experts from Google, Nvidia, Codeplay, and NASDAQ, to define a specification to enable separation of concerns in defining where, when, and how execution is done in service of the constructs in existing C++ standard library, Concurrency, Parallelism, Transactional Memory, and Networking TS.  
This talk will help you understand these TSes which currently only works on CPUs and how they will tie together in future to enable execution on accelerators based on C++ models we already have today such as SYCL, HPX, Kokkos, and Raja. This will enable native C++ to be usable on machine learning algorithms on future self-driving cars, or medical devices.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/Keynote%20C%2B%2B%20executors%20to%20enable%20heterogeneous%20computing%20in%20tomorrow's%20C%2B%2B%20today%20-%20Michael%20Wong.pdf)
- [Video](https://www.youtube.com/watch?v=Evz_J9nAL6Y)


#### Lambda out: a simple pattern for generic output

Speaker: **Davide Di Gennaro**

The lecture will show how to adapt the traditional STL-style generic algorithms to C++0x, replacing output iterators with “output functors”

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/Lambda%20out%20a%20simple%20pattern%20for%20generic%20output%20-%20Davide%20Di%20Gennaro.pdf)
- [Video](https://www.youtube.com/watch?v=i9_DG8e3qq8)

#### An overly simple, C++ idiomatic pattern language for message-based product families  

Speaker: **Carlo Pescio**

In questo talk mostro come realizzare un sistema, costituito modularmente da sottosistemi, ognuno dei quali gestisce messaggi, in modo realmente estendibile. Per aggiungere un sottosistema o un messaggio aggiungiamo dei file. Per eliminarli li escludiamo. Nessun file viene mai modificato e l’eseguibile includerà i soli sottosistemi e messaggi richiesti. Non si utilizzano configurazioni esterne, caricamenti dinamici o pseudo reflection. Vedremo anche come alcuni vituperati pattern siano in realtà utili, una volta capite bene alcune simmetrie ed asimmetrie proprie del C++.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/An%20overly%20simple%20C%2B%2B%20idiomatic%20pattern%20language%20for%20message-based%20product%20families%20-%20Carlo%20Pescio.pdf)
- [Video](https://www.youtube.com/watch?v=AS3AqaMxXYA)

#### Monads for C++  

Speaker: **Bartosz Milewski**

Monad is no longer a dirty word at C++ conferences. Ignoring monads got us a flawed design of std::future (monadic “then” and “make\_ready\_future” are to this day experimental). I’ve talked about monads in C++ before, but I never tackled the most mysterious one, the IO monad. Realizing that no amount of abstract nonsense is going to make monads approachable, I decided to explain abstraction through implementation. Once you see how it works, you’ll be surprised what a powerful pattern it is.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/Monads%20for%20C%2B%2B%20-%20Bartosz%20Milewski.pdf)
- [Video](https://www.youtube.com/watch?v=vkcxgagQ4bM)
  
  
#### Costruire un bridge C++ tra NodeJS e C#

Speaker: **Raffaele Rialdi**

Oggi più che mai l’interoperabilità tra linguaggi è strategica per moltissime applicazioni. NodeJS, C++ e .NET sono ecosistemi ben consolidati che risolvono problemi differenti. La loro integrazione non solo è possibile ma può rivelarsi strategica per sfruttare il meglio dei tre mondi e distribuire le competenze all’interno del team di sviluppo.

Nel corso della sessione vedremo un esempio di come sia possibile sviluppare uno strato di interoperabilità che permetta a NodeJS di comunicare con C++ e a catena con una libreria C# sviluppata con il più recente .NET Core.

Sarà un’occasione per vedere cosa si nasconde dietro la libreria V8, cuore di NodeJS, l’hosting del CoreCLR e la tecnica di Reverse PInvoke che permette di eseguire chiamate native verso .NET.

L’esempio più interessante sarà quello di sviluppare una applicazione Electron/Angular2 con un backend misto tra C++ e C#.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/Costruire%20un%20bridge%20C%2B%2B%20tra%20NodeJS%20e%20C%23%20-%20Raffaele%20Rialdi.pdf)
- [Video](https://www.youtube.com/watch?v=Ph_YZEAZrtw)


#### Una libreria di rete asincrona scritta in C++ ispirata a Node.js

Speaker: **Stefano Cristiano**

Racconterò le motivazioni che hanno portato a creare un framework in C++ per programmazione asincrona di rete (e molto altro) ispirato a Node.js.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/A%20Node%20JS%20like%20api%20in%20C%2B%2B%20-%20Stefano%20Cristiano.pdf)
- [Video](https://www.youtube.com/watch?v=VFGUPB5pqpw)

#### Boost vs Qt: What Could They Learn From Each Other?  

Speaker: **Jens Weller**

Having a long history of using boost and Qt, plus visiting both communities for a long time, this talk reflects, on what the boost and Qt communities could learn from each other.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/What%20boost%20and%20Qt%20could%20learn%20from%20each%20other%20-%20Jens%20Weller.pdf)
- [Video](https://www.youtube.com/watch?v=X6lpYGE4TB4)


#### Functional C++ for Fun and Profit  

Speaker: **Phil Nash**

C++11 gave us lambdas in the language for the first time (boost::lambda aside) – so it’s a functional language now, right? There’s a bit more to functional programming than having first class function objects (and I’d even argue we still don’t quite have that). But does that mean we can’t do functional programming in C++? Yes. No. Maybe…  
First we have to define what functional programming actually is – and it may not be quite what you think! Then we need to see what valuable ideas have come out of the functional approach to software design and which ones we can use in C++ to good effect. In the end we’ll see that, while not strictly a functional programming language, we can get quite a long way with immutable data types, persistent data structures, atomic references, and – if you’re not watching carefully – we might even throw the M word in there!  
All this based on real-world experience – not just theoretical.

Material:

- [Video](https://www.youtube.com/watch?v=rxmgkbQrah0)

#### Quicker Sorting  

Speaker: **Dietmar Kühl**

Quicksort is a well-known sorting algorithm used to implement sort functionality in many libraries. The presentation isn’t really about the algorithm itself but rather about how to actually create an efficient implementation of the algorithm: a text-book implementation of the algorithm actually is not that quick (even if the pivot is chosen cleverly). It takes paying some attention to detail to improve the implementation significantly. This presentation starts with a simple implementation and makes incremental improvements to eventually yield a proper generic and fast sorting function. All code will be in C++ but it should be possible to follow the majority of the reasoning with knowledge of another programming language.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/Quicker%20Sorting%20-%20Dietmar%20K%C3%BChl%20.pdf)
- [Video](https://www.youtube.com/watch?v=jz9xIfvAd30)


#### Diversity and Inclusion in Microsoft

Speaker: **Paola Presutto**

“Sii quello che ami essere”. In questa sessione percorriamo i princìpi di Diversity and Inclusion dal punto di vista di Microsoft: raccontiamo la trasformazione della cultura nei confronti della diversità come conduttore di una crescita personale ma anche di business.

Material:

- [Slides](https://github.com/italiancpp/itcppcon17/blob/master/Diversity%20and%20Inclusion%20in%20Microsoft%20-%20Paola%20Presutto.pdf)
- [Video](https://www.youtube.com/watch?v=PyxYWF7GR30)
