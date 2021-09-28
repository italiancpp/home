---
title: "Dettagli Meetup Firenze 2015"
layout: splash
permalink: /meetup-0615
---

### C++ and why you care

Relatore: **Gian Lorenzo Meocci**

Negli ultimi 20 anni abbiamo assistito al fiorire di molti linguaggi di programmazione, all’affermarsi di volta in volta di molteplici paradigmi e al susseguirsi di differenti tecnologie legate ad essi. Oggi, in pieno 2015, il C++ è ancora in prima linea soprattutto dopo l’approvazione del C++11 e del C++14. In questo talk cercheremo, tramite semplici esempi, di capire quali sono i punti di forza del linguaggio e quali gli aspetti che dovranno essere migliorati nel corso dei prossimi anni. Non mancheranno confronti con altri linguaggi di programmazione su alcuni punti fondamentali come:

– Performance  
– Maintainability  
– Concurrency

Dal mio punto di vista il C++ paga ancora il conto! Scopriamone insieme le ragioni.

[Slides](http://www.meocci.it/meetup/2015/firenze/C++_Why_YouCare.pdf)


### Introduzione al game-development in C++11/C++14

Relatore: **Vittorio Romeo**

I nuovi standard del C++ hanno reso il game-development un’esperienza molto più piacevole. Features come gli “smart pointers” e le “variadic templates” velocizzano moltissimo lo sviluppo e rendono il codice più pulito e robusto.

Nuove librerie multimediali semplici da usare come SFML, SDL e Cinder rendono la gestione della grafica, dell’audio e dell’input veramente semplice, e si adattano senza problemi ai “principi” del C++ moderno.

Questo talk guida gli ascoltatori attraverso la creazione di un clone di Arkanoid/Breakout in meno di 200 linee di codice, usando features ed idiomi del C++11/C++14. Segmenti di codice cronologicamente sequenziali, compilati ed eseguiti uno ad uno, mostreranno ai partecipanti come si crea un gioco da zero, passo dopo passo. Il risultato finale sarà un piccolo gioco completo, scritto totalmente in codice C++ moderno.

Gli argomenti trattati saranno vari: creazione del “game loop”, gestione delle entità, 2D rendering, rilevamento delle collisioni, e molto altro.

Materiale:

- [Slides](https://github.com/SuperV1234/itcpp2015/blob/master/presentation.pdf)
- [Demo](https://github.com/SuperV1234/itcpp2015)
- [Video](https://www.youtube.com/watch?v=t9PeU5Dc-xY)

### Solving Constraint Satisfaction Problem using monads

Relatore: **Bartosz Milewski**

Constraint satisfaction is one of those problems that are hard to solve using imperative programming. They usually involve exhaustive searches and backtracking. I’m always surprised to see an easy declarative solution in a functional language. I can’t resist the urge to translate it to C++. I did this before with the eight-queen problem and the conference scheduling algorithm. This time I was inspired by Justin Le’s clever solution to a cryptarithmetic puzzle “SEND+MORE=MONEY”.

Materiale:

- [Slides](https://github.com/BartoszMilewski/Publications/blob/master/SolvingConstraintsWithMonads.pdf)
- [Video](https://www.youtube.com/watch?v=2G5MprrtgMs)


### Utilize your CPU power – Cache optimizations and SIMD instructions

Relatore: **Mario Mulansky**

Performance is and always will be a crucial aspect of application development. In recent years, the main focus has shifted towards parallelization and efficient utilization of many-core environments. However, here I will show that in many cases it is worth to address the single-core performance first. Using numerical simulations as an example, I will show how performance can be limited by memory bandwidth rather than CPU throughput. Having identified this bottleneck, I will present strategies to overcome this performance problem. Finally, I will show how to further improve performance by utilizing SIMD instructions with the help of the Boost SIMD library.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2015/06/Mario-Mulansky-Utilize-your-CPU-Power.pdf)
- [Video](https://www.youtube.com/watch?v=RGQ6uYjlYR0)

### Teaching C++14 on Raspberry PI 2

Relatore: **Marco Foco**

E’ possibile insegnare C++14 a principianti?  
E farlo su Raspberry PI?  
Io ci ho provato, e ve ne mostro i risultati.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2015/06/Marco-Foco-Teaching-C-14-on-Raspberry-PI-2.pdf)
- [Video](https://www.youtube.com/watch?v=qMRxNQO3qbI)


### Cat’s anatomy: a C++14 Functional Library

Relatore: **Nicola Bonelli**

The talk presents Cat, a pure functional library implemented in C++14. The contribute of Cat is twofold.

On one hand it aims to fill the gap in the C++ language with respect to functional programming and, to this end, some utility functions and internals of the library are presented.

On the other hand Cat enables generic programming with type classes (inspired by Haskell and Category Theory). A dozen of classes along with the related instances dropped in the context of C++ are presented (Functor, Applicative, Monoids, Monads, Read, Show to mention a few), and some examples and inspiring use-cases are shown.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2015/06/Nicola-Bonelli-Cats-Anatomy-.pdf)
- [Video](https://www.youtube.com/watch?v=i3j0SYzt1MQ)


### **Qt e C++: binomio perfetto**

Relatore: **Luca Ottaviano**

Il C++ sta diventando con ogni iterazione un linguaggio sempre più comodo da usare e con performance ineguagliate; tuttavia la libreria standard fornisce solamente i tipi di base, senza alcun supporto per operazioni di più alto livello. In questo contesto entra in gioco Qt, che con la sua vasta libreria di classi e funzionalità completa al 100% il linguaggio e fornisce numerosi moduli utili in ogni occasione.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2015/06/Luca-Ottaviano-Qt-C-un-binomio-perfetto.pdf)
- [Video](https://www.youtube.com/watch?v=EhUeOQ7ck60)